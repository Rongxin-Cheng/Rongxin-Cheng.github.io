---
title:          "Characterizing off-path SmartNIC for accelerating distributed systems"
# date:           2023-03
selected:       true
pub:            "17th USENIX Symposium on Operating Systems Design and Implementation (OSDI 23)"
pub_date:       "2023"
# abstract: >-
#   SmartNICs have recently emerged as an appealing device for accelerating distributed systems. However, there has not been a comprehensive characterization of SmartNICs, and existing designs typically only leverage a single communication path for workload offloading. This paper presents the first holistic study of a representative off-path SmartNIC, specifically the Bluefield-2, from a communication-path perspective. Our experimental study systematically explores the key performance characteristics of communication among the client, on-board SoC, and host, and offers insightful findings and advice for designers. Moreover, we propose the concurrent use of multiple communication paths of a SmartNIC and present a pioneering guideline to expose new optimization opportunities for various distributed systems. To demonstrate the effectiveness of our approach, we conducted case studies on a SmartNIC-based distributed file system (LineFS) and an RDMA-based disaggregated key-value store (DrTM-KV). Our experimental results show improvements of up to 30% and 25% for LineFS and DrTM-KV, respectively.
# cover:          /assets/images/covers/cover1.jpg
authors:
- Xingda Wei
- <strong>Rongxin Cheng</strong>
- Yuhan Yang
- Rong Chen
- Haibo Chen
links:
  Paper: https://www.usenix.org/conference/osdi23/presentation/wei-smartnic
---