---
layout: post
title: How to do system design
---

* First things first - clarify requirements with standard questions:

  * What: clarify questions about what application must minimally do?
  * CAP Theorem: understand the latency, bandwidth, reliability, security requirements.
  * Concurrency:  understand number of users, scale, live concurrent sessions.
  * Services:  Different internal and external logical functions will be needed. Here, some services are internal to scale and some are user facing. In order to serve millions of users, what internal functions are needed? For example, logging, telemetry for performance, etc. Caution: mostly it is not asked unless it is a use case.
 * For ecommerce: 3rd part interface - we can also do authentication and autohrization this way.

* What is the Core usecase
  * What are the components or modules needed - just list them. Later you can drag and drop them.
  * think in terms of workflow of your use case.

