---
layout: page
title: Continual Learning for Network Intrusion Detection
description: Security systems that keep learning as new attack types emerge, without forgetting the old ones.
importance: 1
category: research
related_publications: true
---

Traditional network intrusion detection systems (NIDS) are trained once and struggle to keep up as new attack types emerge. My research develops **continual learning**-based NIDS that adapt to novel threats over time while retaining what they've already learned, addressing challenges such as catastrophic forgetting, class imbalance, task-order sensitivity, and limited supervision.

{% cite 9668482 %} introduces continual learning for anomaly-based intrusion detection and studies its sensitivity to task ordering. {% cite 10.1145/3486001.3486231 %} tackles the severe class imbalance that arises when new attack classes are learned incrementally.
