---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

_You can find my publications on [my Google Scholar Profile](https://scholar.google.com/citations?user=dpJU4IcAAAAJ&hl=en)._

Overview
------

I am interested in developing AI agents (and/or robots) that can collaborate coherently with humans.
Currently, I am working on two of the core problems:
1. _Persistent_ and _interpretable_ policy updates based on human feedback (how AI agents can _**adapt**_ to humans)
2. Human behavior modeling (how AI agents can _**understand**_ humans)

I believe these two problems complement each other (representing the explicit and implicit communications from the human to the agent respectively) and are fundamental to human-AI / human-robot interaction. Many other open questions in algorithmic human-robot interaction can be reduced to them. For example:
1. **End-user programming**: It is essentially humans using **commands as feedback** to update the agents' policy.
2. **Human-agent mutual adaptation**: Joint adaptation is complicated as the agent has to learn the task, the human's policy, the human's current belief of the agent... An easier alternative is to have the agent reveal its current policy, let the human decide how the work should be split, and assign the agent's role through policy adaptation.
3. **Objective alignment**: As it is extremely challenging to fully specify the _intrinsic_ objective function of the human in one go, it is easier to **iteratively adapt the policy** of the AI agent to align with the human's true objective.
4. **Safety**: Persistency entails no repeated mistakes (safety in seen environments), and interpretability enables formal verifications of the agent's policy (safety in unseen environments).

To solve the first problem, I aim to draw inspiration from the cognition level (not neuron level!) of human intelligence to inform the design of AI agents.
At the moment I am particularly interested in the use of **Cognitive Architectures** with the help of _Large Language Models_.

To solve the second problem, I have accumulated experience with different deep learning backbones (e.g., multi-modal transformers, random forest, etc.) and feature engineering methods.

Projects
------

**[Policy Adaptation] [Undergraduate Honors Thesis] Incorporating Instructive Feedback in Human-AI Collaboration**<br>
<span style="font-size:0.9em;"> [AAAI 2024 under 2nd phase review] [[poster](https://zfy0314.github.io/files/thesis_poster_04282023.pdf)] [[3MT](https://youtu.be/5_6ujpwyREU)] </span><br>
Details to be added

**[Human Modeling] Home-based Stroke Patients Function Evaluation**<br>
<span style="font-size:0.9em;"> [[slides](https://zfy0314.github.io/files/stroke_summary.pdf)] </span><br>
Details to be added

**[Human Modeling] Action Anticipation in Ego-centric Kitchen Videos**<br>
<span style="font-size:0.9em;"> [[report](https://zfy0314.github.io/files/action_anticipation.pdf)] </span><br>
Details to be added

**[Policy Adaptation] Rapid Adaptation to Human Partners in Hanabi**<br>
<span style="font-size:0.9em;"> [[code](https://github.com/zfy0314/Hanabi-HumanAI)] </span><br>
Details to be added

**[Human Modeling] Pedestrian Tracking Test Time Augmentation**<br>
<span style="font-size:0.9em;"> [[CVPR 2020](https://openaccess.thecvf.com/content_CVPR_2020/html/Huang_SQE_a_Self_Quality_Evaluation_Metric_for_Parameters_Optimization_in_CVPR_2020_paper.html)] [[video](https://youtu.be/7JTCqv6vKC0?si=p8zROLS80muNON5z)] </span><br>
Details to be added
