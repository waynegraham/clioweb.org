---
date: '2008-04-27 14:00:36'
layout: post
slug: part-two-information-architecture-and-organization
status: publish
title: 'Part Two: Information Architecture and Organization'
wordpress_id: '595'
tags:
- information architecture
- sitemaps
- Web Design
- Web Development
- wireframes
---

Before you even write a line of code or color a pixel, the project team should define the information architecture of a site. A lot of people fail to realize that the organization of content greatly affects the design and development of a site. Adding a new section of content months after the design has been finalized can throw a wrench in the design, and developers need some idea as to what content will be used by site visitors before coding. I don't think this content has to exist in its entirety at this stage, but it useful to have a solid sense of what you plan to create. Of course, things come up, and new content may have to be added or the information architecture needs to be changed. This is fine, so long as everyone understands that this adds time to the completing of a project, may require designers and developers on the project to revisit their work, and may require reworking the site architecture.

## Initial Steps

  1. Determine genre
  2. Content inventory/audit
  3. Site Maps
  4. Page wireframes

## Genres

### Collecting Sites/Online Archives

Online archives and online collecting sites provide an interesting challenge to defining site architecture. On one hand, they are challenging because the much of the content itself is continuously updated, and never finished. On the other, it can be easier to narrow down the scope of the _kinds_ of content you want to collect and archive. Thus, collecting sites and online archives need to blend





