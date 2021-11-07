---
title: Auction-Based Cloud Service Differentiation with Service Level Objectives
subtitle: ""
publication_types:
  - "2"
authors:
  - Jianbing Ding
  - admin
  - Yin Yang
  - Zhenjie Zhang
doi: https://doi.org/10.1016/j.comnet.2015.11.007
publication: In *Computer Networks, Volume 94, pp. 231 - 249, January 2016.*
publication_short: In *Computer Networks*
abstract: We present a new study on service differentiation techniques for
  general cloud system. Our solution potentially opens new business models for
  cloud systems in the future, and enables ordinary users to exploit the
  benefits of clouds.We propose Abacus an auction based approach to cloud system
  resource allocation and scheduling, with enticing features such as
  incentive-compatibility, system stability and efficiency.We simplify the
  auction procedure by allowing the users to skip the utility function when the
  user is unsure or unaware of the exact utility model of his own repeated
  jobs.We implement Abacus by modifying the scheduling algorithm in Hadoop, and
  test it on a large-scale cloud platform. Our experimental results verify the
  truthfulness of our auction-based mechanism, system efficiency, as well as the
  accuracy of our utility prediction algorithm. The emergence of the cloud
  computing paradigm has greatly enabled innovative service models, such as
  Platform as a Service (PaaS), and distributed computing frameworks, such as
  MapReduce. However, most existing cloud systems fail to distinguish users with
  different preferences, or jobs of different natures. Consequently, they are
  unable to provide service differentiation, leading to inefficient allocations
  of cloud resources. Moreover, contentions on the resources exacerbate this
  inefficiency, when prioritizing crucial jobs is necessary, but impossible.
  Motivated by this, we propose Abacus, a generic resource management framework
  addressing this problem. Abacus interacts with users through an auction
  mechanism, which allows users to specify their priorities using budgets, and
  job characteristics via utility functions. Based on this information, Abacus
  computes the optimal allocation and scheduling of resources. Meanwhile, the
  auction mechanism in Abacus possesses important properties including incentive
  compatibility (i.e., the users' best strategy is to simply bid their true
  budgets and job utilities) and monotonicity (i.e., users are motivated to
  increase their budgets in order to receive better services). In addition, when
  the user is unclear about her utility function, Abacus automatically learns
  this function based on statistics of her previous jobs. Extensive experiments,
  running Hadoop on a private cluster and Amazon EC2, demonstrate the high
  performance and other desirable properties of Abacus.
draft: false
featured: false
tags:
  - Apache Storm
projects:
  - cloud-native-systems
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2016-01-01T13:07:51.550Z
---
