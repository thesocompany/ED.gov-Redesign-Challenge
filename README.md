# Ed.gov

Hello! We are The So Company. We are a services consulting firm that provides content, usability, and software development services to government agencies and private sector organizations. Our goal is to make a lasting impact on how technology in government, health care, and other critical service areas can better serve the public and government customers alike.

The So Company Team, a SDVOSB and SBA 8(a), intends to submit a response to any solicitation related to this market research challenge. Furthermore, in a response, we intend to offer fair and reasonable prices. Based on our past performance with other similar federal agencies, we believe an offered price relating to a possible solicitation will satisfy any fair and reasonable threshold.

## Product description
To improve service to and communication with stakeholders and the general public, the Department of Education (“ED” or “Department”) plans to modernize its public-facing website. Accordingly, ED is seeking interactive prototypes for a redesign of ed.gov, the Department’s homepage.

The Department is not seeking a run-of-the-mill refresh but rather a creative redesign that maximizes user experience and proposes new innovations in layout, typography, animation, illustration, video and photography, and other modern advances.

The redesign of ed.gov should engage the American public, amplify the Secretary’s message, and advance ED’s policy goals, while maintaining high availability and high performance.
 
## Our Solution
We hypothesized that if we create a website design that is elegant and clean, with a simple and modern aesthetic that integrates human-centered design (HCD) principles, we can provide a website that maximizes user experience. We would also use new adaptations and innovations in color, layout, typography, animation, and illustration. If we also incorporate plain language content to effectively communicate with users and a modern FedRamp-approved tech stack, the website redesign can be sustainably implemented.

Requirements to complete this hypothesis include utilizing the Digital Services Playbook and USWDS design system with Department of Education branding. The So Company (TSC) followed these requirements and implemented our hypothesis. 

## Our Approach
To build the ed.gov website redesign prototype, not only did we utilize the USWDS design system, we also ran plays 1, 2, 3, 4, 7, 8, 9, 10, 11, 12, and 13 of the Digital Services Playbook. 

(Plays 5, “Structure budgets and contracts to support delivery” is  more applicable to our government partners, so we did not address those.) Please see the Our Process section to understand more details of our process, our discoveries, and how we utilized the playbook. 