An example of this kind of project is the [Hurricane Digital Memory Bank](http://hurricanearchive.org). The goal of the project team when organizing HDMB was to feature the contributions from the public, and account for as many different kinds of contributions as possible: audio, video, images, and text. The site architecture of HDMB reflects a blend of hierarchical guidance and fluid exploration by the user, and is flexible enough to account for constantly-updated content, provided by the public.





### Online Exhibits




The goal of online exhibits is to provide a structured, guided presentation of content to the user. Ideally, online exhibits combine an overarching narrative interspersed with relevant exhibit items or objects showcased from the exhibit archive.


In some cases, online exhibits organize content in very hierarchical, guided ways. [Object of History](http://objectofhistory.org), for instance, organizes its content around six featured objects, and asks visitors to explore each of those objects separately, associating additional items, interviews, and text along the way. The structure of each object's exhibit is the same, which helps build comfort and allows users to anticipate how the other exhibits will be presented. 





A more complicated exhibit, like [America on the Move](http://americanhistory.si.edu/onthemove/), offers a variety of ways for users to explore the content. A structured "Exhibit" gives users a chronologically-organized presentation of the content. The "Collection" is a typical archive of items that users can browse by keyword, search. The "Themes" section allows users to explore the content across time, thematically. Multiple options, multiple ways of "reading" the site, allows for more independence on the part of the user to explore how she/he feels.





Both approaches, however, depend on _how_ the project team wants to present the content to the user, and where they want users to focus. Object of History has very specific goals: introduce uses to how historians can use material culture, provide narrative and related items to six key objects, and provide a place for users to try their hand at doing their own exhibits. America on the Move has more general goals: present and document the impact that movement and transportation has had on US history, and provide ways for users to explore that topic as they wish. Both approaches are valid and useful, but both are also reflected in the information architecture of the site.





### Teaching Resources





With sites focused on teaching and learning we have a set target audience: teachers and students first, then the general public. As a result, the IA of the site reflects the needs of the primary audience. While some of the kinds of content may be similar, the manner in which site visitors go to access that content is different. [Women and World History](http://chnm.gmu.edu/wwh/) is an educational site that structures its site to emphasize the teaching resources it offers. Sections like "Teaching Case Studies," "Primary Sources," "Analyzing Evidence," and "Modules" highlight how the site can help teachers to present the history women throughout the world in their classrooms. The titles of sections, the presentation of various content elements, all cater to the audience and the goals of the site.





## Auditing and Displaying Information Architecture





### Site Architecture Visualizations: Site Maps





I generally start thinking about site architecture with site maps, first sketched on paper or a whiteboard, then developed more formally with software like Omnigraffle or Illustrator. Dan Brown, in his book _Communicating Design_, rightly points out that site maps alone can simplify a web site too much, hiding the "spaghetti-like structure that's really there." Brown points out that site maps are a hold-over from a much simply time of web site development, when sites were simply static pages with little dynamic or database-driven interaction. (Brown) Still, I think site maps provide a useful method for visualization relationships among web pages on your site, and provide you with a map for potential avenues through which users can access your content.






{% img /i/site-map1.png Example site map %}


Example site map using Garrett IA stencils in Omnigraffle.








When creating a site map you should strive to:






	
  * Represent the virtual structure of a site with some simplicity.
  * Represent _relationships_ among sections/pages of a site
  * Begin conversation for naming pages and sections (not concrete at this point)
  * Explain _why_ you think those relationships work for the site and for your audience





I use a tool called [Omnigraffle](http://www.omnigroup.com/applications/OmniGraffle/) to develop site maps and user interaction flowcharts. Omnigraffle comes preinstalled with the Garrett IA stencils--which I used in the example site map--and other stencil packages are available for download elsewhere.





### Content Inventory: Spreadsheet





After getting a broader, general sense of the site architecture, its good to start a content inventory for each section and page of your site. This not only help to make the abstract site map  more concrete, it also provides a communication tool between content managers and designers when building web pages. These are very helpful, for instance, for organizing and publishing complicated online exhibits that require lots of outside resources and displaying multiple files on a page.





Spreadsheets can be a quick and easy way to list information architecture. Using a spreadsheet can feel more like creating an "inventory" or "audit" of site content, but it can be useful for hierarchically organizing web pages, their descriptions, and a brief listing of their content. Content inventories are great because it gets you thinking about what content you want to display on each page, divorced from design.





{% img /i/content-inventory.png Example content inventory %}


Example of a content inventory from the online exhibit of [Gulag: Soviet Forced Labor Camps and the Struggle for Freedom](http://gulaghistory.org/nps/).







I used a content inventory when creating the [NPS exhibit for Gulag](http://gulaghistory.org/nps/) a few years ago. With that project, our goal was to recreate an physical exhibit on the web. Thus, the physical exhibit already had set content and organization. The task, then, was to translate the display panels from the physical exhibit into distinct web pages, and make sure that the information displayed on each panel corresponded to the each respective web page. I typically use five main headings:






	
  1. Section - The section title
  2. Page - the title of the page
  3. Location - The URL of the page
  4. Description - A brief description of the page, how it fits with the section.
  5. Contents - Number of paragraphs, word count, figures, images, video, audio, with specific file names to make finding easier.





### Page Content Visualizations: Wireframes





A content inventory is very helpful when beginning the third part of site architecture: page wireframes. Page wireframes belong in the IA stage because they're much less about design (layout, typography, color) and more about the importance of content pieces relative to each other. Additionally, they function as blueprint for what specific content areas should be on each page. It is _extremely_ difficult to design a web page, or code a web page, if you do not know what the site architecture is as a whole _and_ what content will go on the page. Creating and discussing wireframes in the IA stage not only help anticipate specific content pieces for each page, they also help you evaluate how your site organization is represented on individual pages.





> 

	
> 
> Remember, the goal for wireframes is to discuss _relative importance_ of content on a page--_what_ should be important, not _how_ to make it important.
> 
> 







When discussing wireframes, try to steer the conversation away from the design aesthetics of the wireframe and more towards the content delivery of the wireframe. What content does it emphasize? What content does it reduce in importance? Should one piece of content appear more important than others? Is all the content represented on the page? Avoid conversations like "The navigation needs to be on the right," or "The font should be Georgia" in favor of observations like "I think the callouts should be emphasized more than the secondary navigation," or "The item's title should be equally important to the items subheadings," Remember, the goal for wireframes is to discuss _relative importance_ of content on a page--_what_ should be important, not _how_ to make it important. There's plenty of time for _how_ conversations in the design phase. Discussing what goes on the page, and how each page component related to the others, will give the designers good ideas to do their jobs: _design_.





I recommend creating three levels of wireframes: homepage, browse page, show page. Your mileage may vary, depending on your content and type of site, but its good to think about how content is presented differently at different levels of your site. I also use Omnigraffle to draw page wireframes, using [a stencil package by Michael Angeles](http://urlgreyhot.com/personal/resources/omnigraffle_wireframe_palette), but I've also done wireframes on whiteboards, and with pencil and paper. In fact, I would encourage you to start with pencil and paper before creating a more formal wireframe in Omnigraffle.





## Content Delivery





All the planning for information architecture will pretty much go to waste if that content isn't delivered in a timely fashion. Luke Wroblewski suggests visualizing a "content delivery schedule" to keep the development and delivery of content on time. Using a simple calendar or table, you could construct a list of specific pages or sections of content that needs to be delivered, when it's due, and who's responsible for delivering it. An simple example using a table:





	
		

<table>
	<thead>
	    <tr>
	        <th>Name</th>
			<th>URL</th>
			<th>Due Date</th>
			<th>Provider</th>
			<th>Received?</th>
		</tr>
	</thead>
	<tbody>
        <tr>
            <td>Homepage</td>
            <td>example.com</td>
            <td>05.04.08</td>
            <td>John Hawking, jhawking@example.com</td>
            <td>X</td>
        </tr>
        <tr>
            <td>About</td>
            <td>example.com/about/</td>
            <td>05.12.08</td>
            <td>Mary Bailey, mbailey@example.com</td>
        </tr>
        <tr>
            <td>Exhibit One</td>
            <td>example.com/exhibit1/</td>
            <td>05.22.08</td>
            <td>Larry Stevens, lstevens@example.com</td>
        </tr>
    </tbody>
</table>

You could just as easily use a spreadsheet, Google Calendar, milestones in Basecamp, or a wiki page, but the end goals are the same: have deadlines for content delivery and know who should be delivering content.





## Importance of Information Architecture




Here are a few concluding points/summaries about why content management and information architecture are vital:






  * Thinking about content organization gets you thinking more about what kind of site you want to build, who you want to use this site, and how you can best cater to that audience
  * Genres of sites impact information architecture.
  * Scope creep with content--involving both _removing_ content and _adding_ new content--affects decisions in future design/development phases.
  * Begin thinking more abstractly about site architecture (site maps) and end with more concrete thoughts (page wireframes)
  * Be sure that all the steps you take in developing site architecture coincide with the project requirements you set at the very beginning. All work in this phase must ensure the requirements are met.





Once the team has agreed upon the architecture and organization of a site's content, designers can begin working on, you guessed it, design! In the next post I'll discuss the process for coming up with a design for your project!
