---
title: "Map-Matching on Low-Sampling-Rate Trajectories through Frequent Pattern Mining"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'This paper is a further improvement of the fp matching algorithm, which introduces general behavioral rules and consideration of time factors to further improve the accuracy of map matching.'
date: 2022-02-17
venue: 'Journal 1'

---
Map-matching, an important pre-processing task in many location-based services (LBS),projects each point of the global positioning system (GPS) within a trajectory dataset onto adigital map. The state-of-the-art map-matching algorithms typically employ hidden Markovmodel (HMM) via shortest path computation. But the computation of the shortest path mightnot work well on low-sampling-rate trajectory data (e.g., one GPS point every 1-5min),leading to low matching precision and high running time. To solve the problem, this paperfirstly identifies frequent patterns (FPs) in historical trajectories to capture meaningfulmobility behaviors, and then extracts mobile behavior criterion (MBC) of mobile users. Sucha criterion generally represents the route choice of mobile users on road networks. Moreover,the temporal information within trajectory data was employed to estimate the speed of mobileusers on road segments. The identified FPs, coupled with MBC and moving speed, help toimprove the map-matching precision of low-sampling-rate trajectories. In addition, an FP-forest structure was proposed to index the identified FPs. The structure could greatly speedup the lookup of frequent paths for shorter running time. Further, the FP-forest structure waspruned to reduce redundancy with smaller space cost. Finally, experiments were carried outon real-world datasets. The results confirm that our FP-matching method outperforms state-of-the-arts in terms of effectiveness and efficiency.

Recommended citation: Lei Yu, **Zhiqiang Zhang**, Rongtao Ding. "Paper Title Number 3." <i>Journal 1</i>.

[Download paper here](http://zhiqiang11.github.io/files/mapmatching.pdf)
