---
layout: post
title: 'The White House Releases An Open Data Strategy'
url: 'http://apievangelist.com2013/05/11/the-white-house-releases-an-open-data-strategy/'
image: 'http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/blog/obama-white-house-open-data.jpg'
---
{% include JB/setup %}
<table cellspacing="3" cellpadding="5" align="right">
     <tbody>
          <tr>
               <td align="center">
                    <img src="https://s3.amazonaws.com/kinlane-productions/federal-strategy/obama-white-house-open-data.jpg" border="0" width="300" />
               </td>
          </tr>
          <tr>
               <td align="center">
                    <strong><a href="http://www.flickr.com/photos/whitehouse/8638883692/" target="_blank">Photo Credit - White House</a></strong>
               </td>
          </tr>
     </tbody>
</table>
<p>
     President Obama issued an Executive Order this last week - <a href="http://www.whitehouse.gov/the-press-office/2013/05/09/executive-order-making-open-and-machine-readable-new-default-government-">Making Open and Machine Readable the New Default for Government Information</a>. A move that will signficantly define the fast growing API economy.  But before I dive into what this means for open data and APIs, I wanted to recap the last year of progress in Washington when it comes to open data and APIs.
</p>
<p>
     If you recall, in May of 2012, the White House issued the <a href="http://www.whitehouse.gov/sites/default/files/uploads/2012digital_mem_rel.pdf">Memorandum on Building a 21st Century Digital Government</a>, which provided federal agencies with a 12-month roadmap to get familiar the concept of possessing a healthy digital strategy, which involves taking a strategic approach to using social, cloud computing and mobile, with open data and APIs as the core.
</p>
<p>
     After reading the directive from the White House in 2012, I wrote <a href="http://apievangelist.com/2012/06/01/barak-obama-directs-all-federal-agencies-to-have-an-api/">Barack Obama Directs All Federal Agencies to Have an API</a>, which is still one of the most viewed posts on API Evangelist, after <a href="http://apievangelist.com/2012/01/12/the-secret-to-amazons-success-internal-apis/">The Secret to Amazons Success Internal APIs</a>.
</p>
<p>
     While I am a believer in both APIs and the potential of healthy government leadership, I'm also very skeptical of blind API faith and of our federal government to deliver on open data. After reading the directive out of the White House last year, I got to work understanding, tracking and quantifying the potential and progress coming out of Washington when it comes to open data and APIs.
</p>
<p>
     The important thing to understand about the White House Digital Strategy, is that it doesn't just say open up APIs to support open data and mobile iniatives, it also says to make these efforts discoverable by providing a HTML, JSON and XML version of each agencies digital strategy--making their strategy and resulting data sets not just machine readable, but also machine discoverable. This is the critical aspect of the digital strategy, which will act as the gears in the government fueled API economy, but it also gave me an idea on how to measure the progress of each agency in the Digital Strategy and resulting open data efforts.
</p>
<p>
     All federal agency were directed to develop a digital strategy around open data and mobile, then publish it at their website in HTML, XML and JSON. So I got to work quantifying this. I wanted to understand which agencies had done this successfully. To begin I needed a list of federal agencies, which I was able to pull from the <a href="http://www.usa.gov/About/developer-resources/federal-agency-directory/index.shtml" target="_blank">Federal Agency Directory API</a>. Now I had a database of each agency name, abbreviation code and URL. Next I wrote a script that "pinged" each agencies URL and looked for http://[agencyname].gov/digitalstrategy.html, http://[agencyname].gov/digitalstrategy.xml and http://[agencyname].gov/digitalstrategy.json. I ran this script each night to see who had published their strategy.
</p>
<p>
     Coming up on a year after the release of <a href="http://www.whitehouse.gov/the-press-office/2012/05/23/presidential-memorandum-building-21st-century-digital-government">Memorandum on Building a 21st Century Digital Government</a>, we have <span >0 "agencies" that have published a digital strategy:
</p>
<table >
     <tbody>
          <tr>
               <td colspan="2">
                    <table cellpadding="1" width="100%">
                         <tbody>
                              <tr>
                                   <td width="80%" align="left">
                                        <strong>Federal Agency Digital Strategies</strong>
                                   </td>
                                   <td width="10%" align="center">
                                        <a href="https://gist.github.com/kinlane/5564677" target="_blank" title="Script for Display"><img src="https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-code.png" border="0" width="25" /></a>
                                   </td>
                                   <td width="10%" align="center">
                                        <a href="https://raw.github.com/kinlane/federal-government/gh-pages/data/federal-agencies-digital-strategy.json" target="_blank" title="Raw JSON Data"><img src="https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-json-data-store.png" border="0" width="25" /></a>
                                   </td>
                              </tr>
                         </tbody>
                    </table>
               </td>
          </tr>
     </tbody>
