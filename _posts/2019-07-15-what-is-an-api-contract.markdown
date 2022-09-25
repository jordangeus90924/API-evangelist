---
published: true
layout: post
title: 'What Is An API Contract?'
date: 2019-07-15T09:00:00.000Z
tags:
  - API Evangelist
  - API Contracts
  - Reliability
  - Stability
  - Service Level Agreement
  - SLA
image: >-
  https://s3.amazonaws.com/kinlane-productions/algorotoscope-master/adam-smith-adam-smith-purp-paper.jpg
---
<img src="{{ page.image }}" width="45%" align="right" style="padding: 15px;" />
I am big on regularly interrogating what I mean when I use certain phrases. I’ve caught myself repeating and reusing many hollow, empty, and meaningless phrases over my decade as the API Evangelist. One of these phrases is, "an API contract". I use it a lot. I hear it a lot. What exactly do we mean by it? What is an API contract, and how is it different or similar to our beliefs and understanding around other types of contracts? Is it truth, or is just a way to convince people that what we are doing is just as legitimate as what came before? Maybe it is even more legitimate, like in a blockchain kind of way? It is an irreversible, unbreakable, digital contract think bro!

If I was to break down what I mean when I say API contract, I’d start with being able to establish to a shared articulation of what an API does. We have an OpenAPI definition which describes the surface area of the request and response of each individual API method being offered. It is available in a machine and human readable format for both of us to agree upon. It is something that both API provider and API consumer can agree upon, and get to work developing and delivering, and then integrating and consuming. An API contract is a shared understanding of what the capabilities of a digital interface are, allowing for applications to be programmed on top of.

After an API contract establishes a shared understanding, I'd say that an API contract helps mitigate change, or at leasts communicates it—-again, in a human and machine readable way. It is common practice to semantically version your API contracts, ensuring that you won’t remove or rename anything within a minor or patch release, committing to only changing things in a big way with each major release. Providing an OpenAPI of each version ahead of time, allowing consumers to review that new version of an API contract before they ever commit to integrating and moving to the next version. Helping reduce the amount of uncertainty that inevitably exists when an API changes, and consumers will have to respond with changes in their client API integrations.

Then I’d say an API contract moves into service level agreement (SLA) territory, and helps provide some guarantees around API reliability and stability. Moving beyond any single API, and also speaking to wider operations. An API contract represents a commitment to offering a reliable and stable service that is secure, observability, and the provider has consumers best interest in mind. A contract should reflect a balance between the provider and the consumer interests, and provide a machine and human readable agreement that reflects the shared understanding of what an API delivers—for an agreed upon price. Any API contract reflects the technical and business details of us doing business in this digital world.

Sadly, an API contract is often wielded in the name of all of these things, but there really is very little accountability or enforcement when it comes to API contracts. It is 100% up to the API provider to follow through and live up to the contract, with very little an API consumer can do if the contract isn’t met. Resulting in many badly behaved API providers, as well as monstrous API consumers. Right now, API contract is thrown around by executives, evangelists, analysts and pundits, more than they are ever actually used to govern what happens on the ground of API operations. Only time will tell if API contracts are just another buzzword that comes and goes, or if they become common place when it comes to doing business online in a digital world.
