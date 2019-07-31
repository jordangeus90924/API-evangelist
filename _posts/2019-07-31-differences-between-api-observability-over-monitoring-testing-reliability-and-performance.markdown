---
published: true
layout: post
title: 'Differences Between API Observability Over Monitoring, Testing, Reliability, and Performance'
date: 2019-07-31T09:00:00.000Z
tags:
  - API Evangelist
  - Testing
  - Monitoring
  - Status
  - Performance
  - Observability
image: https://s3.amazonaws.com/kinlane-productions/algorotoscope-master/35201856153_61bc075e4b-udnie.jpg
---
<img src="{{ page.image }}" width="45%" align="right" style="padding: 15px;" />
I’ve been watching the API observability coming out of Stripe, as well as Honeycomb for a couple years now. Then observability of systems is not a new concept, but it is one that progressive API providers have embraced to help articulate the overall health and reliability of their systems. In control theory, observability is a measure of how well internal states of a system can be inferred from knowledge of its external outputs. Everyone (except me) focuses only on the modern approaches for monitoring, testing, performance, status, and other common API infrastructure building blocks to define observability. I insist on adding the layers of transparency and communication, which I feel are the critical aspects of observability—-I mean if you aren’t transparent and communicative about your monitoring, testing, performance, and status, does it really matter?

I work to define observability as a handful of key API building blocks that every API provider should be investing in:

- **Monitoring** - Actively monitoring ALL of your APIs to ensure they are up and running.
- **Testing** - Performing tests to ensure APIs aren’t just up but also doing what they are intended to.
- **Performance** - Adding an understanding of how well your APIs are delivering to ensure they perform as expected.
- **Security** - Actively locking down, scanning, and ensuring all your API infrastructure is secure.

Many folks rely on the outputs from these areas to define observability, but there are a couple more ingredients needed to make it observable:

- **Transparency** - Sharing the practices and results from each of these areas is critical.
- **Communication** - If you aren’t talking about these things regularly they do not exist.
- **Status** - Providing real time status updates for al these areas is essential.

You can be actively observing the outputs from monitoring, testing, performance, and security operations, but if this data isn’t accessible to other people on your team, within or company, partners, and for the public as required, then things aren’t observable. Of course, I’m not talking about making ALL API activity public, but I’m saying, if you are a public API, and you aren’t providing transparency, communication, and status of your monitoring, testing, performance, and security—-then you aren’t observable.

I know many folks will disagree with me on this part, but that is ok. I am used to it. So far, I haven’t seen much embrace of the observability concept, with many providers either not understanding it, or not grasping the meaningful impact it will have on their operations. So I’m not holding my breath that folks will buy into my portion of it. However it is my self appointed role to make sure the bar is high, even if nobody adopts the same set of rules. In the end, API observability isn’t some new trendy buzzword, it is one of a handful of meaningful constructs that exist to help make us all better, but most likely will get lost in the shuffle of doing APIs each day. :-(
