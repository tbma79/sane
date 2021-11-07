---
title: DRS ICDCS
subtitle: "DRS: Dynamic Resource Scheduling for Real-Time Analytics over Fast Streams. "
publication_types:
  - "1"
authors:
  - Tom Z. J. Fu
  - Jianbing Ding
  - admin
  - Marianne Winslett
  - Yin Yang
  - Zhenjie Zhang
doi: 10.1109/ICDCS.2015.49
publication: In *The 35th International Conference on Distributed Computing
  Systems (ICDCS), Columbus, Ohio, USA, June 29th - July 2nd, 2015.*
publication_short: In *IEEE ICDCS Conference*
abstract: "In a data stream management system (DSMS), users register continuous
  queries, and receive result updates as data arrive and expire. We focus on
  applications with real-time constraints, in which the user must receive each
  result update within a given period after the update occurs. To handle fast
  data, the DSMS is commonly placed on top of a cloud infrastructure. Because
  stream properties such as arrival rates can fluctuate unpredictably, cloud
  resources must be dynamically provisioned and scheduled accordingly to ensure
  real-time response. It is essential, for the existing systems or future
  developments, to possess the ability of scheduling resources dynamically
  according to the current workload, in order to avoid wasting resources, or
  failing in delivering correct results on time. Motivated by this, we propose
  DRS, a novel dynamic resource scheduler for cloud-based DSMSs. DRS overcomes
  three fundamental challenges: (a) how to model the relationship between the
  provisioned resources and query response time (b) where to best place
  resources, and (c) how to measure system load with minimal overhead. In
  particular, DRS includes an accurate performance model based on the theory of
  Jackson open queueing networks and is capable of handling arbitrary operator
  topologies, possibly with loops, splits and joins. Extensive experiments with
  real data confirm that DRS achieves real-time response with close to optimal
  resource consumption."
draft: false
featured: false
projects:
  - stream-systems
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2015-06-30T12:44:46.479Z
---
