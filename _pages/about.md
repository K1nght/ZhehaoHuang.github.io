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
# 🧑‍💻 About Me
I am currently a fourth-year Ph.D. student (Zhiyuan Honors) at the [Institute of Image Processing and Pattern Recognition](http://www.pami.sjtu.edu.cn/En/Home), [Shanghai Jiao Tong University](https://www.sjtu.edu.cn/), supervised by [Prof. Xiaolin Huang](http://www.pami.sjtu.edu.cn/xiaolin). My research focuses on **efficient adaptation methods** for large language models (LLMs) and vision-language models (VLMs), with particular interests in **continual learning** and its applications to **intelligent agents**. 

I am now visiting the MMLab at The Chinese University of Hong Kong (CUHK), under [Prof. Hongsheng Li](https://www.ee.cuhk.edu.hk/~hsli/).

I am always open to academic discussions and potential collaborations and and please feel free to contact me via email / wechat: HzKinght


<span class='anchor' id='news'></span>
# 🔥 News
- *2026.04*: &nbsp;🎉🎉 Our paper "[VL-RouterBench: A Benchmark for Vision-Language Model Routing](https://arxiv.org/abs/2512.23562)" is accepted by **CVPR 2026** as **Highlight**!
- *2026.02*: &nbsp;🎉🎉 Our paper "[RAIN-Merging: A Gradient-Free Method to Enhance Instruction Following in Large Reasoning Models with Preserved Thinking Format](https://openreview.net/forum?id=PO2iULmu5e)" is accepted by **ICLR 2026** as **Oral**!
- *2026.02*: &nbsp;🎉🎉 Our paper "[Remaining-data-free Machine Unlearning by Suppressing Sample Contribution](https://openreview.net/forum?id=3iw5t2W41F)" is accepted by **ICLR 2026** as **Poster**. Congrats to collaborators!
- *2026.02*: &nbsp;🎉🎉 Our paper "[Bi-LoRA: Efficient Sharpness-Aware Minimization for Fine-Tuning Large-Scale Models](https://openreview.net/forum?id=zoYPlgX1bH)" is accepted by **ICLR 2026** as **Poster**. Congrats to collaborators!
- *2025.08*: &nbsp;🎉🎉 Our paper "[Towards Natural Machine Unlearning](https://ieeexplore.ieee.org/document/11122296)" is accepted by **TPAMI**. Congrats to collaborators!
- *2025.01*: &nbsp;🎉🎉 Our paper "[Simulating Training Dynamics to Reconstruct Training Data from Deep Neural Networks](https://openreview.net/forum?id=ZJftXKy12x)" is accepted by **ICLR 2025** as **Poster**. Congrats to collaborators!
- *2024.09*: &nbsp;🎉🎉 Our paper "[Unified Gradient-Based Machine Unlearning with Remain Geometry Enhancement](https://neurips.cc/virtual/2024/poster/94324)" is accepted by **NeurIPS 2024** as **Spotlight**!
- *2024.04*: &nbsp;🎉🎉 Our paper "[Online Continual Learning via Logit Adjusted Softmax](https://openreview.net/forum?id=MyQKcQAte6)" is accepted by **TMLR 2024**.

<span class='anchor' id='publications'></span>
# 📝 Featured Publications ( * denotes equal contribution)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026 (Highlight)</div><img src='images/VL-RouterBench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VL-RouterBench: A Benchmark for Vision-Language Model Routing](https://arxiv.org/abs/2512.23562)

**Zhehao Huang**<sup>\*</sup>, Baijiong Lin<sup>\*</sup>, Jingyuan Zhang, Yuhang Liu, Ning Lu, Tao Li, Xiaolin Huang

[**Code**](https://github.com/K1nght/VL-RouterBench) \| [**Dataset**](https://huggingface.co/datasets/KinghtH/VL-RouterBench) \| [**Poster**]() \| [**Slides**]() (coming soon)

This paper addresses the lack of systematic evaluation for VLM routing by introducing **VL-RouterBench**, a comprehensive benchmark covering 14 datasets and 17 models that measures the trade-offs through evaluating 10 routing methods, it reveals a "routability gain" but highlights a gap between current routers and the Oracle, providing an open-source toolchain to advance more efficient, VLM routing deployments.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026 (Oral)</div><img src='images/RAIN-Merging.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RAIN-Merging: A Gradient-Free Method to Enhance Instruction Following in Large Reasoning Models with Preserved Thinking Format](https://openreview.net/forum?id=PO2iULmu5e)

**Zhehao Huang**, Yuhang Liu, Baijiong Lin, Yixin Lou, Zhengbao He, Hanling Tian, Tao Li, Xiaolin Huang

[**Code**](https://github.com/K1nght/RAIN-Merging) \| [**Project**]() \| [**Poster**]() \| [**Slides**]() (coming soon)

This paper identifies that LRMs struggle with strict instruction following despite reasoning, and introduces **RAIN-Merging**, a gradient-free method that integrates instruction-tuned features into the LRM's null space to preserve structured "thinking" formats while significantly enhancing constraint adherence across various scales and tasks without compromising reasoning quality.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/T2I-ConBench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[T2I-ConBench: Text-to-Image Benchmark for Continual Post-training](https://arxiv.org/abs/2505.16875)

**Zhehao Huang**<sup>\*</sup>, Yuhang Liu<sup>\*</sup>, Yixin Lou<sup>\*</sup>, Zhengbao He, Mingzhen He, Wenxing Zhou, Tao Li, Kehan Li, Zeyi Huang, Xiaolin Huang

[**Code**](https://github.com/K1nght/T2I-ConBench) \| [**Project**](https://k1nght.github.io/T2I-ConBench/) \| [**Dataset**](https://huggingface.co/datasets/T2I-ConBench/T2I-ConBench)

This paper identifies that naive continual post-training in text-to-image models causes catastrophic forgetting and loss of compositionality, and introduces **T2I-ConBench**, a unified benchmark that evaluates models across four key dimensions—including generality retention and cross-task generalization, providing a standardized foundation for future research.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/UG-CLU.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Unified Gradient-based Framework for Task-agnostic Continual Learning-Unlearning](https://arxiv.org/abs/2505.15178.pdf)

**Zhehao Huang**, Xinwen Cheng, Jie Zhang, Jinghao Zheng, Haoran Wang, Zhengbao He, Tao Li, Xiaolin Huang

This paper demonstrates that learning and forgetting are mathematically linked through a unified framework, and proposes **UG-CLU** to balance new knowledge acquisition with precise data removal by using a weight-adaptation mechanism and manifold constraints, enabling stable, task-agnostic unlearning at both the category and sample levels without retraining from scratch.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024 (Spotlight)</div><img src='images/sfr-on.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Unified Gradient-Based Machine Unlearning with Remain Geometry Enhancement](https://neurips.cc/virtual/2024/poster/94324)

**Zhehao Huang**, Xinwen Cheng, Jinghao Zheng, Haoran Wang, Zhengbao He, Tao Li, Xiaolin Huang

[**Code**](https://github.com/K1nght/Unified-Unlearning-w-Remain-Geometry) \| [**Project**](https://k1nght.github.io/Unified-Unlearning-project/) \| [**Poster**](https://neurips.cc/media/PosterPDFs/NeurIPS%202024/94324.png?t=1733198028.0248435) \| [**Slides**](https://neurips.cc/media/neurips-2024/Slides/94324.pdf)

This work proposes a fast-slow parameter update strategy to implicitly approximate the up-to-date salient unlearning direction, free from specific modal constraints, and adaptable across computer vision unlearning tasks, including classification and generation. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMLR 2024</div><img src='images/er-las.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Online Continual Learning via Logit Adjusted Softmax](https://openreview.net/forum?id=MyQKcQAte6)

**Zhehao Huang**, Tao Li, Chenhe Yuan, Yingwen Wu, Xiaolin Huang

[**Code**](https://github.com/K1nght/online_CL_logit_adjusted_softmax)

This paper shows that inter-class imbalance in online continual learning is fundamentally caused by imbalanced (time-varying) class priors, and proposes **Logit Adjusted Softmax (LAS)** to counter prior-induced bias by adjusting logits during training, improving performance across class-IL and class+domain incremental settings with minimal overhead.
</div>
</div>


<span class='anchor' id='honors'></span>
# 🎖 Honors and Awards
- *2021.04* 2021 Interdisciplinary Contest In Modeling (ICM) *Meritorious Winner*
- *2020.08* National University Intelligent Car Competition *National Third Prize*
- *2019.11* Shanghai Jiao Tong University *B Class Excellent Scholarship*（< 10%）

<span class='anchor' id='educations'></span>
# 📖 Educations
- *2022.09 - 2027.06 (expected)*, Ph.D. Student, Control Science and Engineering, Shanghai Jiao Tong University, China
- *2018.09 - 2022.06*, B.Eng., Automation, Shanghai Jiao Tong University, China

<span class='anchor' id='experience'></span>
# 💻 Experience
- *2024.06 - 2025.05*, Intern Algorithm Engineer, [Huawei](https://www.huawei.com/), Research on Continual Post-training for Text-to-Image Models.
- *2021.08 - 2022.01*, Intern Algorithm Engineer, [ByteDance](https://www.bytedance.com/), Advertising Business Algorithm Development.
