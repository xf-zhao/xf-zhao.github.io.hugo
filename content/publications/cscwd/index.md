---
title: "[📎 publication] Density Weighted Diversity Based Query Strategy for Active Learning"
date: 2021-05-01
draft: false
description: In 2021 IEEE 24th International Conference on Computer Supported Cooperative Work in Design (CSCWD), May 2021
tags: [active learning, conference paper]
series: ["publication"]
authors:
  - Tingting Wang
  - Xufeng Zhao
  - Qiujian Lv
  - Bo Hu
  - Degang Sun
series_order: 4
# cascade:
#   summaryLength: 30
---


Deep learning has made remarkable achievements in various domains. Active learning, which aims to reduce the budget for training a machine-learning model, is especially useful for the Deep learning tasks with the demand of a large number of labeled samples. Unfortunately, our empirical study finds that many of the active learning heuristics are not effective when applied to Deep learning models in batch settings. To tackle these limitations, we propose a density weighted diversity based query strategy (DWDS), which makes use of the geometry of the samples. Within a limited labeling budget, DWDS enhances model performance by querying labels for the new training samples with the maximum informativeness and representativeness. Furthermore, we propose a beam-search based method to obtain a good approximation to the optimum of such samples. Our experiments show that DWDS outperforms existing algorithms in Deep learning tasks.