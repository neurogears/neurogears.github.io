---
layout: post
title: "HiveTracker: UbiComp 2019"
date: 2019-09-12 12:00:00 -0000
categories: news
image: /assets/images/190912-ubicomp-hivetracker.jpg
excerpt: Excited to present our latest developments on the HiveTracker project at UbiComp 2019!
---

The [HiveTracker](https://hivetracker.github.io/) is a small & affordable system for scalable and accurate 3D tracking developed over the past two years. It builds off the existing SteamVR tracking system by Valve, Inc. and together with a 9DoF inertial measurement unit (IMU), allows sub-millimetric 3D positioning at scale. We have recently presented our latest cross-platform logging and visualization interface at [UbiComp 2019](http://ubicomp.org/ubicomp2019).

<div class="gallery">
  <div class="popup-gallery">
    <a title="Smartphone demo"><img src="/assets/images/190912-ubicomp-hivetracker-phone.gif"></a>
    <a title="Computer demo"><img src="/assets/images/190912-ubicomp-hivetracker-pc.gif"></a>
  </div>
</div>

The original Lighthouse 3D tracking combines real-time readout of dozens of photosensors in a single object, requiring an expensive dedicated FPGA for the accurate readout of the timing of the external beacons. The main innovation of the HiveTracker project is to explore a miniaturization tradeoff by using less photosensors and a single inexpensive microcontroller to accurately log external beacon signals for localization. Read more about the project in the [HiveTracker Hackaday page](https://hackaday.io/project/160182-hivetracker) and the [UbiComp extended abstract](https://dl.acm.org/doi/10.1145/3341162.3349295).
