---
published: true
layout: post
title: 'OpenAPI is Your Source of Truth and Collections are Derivatives of That Truth Designed For Specific Business Outcomes'
image: https://s3.amazonaws.com/kinlane-productions2/algorotoscope-master/bf-skinner-public-market-fish.jpg
tags:
- Postman
- OpenAPI
- Collections
- Contracts
---
I love the spectrum of API awareness that exists out there, and the challenge of trying to figure out how to move people "forward" across that spectrum. One of the most visible metrics of where an individual, team, or organization is at in their API journey is whether they say and use "Swagger" or "OpenAPI". While this is the most visible chasm that exists across this spectrum, there are many more dimensions out there based upon how you see and use OpenAPI, and how you see and use Postman collections. I don’t expect everyone to see things as I do, as I have been thinking full time about this for a very long time, but also I am biased because of my role at Postman. However, my view of the landscape is still relevant in helping provide milestone markers for others to at least consider as they make their way "foward" in their journey.


There is a lot of confusion out there between Swagger and OpenAPI, but there is even more confusion out there between what OpenAPI and Swagger are for, and what Postman Collections are for. Both of these spectrums reflect where folks are in their journey, and the role that machine readable artifacts play in helping stabilize the lifecycle can be found across the varying perspectives of what Swagger, OpenAPI, and Postman Collections are used for. The most common constraint people apply is that Swagger and OpenAPI are just for documentation and that Postman Collections are for API testing. These views articulate where someone is at in their API journey, and how aware and standardized, or ad hoc and chaotic their view of the API lifecycle. OpenAPI is all about grounding the API lifecycle in a source of truth of what is possible with API, and the collection format specializes in deriving variations of that truth that speak to specific business outcomes.


OpenAPI, formerly known as Swagger is a machine readable specification for describing the surface area of your synchronous API, providing you with a vocabulary for establishing a definition of request and response details of your API. This definition can then be used as a machine readable contract with consumers which can power documentation, mock servers, testing, security, code generation, gateway, and other elements of API operations. OpenAPI provides the human and machine-readable contact that defines what each version of your digital resource or capabilities does, helping the team behind producing and sustaining an API, and the consumers who are putting an API to use in applications and integrations on the same page. Now, much of what I have described is also applicable to Postman Collections, resulting in a lot of confusion regarding what each of the open-source API specification can and cannot do, when in reality they actually very much work together and compliment each other, helping you better align your API operations with business outcomes.


Postman Collections are a machine-readable specification that can be created independently, but also auto-generated and kept in sync with any OpenAPI source of truth. Like OpenAPI they can be used to publish reference documentation, mock servers, and other stops along the API lifecycle. But, unlike OpenAPI, Postman collections have built in scripting, authentication, variables, and other characteristics that help it be a more executable derivative of the source of turret for an API. Postman Collections are used to produce onboarding collections that help reduce the cognitive load when it comes to getting started with an API, produce complex workflows involving many different APIs, and often contain examples and supporting data that supports specific business outcomes. Postman collections provide a more executable representation of an API that can then be automated using a runner, scheduled via a cloud monitor in any region, and within any CI/CD pipeline, which can be kept in alignment with the source of truth as defined by an OpenAPI definition. Revealing a dance between OpenAPI and Postman collections that when versioned and documented properly can provide the velocity you need to move each API forward at the speed business demands.


OpenAPI can be used as the source of truth for an API inside and outside of the Postman platform. Collections can be used as a derivative of that truth for mocking, documenting, testing, and securing specific business outcomes satisfied by each API. OpenAPI is the truth of what is possible, and a collection is an executable, publishable, and sharable representation of what is possible being realized across business operations. What makes this different is that it represents the digital resources and capabilities you are making available via an API, but it also represents the operations that are necessary for a successful API, helping establish a machine readable artifact for documentation, mock servers, testing, and security that can be augmented for with another machine readable artifact for each development, staging, and production environments, and is self-documented, and executable via the Postman API Platform, or any CI/CD pipeline using Newman. After I recorded a session of Breaking Changes recently, I suddenly had the realization that this is how you define your inventory of digital resources and capabilities, but it is also how you distill down these technical resources and capabilities into units of value that represent specific business outcomes, that will matter to both producer and consumer.