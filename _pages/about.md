---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a PhD student major in Computer Science at Shanghai Jiao Tong University (SJTU), supervised by Prof. [Yue Gao](https://gaoyue.sjtu.edu.cn/).
Currently, I am conducting researches on Embodied AI at [Shanghai Innovation Institute](https://www.sii.edu.cn/) and [MoE key lab of Artificial Intelligence](https://ailab-moe.sjtu.edu.cn/).
Previously, I received my bachelor degree in Computer Science from IEEE honor class at SJTU. 

My research interest includes:

(1) **Reinforcement Learning (RL) algorithms:** Robust RL algorithms; Improve sample efficiency; Multi-task/Meta RL algorithms.

(2) **Embodied Artificial Intelligence:** Vision-Language-Action (VLA)-based robto manipulation; RL-based locomotion and imitation on legged/humanoid robots; 

I am a final year CS PhD student, expected to graduate in March 2026. Currently, I am looking for a job about Reinforcement Learning or Embodied AI.

# 📝 Publications 

## 🧠 Reinforcement Learning Algorithms

<!-- SDAR -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/SDAR3.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Select before Act: Spatially Decoupled Action Repetition for Continuous Control](https://arxiv.org/abs/2502.06919)

**Buqing Nie**, Yangqing Fu, Yue Gao. [Arxiv](https://arxiv.org/abs/2502.06919)  [Openreview](https://openreview.net/forum?id=PDgZ3rvqHn)
- a flexible action repetition framework for continuous control.
- higher efficiency, superior performance, reduced fluctuation.
- first work to consider spatial features into temporal abstraction.
</div>
</div>

<!-- SortRL -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/sortRL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Improve robustness of reinforcement learning against observation perturbations via $l_\infty$ lipschitz policy networks

**Buqing Nie**, Jingtian Ji, Yangqing Fu, Yue Gao. [Arxiv](https://arxiv.org/abs/2312.08751)
- improve certified robustness under observation adversaries.
- first work to improve robustness using Lipschitz property.
- improve performance over 20% (30% on strong perturbations).
</div>
</div>


<!-- OA-RL -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/OARL.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Action Robust Reinforcement Learning via Optimal Adversary Aware Policy Optimization](https://arxiv.org/abs/2507.03372)

**Buqing Nie**, Yangqing Fu, Yue Gao.  [Arxiv](https://arxiv.org/abs/2507.03372)
- improve robustn4ss under action adversaries
- formulate and prove OA-PI framework 
- training without finding adversaries explicitly
</div>
</div>

- ``NeurIPS 2024`` Accelerating Monte Carlo Tree Search with Probability Tree State Abstraction, Yangqing Fu, Ming Sun, **Buqing Nie**, Yue Gao.


## 🤖 Robotics & Embodied Artificial Intelligence

<!-- SE-Policy -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/SE-Policy.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Learning Symmetry Equivariant Deep Reinforcement Learning Policy for Humanoid Robots

**Buqing Nie**, et al. 
- DRL-based humanoid robot policy with strict symmetry equivariance
- simple to implement without additional hyper-parameters
- higher tracking accuracy with coordinated motions
</div>
</div>


<!-- DanceHAT -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2022</div><img src='images/dancehat.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

DanceHAT: Generate Stable Dances for Humanoid Robots with Adversarial Training

**Buqing Nie**, and Yue Gao.  [Paper](https://ieeexplore.ieee.org/document/9811649/)
- humanoid robot imitation learning using adversarial training
- first learning-based IL work for humanoid robot with stability
</div>
</div>

<!-- Lipsnet policy -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RAL 2024</div><img src='images/lipsnet_policy.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Robust Locomotion Policy with Adaptive Lipschitz Constraint for Legged Robots](https://ieeexplore.ieee.org/document/10767293/)

Yang Zhang, **Buqing Nie**, and Yue Gao.  [Paper](https://ieeexplore.ieee.org/document/10767293/)
- 
- higher smoothness, lower energy cost, robust to observation noise and disturbances.
</div>
</div>

- ``IROS 2025`` Minimizing Acoustic Noise: Enhancing Quiet Locomotion for Quadruped Robots in Indoor Applications, Zhanxiang Cao, **Buqing Nie**, Yang Zhang, Yue Gao.
- ``Under Review`` Learning Motion Skills with Adaptive Assistive Curriculum Force in Humanoid Robots. Zhanxiang Cao, Yang Zhang, **Buqing Nie**, Huangxuan Lin, Haoyang Li, Yue Gao.
- ``Under Review`` Disturbance-Aware Adaptive Compensation in Hybrid Force-Position Locomotion Policy for Legged Robots, Yang Zhang, **Buqing Nie**, Zhanxiang Cao, Yangqing Fu, Yue Gao.
- ``IJRA 2022`` Capability Iteration Network for Robot Path Planning, **Buqing Nie**, Yidong Mei, Yue Gao, Feng Gao.
- ``ROBIO 2022`` Structure-Aware Policy to Improve Generalization among Various Robots and Environments, Wei Xu, Yue Gao, **Buqing Nie**.

# 📖 Educations
- *2022.04 - 2026.03*, PhD Candidate (combined master and doctoral program), Computer Science, Department of Computer Science, Shanghai Jiao Tong University.
- *2020.09 - 2022.04*, Master, Control Science and Engineering, Department of Automation, Shanghai Jiao Tong University.
- *2016.06 - 2020.04*, Bachelor, Computer Science (IEEE honor class), Department of Computer Science, Shanghai Jiao Tong University.


# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  

# 💻 Academic Services
I serve as a reviewer for AI/robotics conferences/journals, including ICLR 2025, NeurIPS 2025, ICRA 2025, IROS 2025, RAL, etc.
