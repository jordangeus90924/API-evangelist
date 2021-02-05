---
published: true
layout: post
title: 'The Complexity of API Discovery'
date: 2019-07-01T09:00:00.000Z
tags:
 - API Evangelist
 - Discovery
image: >-
  https://s3.amazonaws.com/kinlane-productions/algorotoscope-master/aws-s3-stories-containership-copper-circuit.jpg
---
<img src="{{ page.image }}" width="45%" align="right" style="padding: 15px;" />
I can't get API discovery out of my mind. Partly because I am investing significant cycles in this area at work, but it is also something have been thinking about for so long, that it is difficult to move on. It remains one of the most complex, challenging, and un-addressed aspects of the way the web is working (or not working) online today. I feel pretty strongly that there hasn't been investment in the area of API discovery because most technology companies providing and consuming APIs prefer things be un-discoverable, for a variety of conscious and un-conscious reasons behind these belief systems. 

### What API Discovery Means? Depends On Who You Are...
One of the reasons that API discovery does not evolve in any significant ways is because there is not any real clarity on what API discovery is. Depending on who you are, and what your role in the technology sector is, you'll define API discovery in a variety of ways. There are a handful of key actors that contribute to the complexity of defining, and optimizing in the area of API discovery.
 
  - **Provider** - As an API provider, being able to discover your APIs, informs your operations regarding what your capabilities are, building a wider awareness regarding what a company, organization, institution, or government agency does, helping eliminate inefficiencies, and allows for more meaning decisions to be made at run-time across operations.
  - **Consumer** - What you need as an internal consumer of APIs, or maybe a partner, or 3rd party developer will significantly shift the conversation around what API discovery means, and how it needs to be "solved". There is another significant dimension to this discussion, separating human from other system consumption, further splintering the discussion around what API discovery is when you are a consumer of APIs.
  - **Analyst** - As an analyst for specific industries, or technology in general, need to understand the industries they are watching, and how API tooling is being applied, helping them develop an awareness of what is happening, and understand what the future might hold.
  - **Investor** - A small number of investors are in tune with APIs, and even grasp what API discovery means to their portfolio, and the industries they are investing in, generally being unaware of how API discovery will set the tone for how markets behave--providing the nutrients (or lack of) markets need to understand what is happening across industries.
  - **Journalist** - Most journalists grasp the importance of Facebook and Twitter, but only a small percentage understand what APIs are, and how ubiquitous they are, and the benefits they bring to the table when it comes to helping them in their investigations, and research, let alone how it can benefit them in their work when it comes to syndication and exposure for their work--making API discovery pretty critical to what they do.
  - **University** - I am seeing more universities depending on accessible APIs when it comes to research, and an increase in the development of API related curriculum--just as important, I am also seeing the increased development of open source API tooling out of university environments.
  - **Government** - APIs will play an increasing role in regulation, taxation, and government funded / implemented research, making API discovery key to finding the data they need, and being able to have their finger on the pulse of what citizens and businesses are up to on any given week.
  - **End-User** - Last, but definitely not least, the end-user should b e concerned with API discovery, and using it as a low water mark for where they should be doing business, and requiring that the platforms they use have APIs, and have their best interests in mind when allowing for 3rd party access to their data.

### How APIs Are Discovered?
Across these different views of the API discovery landscape, there are a variety of ways in which APIs are discovered, and made discoverable. Providing some formal, and some not so formal ways to define the the API landscape, and develop an awareness of the API ecosystems that have risen up within different industries, within institutions and government agencies. These are the ways I am focused on finding APIs, and making APIs findable, inside and outside the firewall.

Our motivations for finding APIs inside or outside the firewall are not always in sync with our motivations for having our APIs be found. This affects our view of the landscape when it comes to how hard API discovery is, and what the possible solutions for it will be. I find people’s view on API discovery to be very relative to their view of the landscape, and very few people in the API sector travel widely enough, exchange ideas externally enough, and lift themselves up high enough to be able to understand API discovery well enough to provide the right tools and services to move the conversation forward.

### Within the Firewall
API discovery with the firewall is a real struggle. Most companies I know do not know where all of their APIs are. There is no single up to date truth of where each API is, what it does, let alone the machine readable details of what it delivers. These are a few of the ways in which I have seen groups tackle API discovery within the firewall: 

  - **Directories** - Many employ a catalog, directory, or database of APIs, micro services, and other relevant solutions.
  - **Git Repositories** - Git within the enterprise is a very viable way to manage a large volume of artifacts you can use for discovery.
  - **Word of Mouth** - Talking to people is always a great way to understand what APIs exist across the enterprise landscape.
  - **Documentation** - The documentation for APIs often become the focal point of API discovery because it can be searched.
  - **Log Files** - Harvest what is actually coming across the wire, parse APIs that are in use, and documenting them in some way.

The biggest challenge with API discovery within the firewall is having dedicated resources to keep up with the discovery, documenting, while also keeping catalogs, repositories, documentation, and other key sources of API discovery information up to date. In my experience, rarely do teams ever get the budget to properly invest in API discovery, with things often done as part of skunk works, or in every day operations—as teams can--which is never enough.

