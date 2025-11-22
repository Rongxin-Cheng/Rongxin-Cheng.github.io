---
title:          "Characterizing the dilemma of performance and index size in billion-scale vector search and breaking it with second-tier memory"
# date:           2024-05-12 00:01:00 +0800
selected:       true
pub:            "ArXiv preprint"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2024"
# semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776  # use this to retrieve citation count
# abstract: >-
#   Vector searches on large-scale datasets are critical to modern online services like web search and RAG, which necessity storing the datasets and their index on the secondary storage like SSD. In this paper, we are the first to characterize the trade-off of performance and index size in existing SSD-based graph and cluster indexes: to improve throughput by 5.7× and 1.7×, these indexes have to pay a 5.8× storage amplification and 7.7× with respect to the dataset size, respectively. The root cause is that the coarse-grained access of SSD mismatches the fine-grained random read required by vector indexes with small amplification.
#   This paper argues that second-tier memory, such as remote DRAM/NVM connected via RDMA or CXL, is a powerful storage for addressing the problem from a system's perspective, thanks to its fine-grained access granularity. However, putting existing indexes -- primarily designed for SSD -- directly on second-tier memory cannot fully utilize its power. Meanwhile, second-tier memory still behaves more like storage, so using it as DRAM is also inefficient. To this end, we build a graph and cluster index that centers around the performance features of second-tier memory. With careful execution engine and index layout designs, we show that vector indexes can achieve optimal performance with orders of magnitude smaller index amplification, on a variety of second-tier memory devices.
#   Based on our improved graph and vector indexes on second-tier memory, we further conduct a systematic study between them to facilitate developers choosing the right index for their workloads. Interestingly, the findings on the second-tier memory contradict the ones on SSDs.
# cover:          /assets/images/covers/cover3.jpg
authors:
  - <strong>Rongxin Cheng</strong>
  - Yifan Peng
  - Xingda Wei
  - Hongrui Xie
  - Rong Chen
  - Sijie Shen
  - Haibo Chen
links:
  Paper: https://arxiv.org/abs/2405.03267
---
