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

I am currently a Ph.D. candidate in Control Science and Engineering at the [College of Control Science and Engineering](http://www.cse.zju.edu.cn/), [Zhejiang University](https://www.zju.edu.cn/english/). I am advised by Prof. [Mingyang Sun](https://www.coe.pku.edu.cn/teaching/yongforeign/12884.html) and Prof. [Peng Cheng](https://person.zju.edu.cn/cp). I am also a visiting Ph.D. student at the [IDEAL Lab](https://www.ideallab-smy.com/), [Peking University](https://english.pku.edu.cn/).

My research interests lie in the integration of artificial intelligence with power and energy systems, with a focus on large language models, reinforcement learning, power system dynamic security analysis, optimal topology reconfiguration, and optimal power flow. I am currently working on foundation-model-based methods for power system modeling, simulation, optimization, and decision-making, as well as domain-specific benchmark construction and evaluation protocols for reliable AI in power systems.

My research aims to contribute to reliable, interpretable, and scalable intelligent systems for future low-carbon power and energy systems.

For more information, please take a look at my [Google Scholar](https://scholar.google.com/citations?user=mQYrZ4gAAAAJ&hl=zh-CN) and [GitHub](https://github.com/shenchao188).


# 🔥 News
- *2026.06*: &nbsp;🎉🎉 Our paper [**Universal Transient Stability Analysis**](https://doi.org/10.1016/j.apenergy.2026.128028) was published in *Applied Energy*.
- *2026.06*: &nbsp;🎉🎉 Our paper [**LLM-guided safe reinforcement learning**](https://arxiv.org/abs/2603.14018) for energy system topology reconfiguration was accepted by *Applied Energy*.
- *2026.05*: &nbsp;🎉🎉 Our work [**ProOPF**](https://arxiv.org/abs/2602.03070) was accepted by *ICML 2026*.
- *2026.05*: &nbsp;🎉🎉 Our paper [**LLM-DMD**](https://arxiv.org/abs/2601.05632) was accepted by *IEEE Transactions on Industrial Informatics*.
- *2026.02*: &nbsp;🎉🎉 Our paper [**Physics-following neural networks**](https://doi.org/10.1109/TPWRS.2025.3556813) was recognized by Web of Science as an ESI Highly Cited Paper (Engineering).
- *2025.09*: &nbsp;🎉🎉 Our paper on [**probabilistic robustness verified TSCOPF**](https://doi.org/10.1109/TPWRS.2025.3608814) was accepted by *IEEE Transactions on Power Systems*.
- *2025.06*: &nbsp;🎉🎉 Our paper on [**physics-augmented auxiliary learning**](https://doi.org/10.1109/TII.2025.3567400) for transient stability assessment was accepted by *IEEE Transactions on Industrial Informatics*.
- *2025.04*: &nbsp;🎉🎉 Our paper on [**physics-following neural networks**](https://doi.org/10.1109/TPWRS.2025.3556813) for online dynamic security assessment was accepted by *IEEE Transactions on Power Systems*.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Applied Energy Under Review</div><img src='images/workload_resahpe.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Workload reshaping and waste heat valorization for token cost reduction in large model datacenters: A two stage forecasting and optimization framework](https://shenchao188.github.io/)

Junyan Shao, **Chao Shen**, Zihan Guo, Yujia Huang, Mingyang Sun

*Applied Energy Under Review*, 2026.
- The first work links token-level workload reshaping with waste heat valorization, opening a new optimization pathway for cost-efficient large-model datacenters.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2026 Under Review</div><img src='images/optargus.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OptArgus: A Multi-Agent System to Detect Hallucinations in LLM-based Optimization Modeling](https://arxiv.org/abs/2605.11738)

Zhong Li, Zihan Guo, Xiaohan Lu, Juntao Wang, Jie Song, **Chao Shen**, Jiageng Wu, Mingyang Sun

*NeurIPS 2026 Under Review*, 2026.
- OptArgus is among the first systems to formalize optimization-modeling hallucination detection, using specialist agents to catch structural errors missed by objective-value checks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Applied Energy 2026</div><img src='images/Universal_transient_stability.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Universal transient stability analysis: A pre-trained generative transformer-enabled power system dynamics prediction framework](https://doi.org/10.1016/j.apenergy.2026.128028)

**Chao Shen**, Ke Zuo, Mingyang Sun

*Applied Energy*, 2026. (Power/Energy Top, SCI Q1, IF 12.2)
- Uni-TSA presents a first universal transient-stability prediction framework that can generalize across operating conditions, fault scenarios, and even unseen power systems.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Applied Energy 2026</div><img src='images/LLM_guided_safe.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LLM-Guided Safe Reinforcement Learning for Energy System Topology Reconfiguration](https://arxiv.org/abs/2603.14018)

Zongyan Zhang, **Chao Shen**, Xu Wan, Jie Song, Mingyang Sun

*Applied Energy*, 2026. (Power/Energy Top, SCI Q1, IF 12.2)
- This work pioneers an LLM-guided safe RL paradigm for topology reconfiguration, injecting domain reasoning into safety-critical switching decisions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/ProOPF.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ProOPF: Benchmarking and Improving LLMs for Professional-Grade Power Systems Optimization Modeling](https://arxiv.org/abs/2602.03070)

**Chao Shen**, Zihan Guo, Xu Wan, Zhen Yang, Yifan Zhang, Wen Huang, Jie Song, Zongyang Zhang, Mingyang Sun

*International Conference on Machine Learning (ICML)*, 2026. (CCF-A)
- ProOPF introduces the first professional-grade OPF benchmark for LLMs, moving text-to-optimization evaluation from toy tasks to realistic power-system modeling.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TII 2026</div><img src='images/LLM_DMD.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LLM-DMD: Large Language Model-based Power System Dynamic Model Discovery](https://arxiv.org/abs/2601.05632)

**Chao Shen**, Zihan Guo, Ke Zuo, Wen Huang, Mingyang Sun

*IEEE Transactions on Industrial Informatics*, 2026. (Automation/AI Top, SCI Q1, IF 9.8)
- LLM-DMD is an early attempt to use LLM agents for power-system dynamic model discovery, jointly searching differential equations and algebraic constraints.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPWRS 2025</div><img src='images/Probalistic_robustness.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Probabilistic Robustness Verified Data-Driven Transient Security-Constrained Optimal Power Flow](https://doi.org/10.1109/TPWRS.2025.3608814)

Ke Zuo, **Chao Shen**, Peng Cheng, Jie Song, Mingyang Sun

*IEEE Transactions on Power Systems*, 2025. (Power/Energy Top, SCI Q2, IF 8.7)
- This study advances data-driven TSCOPF by adding probabilistic robustness verification, making learned security constraints more reliable under uncertainty.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TII 2025</div><img src='images/physics_argumented.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Physics-augmented auxiliary learning for power system transient stability assessment](https://doi.org/10.1109/TII.2025.3567400)

**Chao Shen**, Ke Zuo, Mingyang Sun

*IEEE Transactions on Industrial Informatics*, 2025. (Automation/AI Top, SCI Q1, IF 9.8)
- PA-AL introduces physics-augmented auxiliary learning for TSA, using electrical velocity as a new auxiliary signal to improve both accuracy and physical consistency.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPWRS 2025</div><img src='images/physics_following.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Physics-following neural network for online dynamic security assessment](https://doi.org/10.1109/TPWRS.2025.3556813)

**Chao Shen**, Ke Zuo, Mingyang Sun

*IEEE Transactions on Power Systems*, 2025. (Power/Energy Top, SCI Q2, IF 8.7)
- PFNN moves beyond generic physics-informed learning by explicitly following power-system dynamics for online security assessment.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CAC 2024</div><img src='images/carbon_neuralGC.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Carbon-NeuGC: Neural Granger Causality Based Attribution Analysis of Power System Carbon Intensity](https://doi.org/10.1109/CAC63892.2024.10864688)

**Chao Shen**, Fengzhou Sun, Hao Chen, Yi Lin, Chuangxin Guo, Mingyang Sun

*China Automation Congress (CAC)*, 2024.
- Carbon-NeuGC provides a neural Granger-causality framework for attributing power-system carbon intensity, enabling more interpretable carbon-flow analysis.
</div>
</div>

# 🎖 Honors and Awards
- *2026.02*: [**PFNN**](https://doi.org/10.1109/TPWRS.2025.3556813) was recognized by Web of Science as an ESI Highly Cited Paper (Engineering).
- *2025.11*: Outstanding Graduate Student, Zhejiang University.
- *2021.10*: National Scholarship.
- *2021.04*: Finalist, Contemporary Undergraduate Mathematical Contest in Modeling (Top 2%).
- *2020.01*: First Prize, China Undergraduate Mathematical Contest in Mathematics (Top 8%).

# 📖 Education

- *Sep 2022 - Present*, **Zhejiang University**, College of Control Science and Engineering. **Ph.D. Candidate in Control Science and Engineering** (GPA: 3.90/4.0). Supervisors: [Mingyang Sun](https://www.coe.pku.edu.cn/teaching/yongforeign/12884.html) and [Peng Cheng](https://person.zju.edu.cn/cp).
- *Jul 2024 - Present*, **Peking University**, College of Engineering. **Visiting Ph.D. Student at the Intelligent DEcision-mAking for Low Carbon Energy Systems Laboratory** ([IDEAL Lab](https://www.ideallab-smy.com/)). Supervisor: [Mingyang Sun](https://www.coe.pku.edu.cn/teaching/yongforeign/12884.html).
- *Sep 2018 - Jun 2022*, **Huazhong University of Science and Technology**, School of Civil and Hydraulic Engineering. **B.Eng. in Hydraulic and Hydropower Engineering** (GPA: 3.96/4.0). Supervisor: [Hui Qin](https://civil.hust.edu.cn/info/1312/9985.htm).

# 🤝 Services
- Invited reviewer for *IEEE Transactions on Power Systems*.
- Invited reviewer for *IEEE Transactions on Smart Grid*.
- Invited reviewer for *Applied Energy*.
- Invited reviewer for *International Journal of Electrical Power & Energy Systems*.
- Invited reviewer for *Electric Power Systems Research*.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