### Outside the Firewall
This is the aspect of API discovery that gets the most attention when it comes to API discovery. These are the API rock stars, directors, marketplaces, and API showcasing that occurs across tech blogs. API discovery outside the firewall has access to far more tools and services to leverage when getting the word out, or helping you find what you are looking for. The challenge becomes, like most other things on the open web, how do you cut through the noise, and get your APIs found, or find the APIs you are looking for. 

  - **Directories** - You use some of the existing API directories out there. Providing you access to a small subsection of the APIs that these operators can find, and manually publish to their API catalogs. There really isn’t a single source of truth when it comes to API directories, but there are some that have been around longer than others.
  - **Marketplaces** - There have been numerous waves of investment into API marketplaces, trying to centralize the discovery and integration with APIs, hoping to simplify APIs enough that consumers use you as their doorway to the API world—giving the API marketplace provider a unique look at how APIs are consumed.
  - **Documentation** - Public API documentation is how your APIs will be found using Google, which is the number one way people are going to find your API—using a Google search. I’m surprised that Google hasn’t tackled the issue of API discovery already, but I’m guessing they haven’t deemed it valuable enough to tackle, and will most likely swoop in and take dominate once some smaller providers plant the seeds.
  - **Definitions** - API discovery has gotten easier, and more robust with the introduction of API definitions like Swagger, OpenAPI, API Blueprint, RAML, Postman collections and other machine readable formats. Going beyond just static or even dynamic API documentation, and providing a machine readable artifact that can be indexed and used to drive API search.
  - **Domains** - You can drive a lot of interesting API discovery using domains, and building indexes of different types of domains, then conduct several types of searches to see if they have any APIs. Using search engine APIs, Twitter, Github, and other social media APIs to find APIs across the landscape—using domains as the anchor for refining and making API discovery queries more precise.
  - **Scraping** - If you have the URL for an companies, organization, institution, or government agencies API documentation page you can also scrape that page, or pages for more information about how any API operations, and what it does—adding to the index of APIs to be search against.
  - **Search Engines** - While Google doesn’t have a good API anymore, Bing and DuckDuckGo do.It is easy to build up an index of queries to search Bing to uncover potential domains, documentation, definitions, and other artifacts to enrich an API discovery index. With the right key phrase glossary, you can quickly automate a pretty comprehensive search for new APIs.
  - **GitHub** - The social coding platform is a rich one of API related data. Similar to search engines you can easy build a search query vocabulary to uncover a number of domains, documentation, definitions, and other artifacts to enrich an API discovery index.
  - **Integrated Development Environment (IDE)** - The IDE is an untapped market when it comes to helping developers find APIs, and to help API providers reach developers. Microsoft has been increasing API discovery features, while also being extended with plugins by the community. There is no universal API search engine baked into the top IDEs, a definite missed opportunity.
  - **News** - It is pretty easy to harvest press releases, blog posts, and other news sources and use them as rich sources of information for new APIs. Helping seed a list of potential domains to look for documentation and other API artifacts. Publishing a press release, or posting to their blog is the most common way that API providers get the word out, unfortunately it tends to be the only thing they do.
  - **Tweets** - Twitter is also a rich source of information about APIs, with a variety of accounts, hashtags, and other ways to make queries for new APIs more precise. Using the social media platform as.a way of tuning into potential new APIs, as well as the activity around existing APIs in the index.
  - **LinkedIn** - More business, institutions, and government entities are talking about their APIs on LinkedIn, publishing posts, job listings, and other API related goings on. Making it a pretty rich way to find new APIs, and companies who are embarking, or making their way along their API journey.
  - **Security Alerts** - Sadly, security alerts is one way I learn about companies and their APIs—when they become un-secure. Providing information about API providers who operate in the shadows, as well as more information to index when actually rating APIs in the index, but that is another story.

Even once you discover the APIs you are looking for, often times more context is required, and you may or may not have the time or expertise to assess what an API delivers, and what it will take to get up and running with an API.

  - **Documentation** - Where the documentation resides for the API.
  - **Signup** - Where a user can signup to use an API.
  - **Pricing** - What is the pricing for using an API.
  - **Support** - Where do you get support if you need help.
  - **Terms of Service** - Where do I find the legalize behind AP operations.

These are just five of the most common questions APIs consumers are going to ask when they are looking at an API, and would benefit from direct links to these essential building blocks as part of any API search results.  I have over a hundred questions that I like to ask of an API as I’m reviewing, which all reflect what a potential API consumer will be asking when they come across an API out in the wild.

### Four Primary Dimensions Of Complexity
I’d say that these are the four main dimensions of complexity I see out there when it comes to API discovery, which makes it really hard to provide a single API discovery solution, and why there hasn’t been more investment in this area. It is difficult to make sense of APIs, and what people are looking for. It is hard to get all API providers on the same page when it comes to investing in API discovery as part of their regular operations. API discovery is something I’ll keep investing in, but it is something that will need wider investment from the community, as well as some bigger players to step up and help move the conversation forward.

Other than API marketplaces, and the proliferation of API definitions, I haven’t seen any big movements in the API discovery conversation. We still have ProgrammableWeb. We still have Google. Not much more. With the number of APIs growing, this is only going to become more of a pain point. I’m interested in investing in API discovery not because I want to help everyone find APIs, or have their APIs found. Im more interested in shining a light on what is going on. I am looking to understand the spread of APIs across the digital landscape, and better see where they are pushing into our physical worlds. My primary objective is not to make sure all APIs are found so they can be used. My primary objects is to make sure all APIs are found so we have some observability into how the machine works.