</table>
<p>
     Across these <span >0 agencies, there are <span >0 published datasets to support 2.2, which was to make high-value data and content in at least two existing major customer-facing systems available through web APIs, apply metadata tagging and publish a plan to transition additional high-value systems:
</p>
<table >
     <tbody>
          <tr>
               <td colspan="2">
                    <table cellpadding="1" width="100%">
                         <tbody>
                              <tr>
                                   <td width="80%" align="left">
                                        <strong>Federal Agency Digital Strategies 2.2</strong>
                                   </td>
                                   <td width="10%" align="center">
                                        <a href="https://gist.github.com/kinlane/5564708" target="_blank" title="Script for Display"><img src="https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-code.png" border="0" width="25" /></a>
                                   </td>
                                   <td width="10%" align="center">
                                        <a href="https://raw.github.com/kinlane/federal-government/gh-pages/data/federal-agencies-digital-strategy-2-1-2-with-social.json" target="_blank" title="Raw JSON Data"><img src="https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-json-data-store.png" border="0" width="25" /></a>
                                   </td>
                              </tr>
                         </tbody>
                    </table>
               </td>
          </tr>
     </tbody>
</table>
<p>
     Across these <span >0 agencies, there are <span >0 published services in support 7.2, which was intended to optimize at least two existing priority customer-facing services for mobile use and publish a plan for improving additional existing services:
</p>
<table >
     <tbody>
          <tr>
               <td colspan="2">
                    <table cellpadding="1" width="100%">
                         <tbody>
                              <tr>
                                   <td width="80%" align="left">
                                        <strong>Federal Agency Digital Strategies 7.2</strong>
                                   </td>
                                   <td width="10%" align="center">
                                        <a href="https://gist.github.com/kinlane/5564715" target="_blank" title="Script for Display"><img src="https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-code.png" border="0" width="25" /></a>
                                   </td>
                                   <td width="10%" align="center">
                                        <a href="https://raw.github.com/kinlane/federal-government/gh-pages/data/federal-agencies-digital-strategy-7-1-2-with-social.json" target="_blank" title="Raw JSON Data"><img src="https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-json-data-store.png" border="0" width="25" /></a>
                                   </td>
                              </tr>
                         </tbody>
                    </table>
               </td>
          </tr>
     </tbody>
</table>
<p>
     All of this data was pulled programmatically, using one of the core elements of the White House Digital Strategy, stating that it should be programmatically discoverable. You can access the resulting JSON and scripts to display in the header of each listings above.
</p>
<p>
     While 22 agencies did publish their strategies, there were a couple I couldn't process at all, and many others who had little problems that made harvesting difficult. Each programmatic request to an agency for their digital strategy could result in any number of HTTP codes retruned, redirects and responses. To demonstrate the potential differences, let compare two agencies:
