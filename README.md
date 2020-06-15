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

*Link to Video*

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