## Design
### View The Prototype
To access The So Company’s clickable prototype, please click the following links:
1. [Homepage](http://edgov-site.s3-website.us-east-2.amazonaws.com/)
2. [Program office page](http://edgov-site.s3-website.us-east-2.amazonaws.com/contact/offices/)
3. [Informational page](http://edgov-site.s3-website.us-east-2.amazonaws.com/student/student-loans/forgiveness/)
4. [Grant page](http://edgov-site.s3-website.us-east-2.amazonaws.com/student/grants/federal-work-study/)
5. [Contact Page](http://edgov-site.s3-website.us-east-2.amazonaws.com/contact/)
6. [News Page](http://edgov-site.s3-website.us-east-2.amazonaws.com/news/)

*Also of note is the* [mobile version](https://xd.adobe.com/view/47f6f21b-46b8-4e52-6c67-aad1b873b1a1-31c7/?fullscreen&hints=off) *of these designs*. 

This prototype was designed in Adobe XD and deployed to an AWS site within an iframe for a more enhanced viewing experience. For more information about our tech stack and process, see the below sections. 

Because this is a prototype rather than a fully developed website, these Adobe XD designs are not mobile responsive. However, we have designed a responsive strategy, linked above. Please note that these designs do not have the same full clickable functionality as the desktop designs, as they are meant simply to serve as an example of mobile responsiveness. 

TSC also created [a short video](https://www.loom.com/share/77f9589c0547441bb8a23abc8d7b37fa) to assist in explaining our submission and documentation. 

### Research Plan 
We developed a research plan [(link)](https://github.com/thesocompany/ED.gov-Redesign-Challenge/blob/master/user-research/research-plan/researchPlan-06012020.pdf) that included conducting an information architecture audit, conducting three direct interviews, and creating personas and stories [(link)](https://github.com/thesocompany/ED.gov-Redesign-Challenge/blob/master/user-research/user-stories/userPersonasJourneys-06082020.pdf). We also have post-MVP research procedures if we are selected for this redesign. Our research plan indicated three essential user types for ed.gov: teachers and school staff, parents, and applying college students. Based on web search data collected from data.analytics.gov, from June 3 to June 8, we discovered top site visits for subdomains were nces.ed.gov and eric.ed.gov, and the latest CARES Act information. We used this data point  for our information architecture audit on content strategy and proceeded with directed interviews to understand the current pain points of our identified audiences. 

From our So Company research groups, we gathered three key participants for our directed interview. All signed our user consent forms for participation. The directed interview had questions aimed at:
1. understanding the intended objectives of our user personas with the current information on ed.gov,
2. identifying current user journeys, and
3. developing user empathy in our redesign.

Highlights from our directed interviews included:
- “Information isn’t laid out in any sort of organic, or simplified manner. Have to go through scattered blocks of text and hyperlinks to figure out which one is going to get me close to what I want....Why would you not have COVID-19 messaging featured on the page - instead of a little picture you have to scroll down for? Then I get sent to just another random list of links? Seems like the department doesn't consider public health a concern, especially since most parents are trying to deal with schools being potential hotbeds for infection.” —Parent, 32 
- “I am surprised that you can’t even access IDEA information on this website through the search feature. I think that is a major failure of this website. ... Yes, there is not K-12 information easily broken down into its own part of the website with resources for parents and teachers linked and outlined.” —Middle School Teacher, 30
- “It’s not particularly engaging, which is fine for a website that mainly exists as a conduit to information - but it doesn’t feel particularly optimized for that either. Perhaps. I think I’m more likely to directly go to the websites that ed.gov connects you to. I could proceed straight to studentaid.gov or fafsa.ed.gov from a google search without interacting with the main page at ed.gov.”—Applying Graduate Student, 27 
 

### Navigation and Site Layout

![existing navigation](https://github.com/thesocompany/ED.gov-Redesign-Challenge/blob/master/product-design/wireframes/Existing%20Navigation.png)


*Existing ed.gov navigation*

The current navigation has many levels, and sometimes information is difficult to find. For example, in the case of the grants page for the Federal Work Study Program, TSC was only able to find it via the search bar functionality. 

With this and user research in hand, TSC’s first major innovation for ed.gov is the use of a drop-down menu navigation system that organizes information based on user persona. One user interview confirmed the necessity of this technique by specifically suggesting it, unprompted. Our easy-to-navigate interface ensures that each user will find the kind of information most important to them.

In combination with the drop-down menus, we also created a left navigation bar for more specific subject exploration. This left navigation is highly specific to the subject matter and functions in a simulated “step-by-step” manner. View the [grants page](http://edgov-site.s3-website.us-east-2.amazonaws.com/student/grants/federal-work-study/) to see this functionality. 

![redesign navigation](https://github.com/thesocompany/ED.gov-Redesign-Challenge/blob/master/product-design/wireframes/Redesign%20navigation.png)

*Redesigned site navigation*

To make this navigation innovation most effective, a full information architecture (IA) discovery, audit, and design process will be needed. IA is the structural design of shared information environments, the art and science of organizing and labeling websites, intranets, online communities, and software to support usability and findability. Typically, it involves a model or concept of information that is used and applied to activities which require explicit details of complex information systems. These activities include library systems implementation and database development. For this exercise the TSC Team did preliminary research and compiled a list for navigation menus which can be seen within the clickable prototype. 


### Style
The clickable prototype utilizes USWDS components styled to include the existing ED color scheme and seal. TSC’s discovery efforts revealed the current ed.gov design includes a large variety of colors and fonts, as can be seen in some of the below images. An important aspect of modern design is to utilize a streamlined style guide. 

To this end, the TSC Team created a preliminary style guide utilizing greens and blues in a specific hue but a variety of tones. For fonts we choose Public Sans and Merriweather, both USWDS-approved fonts. 

As you can see below, the actual color styles of the current ed.gov design have a large variety. This large range can lead to a feeling of a disconnected design. In an attempt to make a cohesive color system, TSC utilized the existing primary color scheme to create a three-tone green, blue, and neutral palette. 

![existing ed.gov colors](https://github.com/thesocompany/ED.gov-Redesign-Challenge/blob/master/product-design/design-files/style%20guide/Original%20Color%20Scheme.png)
*Existing ed.gov colors*

![existing ed.gov colors](https://github.com/thesocompany/ED.gov-Redesign-Challenge/blob/master/product-design/design-files/style%20guide/Redesign%20Colors.png)
*TSC’s redesigned ed.gov colors scheme*

The existing ed.gov typography system suffers from the same large variety and disconnected design. Again, TSC created a cohesive system, in this case utilizing USWDS fonts: Public Sans for the majority of uses including navigation and body text, and Merriweather for titles and headers. 

Public Sans is an open-source sans serif typeface designed and maintained by USWDS and derived from Libre Franklin. It has a plain, straightforward style, appropriate for interfaces and running text. Its large x-height makes it legible at small sizes, and it features a broad range of weights. These features make it a strong, neutral, principles-driven typeface for text or display based on a traditional American form.

![existing ed.gov colors](https://github.com/thesocompany/ED.gov-Redesign-Challenge/blob/master/product-design/design-files/style%20guide/Original%20Fonts.png)
*Existing ed.gov typography*

![existing ed.gov colors](https://github.com/thesocompany/ED.gov-Redesign-Challenge/blob/master/product-design/design-files/style%20guide/Redesign%20Fonts.png)
*TSC’s redesigned ed.gov typography*

Merriweather is an open-source serif typeface designed for on-screen reading. The combination of thin and thick weights gives the typeface stylistic range while conveying a desirable mix of classic, yet modern, simplicity. Merriweather communicates warmth and credibility at both large and small font sizes.

Public Sans is a highly versatile typeface that TSC utilized as the main font throughout the website. Merriweather is used for titles to create an interest while maintaining readability and consistency throughout the design. By choosing these fonts, we gained built-in 508 accessibility compliance. 

### Imagery
Images are great for supporting any related content on a webpage; however, they lack scalability. If a web design showcases an image for a specific part of the design, chances are you will have to supply multiple resolutions of that image to adhere to most devices. Icons, on the other hand, communicate meaning in a graphical user interface while supporting scalability, a modern aesthetic, and consistent styling. 
You will also notice that on websites modernized by USDS and USWDS’s standards that pictures and videos are a rarity. This is often done to keep the designs clean, visuals consistent, and content editable as information changes. 

As ed.gov content is often informative, TSC’s Team determined that an icon-based strategy would be more appropriate. We did provide one image on the home page, a hero image, to provide an exciting visual at the introduction of the site. We also choose to use a pattern-based image, as this strategy is optimal for all device sizes. 

### Page Strategy
In addition to the overall modernized redesign, TSC implemented specific innovations for each page. Below is an overview of these changes:
- [Homepage](http://edgov-site.s3-website.us-east-2.amazonaws.com/)
  + Reduced the number of links and repetitive information by reorganizing and utilizing a drop-down menu.
  + Moved coronavirus information to an upper banner as our research showed it was the most visited page.
- [Program office page](http://edgov-site.s3-website.us-east-2.amazonaws.com/contact/offices/)
  + This existing page currently houses links rather than content. To eliminate this kind of page and reduce the number of visited pages, as is a best practice, we instead moved the linked content directly to the page.
  + Most of the content is technical and legal. Due to the dense nature of such content, TSC placed these items into collapsible boxes for easier information absorption.
- [Informational page](http://edgov-site.s3-website.us-east-2.amazonaws.com/student/student-loans/forgiveness/)
  + This existing page currently houses links rather than content. To eliminate this kind of page and reduce the number of visited pages, as is a best practice, we instead moved these links into the drop-down and left navigations. 
  + If links are required, they are contextualized and shown as buttons. 
- [Grant page](http://edgov-site.s3-website.us-east-2.amazonaws.com/student/grants/federal-work-study/)
  + Again, we chose to reduce the number of links and pages by moving the links to the drop-down and left navigation, and moving the content onto the single page. 
  + TSC created a subway map to simply and visually explain a how-to process and lead users to the next step in the process.  
- [Contact Page](http://edgov-site.s3-website.us-east-2.amazonaws.com/contact/)
  + Our analysis of this page showed that much of this content should be moved to other pages found in the navigation drop-down menu. While content is not evaluated, we would like this page to show the value of proper information architecture.
  + The specific location and phone number information is highlighted in blue for an easy-find experience. 
- [News Page](http://edgov-site.s3-website.us-east-2.amazonaws.com/news/)
  + Again, we choose to reduce the number of links and pages by moving the links to the drop-down and left navigation, and moving the content onto the single page.

### 508 Accessibility
The TSC Team utilized the USDWS design system to ensure inherent 508 accessibility compliance; this includes considerations in choice of fonts and colors. Any website utilizing this prototype template would require a full 508 audit before deployment.

## Content
### Information Architecture
The key findings from our discovery and user persona research revealed that information architecture (IA) and menu structure for ed.gov can be greatly improved with more UX research and feedback. 

The current IA of ed.gov has many broken links throughout the site or links that bring the user to unexpected content. There is a significant need for an audit to identify these issues. 

A successful IA should be directed by a sound content strategy. IA is required to deliver the message quickly and communicate accurately. Users expect to easily understand, relate, and share information in any environment

As stated about in the Navigation and Site Layout section, a full IA discovery, audit, and design process will be needed before any deployment of a new ed.gov website. 

### Content Strategy Insights
While content is not a consideration of this particular challenge, it is an important aspect of any website, especially one as information-driven as ed.gov. To this end TSC would like to offer some insights. 

To design a reusable content model for ed.gov, a vendor must develop and document a
content structure and style guide that can be built out in the publishing/authoring CMS
environment to ensure consistency across all future ed.gov content (with enough flexibility to
allow room for different types of content). Specifically, some suggested required elements would be: 
- An editorial style guide and error messaging style/dictionary
- A structured approach to applications (e.g., intro page > application > after you apply)
- Content around tools, profile, dashboard, etc.
- Static pages for all authenticated tools

The content should be presented in a way that makes sense to the end user, because the
content should be easy to digest. Ultimately, the goal is to present content to help users
find what they need.

### Plain Language
TSC recommends end-to-end content strategy and management, including plain language writing and editing efforts. To assist this effort we also suggest the creation of a plain language content style guide. For our prototype, rather than create a full set of guidelines, we included content utilizing plain language best practices to illustrate the effectiveness of the strategy. 

Some plain language content best practices to consider include:
- Accuracy 
- Consistency in editorial style (established via brand consolidation work) 
- Feedback from users (via user experience research) 
- SEO best practices

## Tech Stack
### Suggested Solution
We understand that ED is looking to tie robust design and content to accessibility, work closely with administration and staff offices to drive change quickly, and ensure students and parents, press, educators and administrators, state and local officials, non-profit stakeholders, representatives from community organizations, and advocates all experience the direct impact of these efforts. In utilizing human-centered design as a core capability, we are striving to create a unified customer experience, delivering unparalleled tools and experiences for everyone ed.gov serves.

Our solution is a "headless" CMS for content management and production, and a flexible and modern UI framework for the front end. 

![headless cms chart](https://github.com/thesocompany/ED.gov-Redesign-Challenge/blob/master/devops/headless%20drupal%20chart.png)

We propose continuing to use Drupal for the "headless" CMS and React via Next.js to serve the content. 

React is a modern, fast, scalable, and simple open-source Javascript library that is used for building attractive user interfaces handling the view layer for web and mobile applications.
When content is published in Drupal, the Next.js React front end will retrieve the content from the Drupal API and Next.js, which generates the static site for public access.

Ed.gov content producers will maintain content with the “headless” Drupal installation, using its standard content management administrative user interface. Aside from the differences in publishing a website, where you can have a Drupal front end, in our “headless” proposal, content producers would encounter a standard setup familiar to regular Drupal users.

![write once, read anywhere chart](https://github.com/thesocompany/ED.gov-Redesign-Challenge/blob/master/devops/write%20once%20chart.png)

Content will be distributed via Drupal’s API in a “raw” format (using the standard web serialization format JSON) and consumed by Next.js React for transformation into formatted HTML and eventual distribution as the public website. Access to raw, unformatted content through the API gives ed.gov flexibility to deploy content to other target platforms, including future native mobile applications. 

This setup is flexible and has the ability to support all operating systems, browsers, and screen sizes.


### The Prototype
The prototype utilizes USWDS design system components executed with static HTML and Javascript for the header and navigation and displaying the page layout and content in an XD file embedded in an iframe.

## Our Process
The So Company Team methodology focuses on Agile and human-centered design. Here is an overview of our process for implementing a project such as ed.gov redesign and development.

### Coordinate kick-off meeting with stakeholders
The Team begins each project with a collaborative kick-off meeting with stakeholders, including the product owner and other stakeholders who bring an understanding of the needs of the product as well as broader processes and technical environments. The Team comes to this meeting prepared with an understanding of the product needs as defined in the initial product request, as well as a curated list of questions from Team members to begin the conversation of uncovering the bigger picture and underlying needs, offline processes, and risks. The Team further asks for additional stakeholders and end user groups who will use or be impacted by the product in order to begin deeper discovery efforts.

### Define product charter
Informed by the kick-off conversation, the Team works to create a clear and succinct problem statement along with a product charter outlining the product’s vision, scope, objectives, budget, risks, milestones, key stakeholders, and end users. The Team collaborates with the product owner and key stakeholders to ensure alignment on the charter as the product’s “north star.”


### Define roles and responsibilities
In alignment with USDS Play #6 (Assign one leader and hold that person accountable), the Team ensures that roles and responsibilities are clear to everyone from the start, including all Team members and stakeholders. The Team assigns one main product manager from The So Company to be responsible for the Team’s delivery of a product solution, and works with the client to identify and agree on a product owner on the client side who is invested with the authority to make decisions.


### Create discovery report
In alignment with USDS Play #1 (Understand what people need) and Play #2 (Address the whole experience, from start to finish), the Team engages in an initial discovery and framing stage. This involves:
- Additional stakeholder interviews, with directed product questions, to better understand all of the potential online and offline interactions a user may have with the product, pain points in the current process and interactions, and other products or services that may be intertwined with the product of focus. All user interviews and user testing are conducted with signed consent forms and acknowledgment from participants.  
- Review and assessment of technological or legislative constraints to set metrics and goals. 
- Review of available analytics for current and legacy systems and products.
- Development of a clear and comprehensive user research plan. 

### Refinement and design
- **Engage in UX research activities to deepen understanding of the problem we’re solving**:** Aligning with USDS Plays #1 and #2, the Team works in collaboration with the client product owner to create a comprehensive user research plan. The Team tailors research activities to the scope of product needs. Informed by UX research activities, the Team works to build personas, journey maps, and additional artifacts to help lead design activities and keep everyone focused on user-centered needs and goals.
- **Generate and prioritize solutions through co-creation labs, prototyping, and rapid testing**: From the results of user research activities and insights, the Team works to rapidly iterate on design solutions, collaborating closely with stakeholders and users throughout the design process. The Team tailors design activities to the needs of each specific product and syncs continuously with content and development teams to prevent information bottleneck. 
- **Develop compelling user stories and new product user flows**: Throughout the design phase, the Team collects insights from stakeholders to build out a fluid user story map 

that captures the overarching story—as well as the many short user stories that work together and target user pain points to be addressed. The Team constantly revisits this user story map to prioritize the user needs and product features to get to an MVP 1.0—and map other features to be addressed post-MVP. The Team product manager ensures that the project taskboard (Github, ZenHub) always reflects the latest prioritization of new user flows and that reprioritization user stories are raised and addressed immediately as they arise. This is so that the full Team and partners remain in close alignment throughout.

### Product development
We approach a new product with a plan that addresses the whole experience, from start to finish, with a prioritized backlog to address future iterations. We do so by integrating from the start an Agile framework that lets us develop, build, deploy, and test quickly and efficiently. Within the product development plan, we provide a product charter and proof of concept (PoC) checklist. These items define the product vision and articulate potential users of the product, as well as what problem we are solving. From the beginning, we incorporate stakeholder input and feedback so that needs and concerns can be at the forefront of the product’s “north star.” We then create an objective-based roadmap that outlines the following and serves as a basis for our “Sprint 0”:
- **Epics** are themes of work that contain issues (stories) needed to complete that larger goal. Issues are related to the subject.
- **Milestones** are sprints that can be tracked from start to finish. Ticket timelines are estimated, enabling us to generate burndown charts, velocity reports, and release schedules. Issues are related by blockers or dependencies. 
- **The backlog** contains all features, updates, bugs, and issue fixes to be planned for the next sprint, with the label of “enhancement” and assigned to a milestone.  Features are reviewed and prioritized accordingly at the end of each day before the scrum takes place the following workday. Built features are turned over to quality assurance and user research teams for testing. This is a validation phase to ensure the Team is maintaining quality and security of the product build while also fulfilling the users’ needs. Results of testing—and any feature identified as feasibly buildable—from the previous sprint gets filled into the backlog for the next iteration. This also helps to mitigate risk in development.

## Conclusion
The Company Team submits this interactive prototype for a redesign of ed.gov. Our submission is a creative redesign that maximizes user experience and proposes new innovations in layout, typography, illustration, and photography, and other modern advances. We also consent to the challenge Official Rules, Terms, and Conditions. 
