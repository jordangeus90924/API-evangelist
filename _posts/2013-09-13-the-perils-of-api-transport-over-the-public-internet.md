---
layout: post
title: "The Perils Of API Transport Over The Public Internet"
url: 'http://apievangelist.com/2013/09/13/the-perils-of-api-transport-over-the-public-internet/'
image: 'http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/blog/bw-danger.png'
---

<img class="c1" src="https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-danger.png" alt="" width="250" align="right" />

George Reese has a very interesting post from last week over at O'Reilly. It is about an earlier post he did on the unpublished [Tesla REST API][1]. I'll let you read the post, "T[he Myth of the Private API][2]"--I highly recommend it.

Reese talks about the mistakes made by Tesla, Phillips and other Internet of Things companies, when they take advantage of the power of web APIs, intending them to be private, but do not put any thought into what happens when you deploy APIs using the public without securing your API endpoints from unintended use.

I find a particular statement he made, fascinating:

> _I sincerely believe that ultimately there is no such thing as a private API for consumption over the public Internet._

After reading his post, I have to agree. I think many technology companies are just considering the Internet to be some sort of constant, magic transport layer for anything we want to use it for. I think this can be true to a point, but as the Intenret matures, we have slow down a bit and consider deeply the impact of our actions, and the way we use Internet enabled technology.

I wrote about a piece last week, which was about the [first FTC case against an Internet of Things manufactuer][3], camera maker TrendNet--where much like Tesla, they took no considerations for the fact they were using the open Internet to drive their technology, and more importantly no thought regarding the privacy of their consumers.

The world of APIs fascinates me. It reminds me of the bug zappers, where we are attracted by the openness and power of web APIs, but as you get closer and closer to the API light, you can easily get burned or zapped by the very thing that drew you in.

I strongly believe in the power of web APIs, but I think there will be a lot of unintended consequences from opening up data, resources and the devices that surround us, over the public Internet. Make sure you are being thoughtful, and seriously considering security, privacy and the other potential repercussions of web APis before jumping in.

   [1]: http://programming.oreilly.com/2013/08/tesla-model-s-rest-api-authentication-flaws.html
   [2]: http://programming.oreilly.com/2013/09/the-myth-of-the-private-api.html
   [3]: http://apievangelist.com/2013/09/05/building-internet-of-things-products-you-better-secure-it-says-the-ftc/
