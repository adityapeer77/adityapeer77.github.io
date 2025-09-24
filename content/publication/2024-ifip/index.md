---
title: "CoDel-ACT: Realizing CoDel AQM for Programmable Switch ASIC"
date: 2024-06-3
publishDate: 2024-06-3
authors: ["Vedant Bothra *", "**Aditya Peer * **", "Vijay Kumar Singh", "Rinku Shah"]
publication_types: ["1"]
abstract: "Bufferbloat is a major issue in computer networks,caused by network devices such as switches and routers with large buffers, resulting in congested queues and high network delays. Active Queue Management (AQM) algorithms like RED, CoDel, and PIE have been developed to address Bufferbloat. Among these, CoDel is the most effective as it does not require parameter tuning. However, software-based AQM solutions cannot scale for high-speed networks, while traditional hardware switches are fixed-function. Programmable switch ASICs offer more flexibility but impose programming constraints to achieve line rates. Due to these limitations, previous research has been unsuccessful in implementing an RFC-compliant CoDel AQM on programmable switch ASICs. To solve this challenge, we have introduced CoDel-ACT, a redesign of CoDel that can handle the global state across switch pipeline stages, improves the accuracy of the math function, and fully implements CoDel within the data plane of an Intel Tofino switch. Our evaluations demonstrate that CoDel-ACT solves Bufferbloat, has negligible overheads, and reduces the average packet queue delay by 52% compared to the existing solution."
featured: false
publication: "IFIP Conference 2024"
links:
  - icon_pack: fas
    icon: scroll
    name: Link
    url: 'https://doi.org/10.23919/IFIPNetworking62109.2024.10619729'
---