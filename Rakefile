require 'yaml'

task :default => :server

desc "Clean up generated site"
task :clean do
  cleanup
end

desc "Build site with Jekyll"
task :build => :clean do
  compass
  jekyll
end

desc 'Start server with --auto'
task :server => :clean do
  compass
  jekyll('--server --auto')
end

desc "Begin a new post"
task :new_post, :title do |t, args|
  require './_plugins/titlecase.rb'
  args.with_defaults(:title => 'new-post')
  title = args.title
  filename = "_posts/#{Time.now.strftime('%Y-%m-%d')}-#{title.downcase.gsub(/&/,'and').gsub(/[,'":\?!\(\)\[\]]/,'').gsub(/[\W\.]/, '-').gsub(/-+$/,'')}.md"
  puts "Creating new post #{filename}"

  open(filename, 'w') do |post|
    system "mkdir -p _posts"
    post.puts "---"
    post.puts "layout: post"
    post.puts "title: \"#{title.gsub(/&/,'&amp;').titlecase}\""
    post.puts "date: #{Time.now.strftime('%Y-%m-%d %H:%M')}"
    post.puts "categories: "
    post.puts "---"
  end
end

desc "Deploy it"
task :deploy => :build do
  sh 'rsync -rtzh --progress _site/ clioweb@clioweb.org:/home/clioweb/clioweb.org/'
end

def cleanup
  sh 'rm -rf _site'
end

def jekyll(opts = '')
  sh 'jekyll ' + opts
end

def compass(opts = '')
  sh 'compass compile -c config.rb --force ' + opts + ' && compass watch &'
end

