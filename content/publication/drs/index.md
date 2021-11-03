---
title: "DRS: Auto-Scaling for Real-Time Stream Analytics. "
subtitle: ""
publication_types:
  - "2"
authors:
  - Tom Z. J. Fu
  - Jianbing Ding
  - admin
  - Marianne Winslett
  - Yin Yang
  - Zhenjie Zhang.
publication: IEEE/ACM Transactions on Networking, Volume 25, Issue 6, pp. 3338 -
  3352, December 2017.
publication_short: IEEE/ACM Transactions on Networking
abstract: "In a stream data analytics system, input data arrive continuously and
  trigger the processing and updating of analytics results. We focus on
  applications with real-time constraints, in which, any data unit must be
  completely processed within a given time duration. To handle fast data, it is
  common to place the stream data analytics system on top of a cloud
  infrastructure. Because stream properties, such as arrival rates can fluctuate
  unpredictably, cloud resources must be dynamically provisioned and scheduled
  accordingly to ensure real-time responses. It is essential, for existing
  systems or future developments, to possess the ability of scaling resources
  dynamically according to the instantaneous workload, in order to avoid wasting
  resources or failing in delivering the correct analytics results on time.
  Motivated by this, we propose DRS, a dynamic resource scaling framework for
  cloud-based stream data analytics systems. DRS overcomes three fundamental
  challenges: 1) how to model the relationship between the provisioned resources
  and the application performance, 2) where to best place resources, and 3) how
  to measure the system load with minimal overhead. In particular, DRS includes
  an accurate performance model based on the theory of Jackson open queueing
  networks and is capable of handling arbitrary operator topologies, possibly
  with loops, splits, and joins. Extensive experiments with real data show that
  DRS is capable of detecting sub-optimal resource allocation and making quick
  and effective resource adjustment."
draft: false
featured: false
tags:
  - Cloud Systems
url_code: https://github.com/ADSC-Cloud/resa-drs
image:
  filename: featured
  focal_point: Smart
  preview_only: false
summary: Based on the Jackson queueing network, DRS is able to dynamically
  determine the optimal resource allocation solution for stream jobs in the
  runtime.
date: 2017-12-03T15:30:21.668Z
---
