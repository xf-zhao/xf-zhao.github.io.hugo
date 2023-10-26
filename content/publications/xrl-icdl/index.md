---
title: "[📎 publication] A Closer Look at Reward Decomposition for High-Level Robotic Explanations"
date: 2023-06-30
draft: false
description: In IEEE International Conference on Development and Learning (ICDL), Nov 2023
tags: [reinforcement learning, robotics, conference paper, explainability]
series: ["publication"]
authors:
  - Wenhao Lu
  - Xufeng Zhao
  - Sven Magg
  - Martin Gromniak
  - Stefan Wermter
series_order: 3
# externalUrl: "https:logi-cot.github.io/"
---

{{< lead >}}
<a href="https://arxiv.org/abs/2304.12958"> 📄 arXiv </a> {{< /lead >}}.

Explaining the behavior of intelligent agents such as robots to humans is challenging due to their incomprehensible proprioceptive states, variational intermediate goals, and resultant unpredictability. Moreover, one-step explanations for reinforcement learning agents can be ambiguous as they fail to account for the agent’s future behavior at each transition, adding to the complexity of explaining robot actions. By leveraging abstracted actions that map to task-specific primitives, we avoid explanations on the movement level. Our proposed framework combines reward decomposition (RD) with abstracted action spaces into an explainable learning framework, allowing for non-ambiguous and high-level explanations based on object properties in the task. We demonstrate the effectiveness of our framework through quantitative and qualitative analysis of two robot scenarios, showcasing visual and textual explanations, from output artifacts of RD explanation, that are easy for humans to comprehend. Additionally, we demonstrate the versatility of integrating these artifacts with large language models for reasoning and interactive querying.
