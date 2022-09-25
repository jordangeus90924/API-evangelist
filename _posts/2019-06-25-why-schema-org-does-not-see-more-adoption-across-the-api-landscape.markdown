---
published: true
layout: post
title: 'Why Schema.org Does Not See More Adoption Across The API Landscape'
date: 2019-06-25T12:00:00.000Z
tags:
  - API Evangelist
image: >-
  https://s3.amazonaws.com/kinlane-productions/algorotoscope-master/machine-road-machine-road-blue-circuit-3.jpg
---
<img src="{{ page.image }}" width="45%" align="right" style="padding: 15px;" />
I’m a big fan of Schema.org. A while back I generated an OpenAPI 2.0 (fka Swagger) definition for each one and published to GitHub. I’m currently cleaning up the project, publishing them as OpenAPI 3.0 files, and relaunching the site around it. As I was doing this work, I found myself thinking more about why Schema.org isn’t the goto schema solution for all API providers. It is a challenge that is multi-layered like an onion, and probably just as stinky, and will no doubt leave you crying.

First, I think tooling makes a big difference when it comes to why API providers haven’t adopted Schema.org by default across their APIs. If more API design and development tooling would allow for the creation of new APIs using Schema.org defined schema, I think you’d see a serious uptick in the standardization of APIs that use Schema.org. In my experience, I have found that people are mostly lazy, and aren’t overly concerned with doing APIs right, they are just looking to get them delivered to meet specifications. If we provide them with tooling that gets the API delivered to specifications, but also in a standardized, they are doing to do it.

Second, I think most API providers don’t have the time and bandwidth to think of the big picture like using standardized schema for all of their resources. Most people are under pressure to more with less, and standards is something that can be easily lost in the shuffle when you are just looking to satisfy the man. It takes extra effort and space to realize common standards as part of your overall API design.  This is a luxury most companies, organizations, and government agencies can not afford, resulting in many ad hoc APIs defined in isolation.

Third, I think some companies just do not care about interoperability. Resulting in them being lazy, or not making it a priority as stated in the first and second points. Most API providers are just concerned with you using their API, or checking the box that they have an API. They do not connect the dots between standardization and it being easier for consumers to put their resources to work. Many platforms who are providing APIs are more interested in lock-in, providing proprietary SDKs and tooling on top of their API. Selling them on the benefits of interoperable open source SDKs and tooling just falls on deaf ears—leaving most API providers to perpetually reinvent the wheel when there is an existing well defined one within reach.

I wish ore API folks cared about Schema.org. I wish I had the luxury of using in more of my own work. If it is up to me, I will always adopt Schema.org for my core API designs, but unfortunately I’m not always the one in charge of what gets decided. I will continue to invest in OpenAPI definitions for all of the Schema.org defined schema. This allows me to have within reach when I’m getting ready to define a new API. If Schema.org ready API definitions are in a neat stack on my desk, the likelihood that I’m going to put to work in the API tooling I’m developing, and actually as the base for an API I’m delivering, increases significantly. Helping me standardize my API vocabulary to something that reaches beyond the tractor beam of daily API bubble.