</p>
<p>
     <strong>Energy (<a href="http://energy.gov" target="_blank">http://energy.gov</a>)</strong>
</p>
<ul >
     <li>Digital Strategy (HTML) - <a href="http://energy.gov/digitalstrategy.html" target="_blank">http://energy.gov/digitalstrategy.html</a>
     </li>
     <li>Digital Strategy (XML) - <a href="http://energy.gov/digitalstrategy.xml" target="_blank">http://energy.gov/digitalstrategy.xml</a>
     </li>
     <li>Digital Strategy (JSON) - <a href="http://energy.gov/digitalstrategy.json" target="_blank">http://energy.gov/digitalstrategy.json</a>
     </li>
</ul>
<p>
     <strong>Commerce (<a href="http://www.commerce.gov" target="_blank">http://www.commerce.gov/</a>)</strong>
</p>
<ul >
     <li>Digital Strategy (HTML) - <a href="http://www.commerce.gov/digitalstrategy" target="_blank">http://www.commerce.gov/digitalstrategy</a>
     </li>
     <li>Digital Strategy (XML) - <a href="http://www.commerce.gov/digitalstrategy" target="_blank">http://energy.gov/digitalstrategy.xml</a>
     </li>
     <li>Digital Strategy (JSON) - <a href="http://energy.gov/digitalstrategy.json" target="_blank">http://energy.gov/digitalstrategy.json</a>
     </li>
</ul>
<p>
     While the XML and JSON version of each agencies strategy is at same location, the HTML version have differences of locations. These small differences only amplify when you scale to 246 agencies. The issues also get more technical, with any variety of HTTP response codes returned including 200, 300, 400 and 500. Which I won't go into for this post, but when you are trying to write code, these can cause a whole bunch of problems.
</p>
<p>
     To put a cherry on top of this exercise, if you go to <a href="http://www.whitehouse.gov/digitalstrategy/" target="_blank">whitehouse.gov/digitalstrategy/</a> you get a pretty elaborate redirect to a PDF version of the original digital strategy mandate, which is a whole different cul-de-sac, especially since the White House has released datasets, APIs and mobile initiatives that should be listed here.  The White House should lead by example.
</p>
<p>
     I walk you through this process of programatically tracking on the White House digital strategy because I want to showcase the success that has occured over the last year, and support the next steps being taken by the release of the Open Data Policy.  But I want to also showcase how difficult this all can be. On the surface it can sound easy, but once you get into the weeds of execution things can breakdown pretty quickly, and it can be very difficult to keep the big picture in focus.  
</p>
<p>
     As we roll into May 2013, and approach the 1 year mark of the White House Digital Strategy, I can't help but embrace the new Open Data Policy with the same chaotic, bi-polar embrace I give the rest of the Digital Strategy and the overall public API space--with healthy balance of optimism, pragmatism and concern--then roll up my sleeves and get to work. During the last year of doing this, I've learned a lot about APIs and the Federal Government I would like to share:
</p>
<ul >
     <li>Web Literacy…is critical
     </li>
     <li>101 Materials..are essential
     </li>
     <li>Evangelists..are necessary
     </li>
     <li>Hackers...are desperately needed
     </li>
</ul>
<p>
     And most importantly, some sort of framework is necessary to give agencies a structure to work within, and a toolkit to direct them. This is the Open Data Policy, and brings us to the <a href="http://www.whitehouse.gov/sites/default/files/omb/memoranda/2013/m-13-13.pdf">Open Data Executive Order and the accompanying Open Data Policy</a> released by the Office of Management and Budget and Office of Science and Technology Policy which:
</p>
<p>
     require(s) that, going forward, newly generated government data shall be made freely available in open, machine-readable formats, while appropriately safeguarding privacy, confidentiality, and security. This requirement will help the Federal government achieve the goal of making troves of previously inaccessible or unmanageable data easily available to entrepreneurs, innovators, researchers, and others who can use those data to generate new products and services, build businesses, and create jobs.
</p>
<p>
     This kind of language is music to my ears. Understanding how our government works is one thing. Understand how to do it programmatically. Well, that is a whole other ball game. If we can move our government forward and develop a true path forward, to make everything our government produces machine readable by default. I'm on board.  Let's get to work!
</p>
<p>
     <strong>What does the <a href="http://www.whitehouse.gov/sites/default/files/omb/memoranda/2013/m-13-13.pdf">Open Data Policy</a> deliver?</strong>
</p>
<ul >
     <li>
          <strong>Laying the Groundwork</strong> - Why is this important? The Open Data Policy makes the business case for why this is important. This is about making government more effecient and generating jobs and innovation amongst entrepreneurs
     </li>
     <li>
          <strong>Open Data Definition -</strong> Balancing "open" with privacy, confidentiality and security. Acknowledging that open data is about it being accessible, described, reusable, complete, available in a timely and manner and should be managed post-release
     </li>
     <li>
          <strong>Common Definitions</strong> - Some basic definitions of data and datasets, as well as covering common points like fair information practice principles and personally identifiable information. But i'm really impressed with the introduction to concepts of information lifecycle and the mosaic effect. Great way to start
     </li>
     <li>
          <strong>Implementation Guidance -</strong> The Open Data Policy is truly a guide, with step by step implementation assistance for agency to help agencies actually making the rubber meet the road with putting open data to work
     </li>
     <li>
          <strong>Tools</strong> - A suite of open source tools are provided to agencies including database to API, CSV to API, spatial search and other useful code that agencies download, fork and put to use
     </li>
     <li>
          <strong>Resources</strong> - Additional resources that help agencies make the business case for open data, develop workflows, example licensing, content checklists and other resources to jumpstart an agencies open data efforts
     </li>
     <li>
          <strong>Life Cycle</strong> - Critical guidance for agencies that helps them understand the importance of using machine-readable and open formats, follow open data standards, use open licenses and to take advantage of common core and extensible metadata whenever possible in open data initiatives
     </li>
     <li>
          <strong>Accessibility</strong> - Provides an overview how agencies must build or modernize information systems in a way that maximizes interoperability and information accessibility. Making sure things are always available, scalable, flexible in multiple formats and empowers sharing and reuse
     </li>
     <li>
          <strong>Release Practices</strong> - Introduces agencies to healthy data release practices to assist in developing data inventory, establishing roles &amp; responsibility for stewardship, guides that assist agencies in developing a public listing and providing the essential outreach and engagement with the public and partners around data throughout its life cycle
     </li>
     <li>
          <strong>Security Guidance</strong> - A clear process for securing publicly available data, consistent with the Open Government Directive's presumption in favor of openness, and to the extent permitted by law and subject to privacy, confidentiality pledge, security, trade secret, contractual, or other valid restrictions.
     </li>
     <li>
          <strong>Institutionalize</strong> - Clear mandate that agencies must institutionalized and operationalized the interoperability and openness requirements in the Open Data Policy into their core processes across all applicable agency programs
     </li>
</ul>
<p>
     <strong>Why the Open Data Policy Make Me Happy?<br /></strong>The Open Data Policy makes me proud to be an American.  Really!  But beyond my joy for APIs, open data and passion for making government more efficient, I see some pretty specific aspects of the Open Data policy that make me happy.
</p>
<ul >
     <li>
          <strong>101 Materials</strong> - The open data lays the groundwork, provides the definitions, tools and resources that agencies will need to make it to the next level and find success with their agencies open data iniatives successful
     </li>
     <li>
          <strong>History</strong> - To help make the case, the White House showcases how releases valuable data like GPS and weather has changed the world and how we do business.  People need meaningful example like this to wrap their heads around the potential
     </li>
     <li>
          <strong>Guidance</strong> - Guidance, in the form of step by step guides showing agencies how to execute on the Open Data Policy.  This type of guidance is critical to help agencies follow the policy
     </li>
     <li>
          <strong>Case Studies</strong> - The Open Data Policy provides case studies, which much like the history it provides, gives clear examples that agencies can relate with when considering, planning and executing on their iniatives.  Agencies need to see clear examples that they can emulate in their own inaitives.
     </li>
     <li>
          <strong>Tools</strong> - The White House provides agencies with a suite of open source tools that can be used to actually start deploying APIs from databases and CSV. Simple, open source tools are critical to the success of agencies when executing on the Open Data Policy.
     </li>
     <li>
          <strong>Life Cycle</strong> - Understanding that just launching open data is not enough, and having processes to manage the lifecycle of open data and APIs is essential to not just a successful iniative, but also iterating and evolving data until it meets the needs of developers and consumers and generates maximum value
     </li>
     <li>
          <strong>Two-Way Street -</strong> Finding sucess with an agencies open data wil require the process being a two way street.  Agencies will need to engage with consumers and possess people, processes and tools for receiving and integrating feedback into agency operations. The Open Data Policy provides valuable information that helps agencies make their programs a two-way street
     </li>
     <li>
          <strong>Institutionalize</strong> - The Open Data Policy isn't just yet another data or technology iniative where a new IT approach is being mandated.  The Open Data Policy is about true change to the way agencies collect, process and publish information, pushing agencies to institutionalize the approaches set forth.  This is about true change, not just another tech trend.
     </li>
</ul>
<p>
     <strong>What Around The Open Data Policy Conerns Me?<br /></strong>Immediately after the joy ride through the items that make me happy, I start stumbling over some serious concerns.  Things that will slow, trip up, or could make the Open Data Policy a non-starter.  These are just a handful of my immediate concerns. 
</p>
<ul >
     <li>
          <strong>Government</strong>
          <ul >
               <li>
                    <strong>Lack of Resources</strong> - Agencies won't be given enough resources to give meaningful attention to executing on the Open Data Policy and the desired results won't be achieved
               </li>
               <li>
                    <strong>Lack of Evangelists</strong> - Agencies won't be able to hire or cultivate the passionate evangelists that will be needed to iniatiate change within agencies and get the word out to consumers
               </li>
               <li>
                    <strong>Lack of Storytellers</strong> - The Federal Government won't actually give agencies the freedom to be storytellers around all information, data and resources coming out of each agency.  Storys around the data will be essential to getting consumer interested and engaging
               </li>
               <li>
                    <strong>Administration Changes</strong> - The next administration will come in and not see the value of Open Data Policy and will roll any progress that has been made back
               </li>
          </ul>
     </li>
     <li>
          <strong>Corporations</strong>
          <ul >
               <li>
                    <strong>Exploitation</strong> - The private sector will step up and expoit government data and resources without recipricating value and sharing their data and augmented resources for the greater good
               </li>
               <li>
                    <strong>Talent</strong> - When talent is identified as part of federal government open data, the private sector will snatch them up and put them to use for their own goals, taking the talent away from where its most needed
               </li>
          </ul>
     </li>
     <li>
          <strong>Citizens</strong>
          <ul >
               <li>
                    <strong>Won't Step Up</strong> - Even with the effort of federal agencies, citizen hackers won't step up and do the work it will take to make agencies open data iniatives work and help clean up, refine and provide the feedback agencies will need
               </li>
               <li>
                    <strong>Won't Be Aloud In</strong> - Citizen hackers will build amazing things and provide some valuable work and feedback, but because of the closed nature of Washington, their efforts will be ignored and now given the attention they need to be successful
               </li>
          </ul>
     </li>
</ul>
<p>
     <strong>Why I am Optimistic About the Open Data Policy?<br /></strong>I think we can navigate many of the concerns I have around the Open Data Policy.  I know many of the people behind the government efforts, and I believe in these folks.  But I also believe in the power of what the private sector, leaving me very optimistic about what the Open Data Policy can achieve. 
</p>
<ul >
     <li>
          <strong>Government</strong>
          <ul >
               <li>
                    <strong>Starting Simple</strong> - The White House is starting simple.  They have started with the necessary education and evangelism needed to get agencies on board.  The Open Data Policy isn't technically overwhelming, it focuses on the basics and keeps things simple so agencies can absorb and put what they've learned to work
               </li>
               <li>
                    <strong>Engage</strong> - The Open Data Policy enforces engagement with consumers as part of a healthy data lifecycle.  Without engaging consumers and making the process a two way street, no amount of opening data will be successful.  Helping agencies understand the importance of engagement is critical to healthy open data iniatives
               </li>
               <li>
                    <strong>Using Github</strong> - The Open Data Policy isn't just educating agencies on the importance of using Github as part of their open data iniatives, the White House is using Github ot deploy and support the Open Data project.  This type of leading by example is critical to the adoption of proper tools by agencies
               </li>
          </ul>
     </li>
     <li>
          <strong>Corporations</strong>
          <ul >
               <li>
                    <strong>Value of Open Data</strong> - The private sector understands the value of open data and will actively participate in open data iniatives from federal agencies.  The more data that is opened, the more the private sector will step up and use, contributing significantly to the data life cycle
               </li>
               <li>
                    <strong>Emulate Government</strong> - With the federal government stepping up and leading, the private sector will follow.  In the API space, corporations often emulate what they see in the space. Strong leadership from Washington will make for healthier busineses across the private sector and API economy
               </li>
          </ul>
     </li>
     <li>
          <strong>Citizens</strong>
          <ul >
               <li>
                    <strong>Roll Up Sleeves and Get to Work</strong> - There are some seriously talented and passionate invidivuals involved with current government open data movements. As more agencies open up their data these hacker citizens will step up and provide some great code, data and feedback for government agencies.  The key is to make sure we continue to train the next generation of these talented, passsionate citizen hackers
               </li>
               <li>
                    <strong>Problem Owners</strong>- There are individuals in the private sector who are extermely passionate about some of the biggest problems our country faces.  These individuals will step up and put open government data and resources to use solving these problems
               </li>
          </ul>
     </li>
</ul>
<p>
     After reading through the Open Data Policy multiple times, I feel that we can do this.  I've read much of the criticism in other folks <a href="http://e-pluribusunum.com/2013/05/10/roundup-media-coverage-of-the-white-house-executive-order-on-open-data/">analysis of the release of the Open Data Policy</a>, along with their praise of the administration's move.  I think there is enough optimism and healthy pessimism out there, to really make this work. We can't be blinded by the often meaningless declrations of "open" or our blind faith in technology solutionism, we have to get to work with the difficult tasks of taking inventory, collecting, deployment and management of our countries valuable information and assets.  It will be a long road to get to where each agency and government worker understands what open and transparent truly means, it will be occur dataset by dataset, app by app and via numerous conversations between government and the private sector around each opened dataset and API.  It won't happen overnight, but the White House Digital Strategy and resulting Open Data Policy are an decent start. 
</p>
<p>
     <strong>What I'd LIke to See!</strong><br />
     The pragmatist in me appreciates the simple and cautious approach of the federal government.  It will take years of baby steps before we can run with open data.  But to help me understand where we need to be, I tend to try and understand what the potential future of government and open data could look like.  So let me share a few items I'd like to see in the future of government open data.
</p>
<ul >
     <li>
          <strong>JSON by Default</strong> - I want every individual in government to speak JSON, just like they speak PDF or Excel.  Government workers need to natively generating and consuming JSON without hestiation or confusion
     </li>
     <li>
          <strong>Dictionaries of Data Inventory </strong>- The listing of agencies who published their digital strategy, lists of 2.1 and 7.2 compliance and the counts listed above were all provided with JavaScript and JSON. ALL government should work like this.  I shouldn't reference an agency, individual, budget report or otherwise without using an open data driven dictionary of some sorts.  There should always be the data behind each fact or claim made in government.  With a healthy inventory across agencies, this is possible
     </li>
     <li>
          <strong>Visualizations</strong> - Pictures are indeed worth a thousand words.  We need an arsenal of simple, JavaScript and HTML5 visualizations that government works can reverse engineer or put to use when trying to tell the store around their information.  Visualizations will be essential in storytelling around federal government open data.
     </li>
     <li>
          <strong>Toolkits</strong> - The Open Data Policy does a great start to provide tools and resources agencie will need.  But we need a whole aresenal of open toolkits providing tools and resources to help agencies with everything from GIS to working with financial data.  These meaningful toolkits will be generated by the projects, in the trenches and published as part of the the living Open Data Policy in coming months
     </li>
     <li>
          <strong>Widgets</strong> - Much like visualizations, there will need to be a arsenal of simple, JavaScript and HTML5 widgets that allow for interaction between agencies, data stewards and the public.  Widgets will allow for feedback, updates, syndication and other essential aspects of data lifecycles
     </li>
     <li>
          <strong>Acreditation</strong> - There will be a lot of data coming from federal government.  We need to know which individuals have the most skills in specific domains.  There will need to be some sort of micro acredition process that individuals can go through to demonstrate the data and tools they have experience with, so that agencies and individuals can quickly identify who they should reach out to as part of the open data life cycle
     </li>
     <li>
          <strong>Tax Incentives</strong> - I've spent probably 150 hours in the last year working on government open data work.  None of it was paid.  As someone who does not seek a career in government, but will continue supporting from the private sector, I would really enjoy some sort of tax incentive to do so for my business or self employment
     </li>
</ul>
<p>
     While I'm always looking toward the future, I am extremeley satisfied with leadership coming out of Washington when it comes to APIs. I'm also happy with the progress that has come out of the Digital Strategy over the last year, and I think the Open Data Policy provides a healthy and logical next step for federal agencies to take.
</p>
<p>
     The Open Data Policy does an excellent job of addressing the technical, business and politics of APIs. While APIs, open data formats and other technical building blocks create a nice base, the policy also considers healthy data life cycles, engagement, outreach and support that will be critical to each agencies success. The Open Data Policy also provides the necessary licensing, security and educational elements that will be necessary to properly deliver on what can be some of the very political aspects of open data and APIs in the wild.
</p>
<p>
     The administration's pragmatic and balanced approach to open data in government will significantly increase the chance for individual agency success with open data and increase the chance they will truly be able to assimiliate the principles and practices set forth by the Open Data Policy into the agency operational fabric.  When each individual within an agency embraces this, information management in the federal government will no longer be a technical or IT solution--every government worker, private sector partner, NGO and citizen will be a gear in an efficient, well lubricated, interoperable government engine that truly serves its people.
</p>
<p>
     P.S.  If you really read all of this post, I thank you.  This whole process starts with my need to truly understand all of this and actually write code against as much of what the federal government is doing with APIs. I learn a lot along the way, and hope I am able to move the conversation forward.
</p>
