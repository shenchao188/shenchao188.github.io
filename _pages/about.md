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

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Applied Energy 2026</div><img src='images/Universal_transient_stability.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Universal transient stability analysis: A pre-trained generative transformer-enabled power system dynamics prediction framework](https://doi.org/10.1016/j.apenergy.2026.128028)

**Chao Shen**, Ke Zuo, Mingyang Sun

*Applied Energy*, 2026. (Top, SCI Q1, IF 12.2)
- Proposes Uni-TSA, a pre-trained generative Transformer framework for universal transient stability dynamics prediction across operating conditions, faults, and power systems.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/optargus.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OptArgus: A Multi-Agent System to Detect Hallucinations in LLM-based Optimization Modeling](https://arxiv.org/abs/2605.11738)

Zhong Li, Zihan Guo, Xiaohan Lu, Juntao Wang, Jie Song, **Chao Shen**, Jiageng Wu, Mingyang Sun

*arXiv preprint*, 2026.
- Detects optimization-modeling hallucinations by routing artifacts to specialist LLM auditors and checking structural consistency across problem descriptions, symbolic models, and solver code.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Applied Energy 2026</div><img src='images/LLM_guided_safe.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LLM-Guided Safe Reinforcement Learning for Energy System Topology Reconfiguration](https://arxiv.org/abs/2603.14018)

Zongyan Zhang, **Chao Shen**, Xu Wan, Jie Song, Mingyang Sun

*Applied Energy*, 2026. (Top, SCI Q1, IF 12.2)
- Integrates LLM-based domain reasoning with safe reinforcement learning to improve topology reconfiguration under operational voltage and thermal constraints.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/ProOPF.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ProOPF: Benchmarking and Improving LLMs for Professional-Grade Power Systems Optimization Modeling](https://arxiv.org/abs/2602.03070)

**Chao Shen**, Zihan Guo, Xu Wan, Zhen Yang, Yifan Zhang, Wen Huang, Jie Song, Zongyang Zhang, Mingyang Sun

*International Conference on Machine Learning (ICML)*, 2026. (CCF-A)
- Introduces ProOPF-D and ProOPF-B, a dataset and benchmark for evaluating LLMs on professional-grade optimal power flow modeling from natural-language requirements.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TII 2026</div><img src='images/LLM_DMD.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LLM-DMD: Large Language Model-based Power System Dynamic Model Discovery](https://arxiv.org/abs/2601.05632)

**Chao Shen**, Zihan Guo, Ke Zuo, Wen Huang, Mingyang Sun

*IEEE Transactions on Industrial Informatics*, 2026. (Top, SCI Q1, IF 9.8)
- Uses LLM reasoning and code synthesis to discover power system dynamic equations while enforcing algebraic constraints through iterative differential and algebraic equation loops.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPWRS 2025</div><img src='images/Probalistic_robustness.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Probabilistic Robustness Verified Data-Driven Transient Security-Constrained Optimal Power Flow](https://doi.org/10.1109/TPWRS.2025.3608814)

Ke Zuo, **Chao Shen**, Peng Cheng, Jie Song, Mingyang Sun

*IEEE Transactions on Power Systems*, 2025. (Top, SCI Q2, IF 8.7)
- Develops a data-driven transient security-constrained optimal power flow method with probabilistic robustness verification for transient security requirements.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TII 2025</div><img src='images/physics_argumented.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Physics-augmented auxiliary learning for power system transient stability assessment](https://doi.org/10.1109/TII.2025.3567400)

**Chao Shen**, Ke Zuo, Mingyang Sun

*IEEE Transactions on Industrial Informatics*, 2025. (Top, SCI Q1, IF 9.8)
- Proposes a physics-augmented auxiliary learning framework for transient stability assessment that improves accuracy and physical consistency via auxiliary electrical velocity prediction.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPWRS 2025</div><img src='images/physics_following.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Physics-following neural network for online dynamic security assessment](https://doi.org/10.1109/TPWRS.2025.3556813)

**Chao Shen**, Ke Zuo, Mingyang Sun

*IEEE Transactions on Power Systems*, 2025. (Top, SCI Q2, IF 8.7)
- Introduces a physics-following neural network for online dynamic security assessment, combining supervised initialization with dynamics-guided local learning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CAC 2024</div><img src='images/carbon_neuralGC.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Carbon-NeuGC: Neural Granger Causality Based Attribution Analysis of Power System Carbon Intensity](https://doi.org/10.1109/CAC63892.2024.10864688)

**Chao Shen**, Fengzhou Sun, Hao Chen, Yi Lin, Chuangxin Guo, Mingyang Sun

*China Automation Congress (CAC)*, 2024.
- Uses component-wise LSTM models with group lasso regularization to identify Granger-causal relationships for power system carbon intensity attribution.
</div>
</div>

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
