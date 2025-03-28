---
title: "SCHC over LoRaWAN Efficiency: Evaluation and Experimental Performance of Packet Fragmentation"
collection: publications
category: manuscripts
permalink: /publication/journal_1
excerpt: ''
date: 2022-02-16
venue: 'Sensors'
slidesurl: ''
paperurl: 'http://rodrigomunozlara.github.io/files/sensors-22-01531-3.pdf'
citation: 'Muñoz, R., Saez Hidalgo, J., Canales, F., Dujovne, D., & Céspedes, S. (2022). SCHC over LoRaWAN Efficiency: Evaluation and Experimental Performance of Packet Fragmentation. Sensors, 22(4), 1531. https://doi.org/10.3390/s22041531 '
---

Low Power Wide Area Networks (LPWAN) are expected to enable the massive connectivity of small and constrained devices to the Internet of Things. Due to the restricted nature of both end devices and network links, LPWAN technologies employ network stacks where there is no interoperable network layer as a general case; instead, application data are usually placed directly into technology-specific two-layer frames. Besides not being able to run standard IP-based protocols at the end device, the lack of an IP layer also causes LPWAN segments to operate in an isolated manner, requiring middleboxes to interface non-IP LPWAN technologies with the IP world. The IETF has standardized a compression and fragmentation scheme, called Static Context Header Compression and Fragmentation (SCHC), which can compress and fragment IPv6 and UDP headers for LPWAN in a way that enables IP-based communications on the constrained end device. This article presents a model to determine the channel occupation efficiency based on the transmission times of SCHC messages in the upstream channel of a LoRaWAN™ link using the ACK-on-Error mode of standard SCHC. The model is compared against experimental data obtained from the transmission of packets that are fragmented using a SCHC over LoRaWAN implementation. This modeling provides a relationship between the channel occupancy efficiency, the spreading factor of LoRa™, and the probability of an error of a SCHC message. The results show that the model correctly predicts the efficiency in channel occupation for all spreading factors. Furthermore, the SCHC ACK-on-Error mode implementation for the upstream channel has been made fully available for further use by the research community.