---
title: "Understanding and Characterizing Transmission Times for Compressed IP packets over LoRaWAN"
collection: publications
category: conferences
permalink: /publication/conference_1.md
excerpt: ''
date: 2020-01-02
venue: '2019 IEEE Latin-American Conference on Communications (LATINCOM)'
paperurl: 'http://rodrigomunozlara.github.io/files/08938005-2.pdf'
citation: 'R. M. Lara, S. Céspedes and A. Hafid, "Understanding and Characterizing Transmission Times for Compressed IP packets over LoRaWAN," 2019 IEEE Latin-American Conference on Communications (LATINCOM), Salvador, Brazil, 2019, pp. 1-6, doi: 10.1109/LATINCOM48065.2019.8938005.'
---

The Low Power Wide Area (LPWA) networks are expected to enable the massive connectivity of small and con- strained devices to the Internet of Things. Due to the restricted nature of both end devices and network links, LPWA technologies employ network stacks that often do not define an interoperable network layer; instead, application data is usually placed directly into technology-specific layer-two frames. Besides not being able to run standard IP-based protocols at the end device, the lack of an IP layer also causes LPWA segments to operate in an isolated manner requiring middle boxes to interface non-IP LPWA technologies with the IP world. IETF is working to standardize a compression scheme, called Static Context Header Compression (SCHC), which will allow compressing the headers of IPv6 and UDP for LPWA networks, in a way that the end device is enabled with IP-based communications. In this paper, we focus on the LoRa/LoRaWAN technology and describe the way in which the selection of the compression rules in SCHC will translate into specific transmission delays. We conduct a study of the expected transmission times, namely the Time on Air (ToA), and propose two additional metrics to understand and characterize the impact of compression over the resultant delay of IP-based communications over LoRaWAN. Our work concludes that there is a non-linear relationship between Time on Air and the percentage of compression of each rule.