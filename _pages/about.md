---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I joined Computer Science & Engineering (CSE) Department at Washington University in St. Louis (WashU) in 2024 as an Assistant Professor. I received my Ph.D. degree in Computer Science Department, UIUC, advised by Prof. [Jiawei Han](http://hanj.cs.illinois.edu). After that, I visited UW as a researcher and worked with Prof. [Hanna Hajishirzi](https://homes.cs.washington.edu/~hannaneh/). Prior to UIUC, I received my Bachelor Degree in Electronic Engineering in Tsinghua University in 2018. My research interest broadly lies in the intersection of natural language processing and machine learning, and I am especially interested in understanding the properties of **language models** as well as improving their **trustworthiness** and **efficiency**.

<div style="background-color: #fff5f0; border-left: 6px solid coral; border-radius: 6px; padding: 14px 20px; margin: 18px 0; font-size: 1.05em">
<p style="margin: 0">📢 <strong>I am looking for PhD students and interns!</strong> If you are interested in working with me, please fill in <a href="https://docs.google.com/forms/d/e/1FAIpQLSeFDUgS0Q6CiH2-SjztPRwPP4DxCED5THhKdTOgIP3fh4LSTw/viewform">this form</a>. <span style="color: coral"><strong>Check out <a href="https://teapot123.github.io/application/" style="color: coral">this page</a> for more details!</strong></span></p>
</div>


News
======
<div style="background-color: #fff5f0; border: 2px solid coral; border-radius: 8px; padding: 20px 24px; margin: 15px 0">
<ul style="line-height:26px; margin-bottom: 0; padding-left: 22px">
  <li><span style="color: coral"><strong>[Oct 2026]</strong></span> Gave a guest lecture on <em>Sustainable Self-Evolving Models</em> at <strong>Virginia Tech</strong>, for the course <em>From Foundation Models to AI Agents</em>.</li>
  <li><span style="color: coral"><strong>[Sep 2026]</strong></span> Two papers accepted to NeurIPS 2026: <em><a href="https://arxiv.org/abs/2605.09959" target="_blank">G-Zero</a></em> (<span style="color: #cc0000"><strong>spotlight</strong></span>, top 1.3%) and <em><a href="https://arxiv.org/abs/2605.21468" target="_blank">Minimal RLVR</a></em>. See you in Atlanta!</li>
  <li><span style="color: coral"><strong>[Aug 2026]</strong></span> Two papers accepted to EMNLP 2026: <em><a href="https://www.arxiv.org/abs/2601.05167" target="_blank">RelayLLM</a></em> and <em><a href="https://arxiv.org/abs/2605.05566" target="_blank">Nonsense Helps (LoPE)</a></em>.</li>
  <li><span style="color: coral"><strong>[Jun 2026]</strong></span> <em><a href="https://openreview.net/forum?id=ugRJVwcjbZ" target="_blank">SPEED</a></em> accepted to COLM 2026. See you in San Francisco!</li>
  <li><span style="color: coral"><strong>[May 2026]</strong></span> Received the <strong>NSF CAREER Award</strong>!</li>
  <li><span style="color: coral"><strong>[May 2026]</strong></span> Received the <strong>WashU AI for Health Grant</strong>!</li>
  <li><span style="color: coral"><strong>[May 2026]</strong></span> Three papers accepted to ICML 2026: <em><a href="https://arxiv.org/abs/2602.04145" target="_blank">Training Data Efficiency in Multimodal Process Reward Models</a></em>, <em><a href="https://arxiv.org/abs/2602.03845" target="_blank">Parallel-Probe</a></em>, and <em><a href="https://arxiv.org/abs/2602.03689" target="_blank">Rethinking the Reranker</a></em>.</li>
  <li><span style="color: coral"><strong>[Feb 2026]</strong></span> <em><a href="https://www.arxiv.org/abs/2511.15661" target="_blank">VisPlay</a></em> accepted to CVPR 2026.</li>
  <li><span style="color: coral"><strong>[Jan 2026]</strong></span> Selected for the <strong>AAAI New Faculty Highlight Program 2026</strong>.</li>
  <li><span style="color: coral"><strong>[Jan 2026]</strong></span> Two papers accepted to ICLR 2026: <em><a href="https://www.arxiv.org/abs/2508.05004" target="_blank">R-Zero</a></em> and <em><a href="https://arxiv.org/abs/2503.00031" target="_blank">Self-Calibration</a></em>.</li>
</ul>
</div>


Recent Research Interests
======

<style>
.rc-title {
  color: #c2552f;
  font-size: 1.12em;
  font-weight: 700;
  line-height: 1.35;
  margin: 30px 0 3px;
  padding-left: 13px;
  border-left: 5px solid coral;
}
.rc-desc {
  margin: 0 0 10px 18px;
  color: #7b7b7b;
  font-style: italic;
  font-size: 0.95em;
}
.rc-title + .rc-desc + ul {
  list-style: none;
  padding-left: 18px;
  margin-top: 0;
}
.rc-title + .rc-desc + ul > li {
  margin: 0 0 8px;
  line-height: 1.5;
}
.rc-venue {
  display: inline-block;
  min-width: 92px;
  text-align: center;
  background: #fff1ec;
  color: #c2552f;
  border: 1px solid #ffd6c7;
  border-radius: 4px;
  padding: 1px 8px;
  margin-right: 8px;
  font-size: 0.78em;
  font-weight: 700;
  letter-spacing: 0.02em;
  vertical-align: 1px;
}
.rc-authors { color: #6b6b6b; font-size: 0.92em; }
.rc-spotlight {
  color: #cc0000;
  font-size: 0.8em;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.04em;
  margin-left: 6px;
}
</style>

My group studies how to make language models **self-improving**, **efficient**, and **trustworthy**. Selected recent work:

<h3 class="rc-title">Self-Evolving Models: Learning without Human-Curated Data</h3>
<p class="rc-desc">Training models that generate their own tasks, data, and environments.</p>

* <span class="rc-venue">ICLR 2026</span> <span class="rc-authors">Chengsong Huang <em>et al.</em></span> **[R-Zero: Self-Evolving Reasoning LLM from Zero Data](https://www.arxiv.org/abs/2508.05004)**
* <span class="rc-venue">CVPR 2026</span> <span class="rc-authors">Yicheng He <em>et al.</em></span> **[VisPlay: Self-Evolving Vision-Language Models from Images](https://www.arxiv.org/abs/2511.15661)**
* <span class="rc-venue">NeurIPS 2026</span> <span class="rc-authors">Chengsong Huang <em>et al.</em></span> **[G-Zero: Self-Play for Open-Ended Generation from Zero Data](https://arxiv.org/abs/2605.09959)** <span class="rc-spotlight">spotlight</span>
* <span class="rc-venue">Preprint 2026</span> <span class="rc-authors">Jinyuan Li <em>et al.</em></span> **[Questioning the Questions: Sustaining Self-Evolution in Reasoning Models](https://arxiv.org/abs/2610.04299)**
* <span class="rc-venue">Preprint 2026</span> <span class="rc-authors">Chengsong Huang <em>et al.</em></span> **[EnvHarness: Awakening Static Worlds for Agent Learning](https://arxiv.org/abs/2608.19880)**
* <span class="rc-venue">EMNLP 2023</span> <span class="rc-authors">Jiaxin Huang <em>et al.</em></span> **[Large Language Models Can Self-Improve](https://arxiv.org/abs/2210.11610)**

<h3 class="rc-title">Reinforcement Learning and Exploration for Reasoning</h3>
<p class="rc-desc">How reasoning improves under RL, and how to keep exploration broad.</p>

* <span class="rc-venue">NeurIPS 2026</span> <span class="rc-authors">Zhepei Wei <em>et al.</em></span> **[You Only Need Minimal RLVR Training: Extrapolating LLMs via Rank-1 Trajectories](https://arxiv.org/abs/2605.21468)**
* <span class="rc-venue">EMNLP 2026</span> <span class="rc-authors">Langlin Huang <em>et al.</em></span> **[Nonsense Helps: Prompt Space Perturbation Broadens Reasoning Exploration](https://arxiv.org/abs/2605.05566)**
* <span class="rc-venue">COLM 2025</span> <span class="rc-authors">Jixuan Leng <em>et al.</em></span> **[CrossWordBench: Evaluating the Reasoning Capabilities of LLMs with Controllable Puzzle Generation](https://arxiv.org/abs/2504.00043)**

<h3 class="rc-title">Efficient Reasoning and Inference</h3>
<p class="rc-desc">Reducing the cost of long reasoning chains at training and inference time.</p>

* <span class="rc-venue">EMNLP 2026</span> <span class="rc-authors">Chengsong Huang <em>et al.</em></span> **[RelayLLM: Efficient Reasoning via Collaborative Decoding](https://www.arxiv.org/abs/2601.05167)**
* <span class="rc-venue">COLM 2026</span> <span class="rc-authors">Langlin Huang <em>et al.</em></span> **[SPEED: Position Specialist Generates Better Draft for Speculative Decoding](https://arxiv.org/abs/2506.03566)**
* <span class="rc-venue">ICML 2026</span> <span class="rc-authors">Tong Zheng <em>et al.</em></span> **[Parallel-Probe: Towards Efficient Parallel Thinking via 2D Probing](https://arxiv.org/abs/2602.03845)**
* <span class="rc-venue">EACL 2026</span> <span class="rc-authors">Chengsong Huang <em>et al.</em></span> **[Divide, Reweight, and Conquer: A Logit Arithmetic Approach for In-Context Learning](https://arxiv.org/abs/2410.10074v1)**

<h3 class="rc-title">Reward Modeling and Calibration</h3>
<p class="rc-desc">Making reward signals and model confidence reliable enough to train on.</p>

* <span class="rc-venue">ICLR 2026</span> <span class="rc-authors">Chengsong Huang <em>et al.</em></span> **[Efficient Test-Time Scaling via Self-Calibration](https://arxiv.org/abs/2503.00031)**
* <span class="rc-venue">ICML 2026</span> <span class="rc-authors">Jinyuan Li <em>et al.</em></span> **[Training Data Efficiency in Multimodal Process Reward Models](https://arxiv.org/abs/2602.04145)**
* <span class="rc-venue">ICLR 2025</span> <span class="rc-authors">Jixuan Leng <em>et al.</em></span> **[Taming Overconfidence in LLMs: Reward Calibration in RLHF](https://arxiv.org/abs/2410.09724)**
* <span class="rc-venue">Preprint 2026</span> <span class="rc-authors">Jinyuan Li <em>et al.</em></span> **[Process Rewards with Learned Reliability](https://arxiv.org/abs/2605.15529)**



<a id="awards"></a>

Honors and Awards
======
NSF CAREER Award  2026  
AAAI New Faculty Highlight Program  2026  
Microsoft Research PhD Fellowship  2021-2023  
C.W. Gear Outstanding Graduate Award  
Chirag Foundation Graduate Fellowship  
Outstanding Graduates, Tsinghua University  2018  
Academic Excellence Scholarship, Tsinghua University  2015-2017  
China National Scholarship (Top 1%)  2016  
Samsung Scholarship  2015  

 
<!---
Education
======
* University of Illinois, Urbana-Champaign (2018.08-2023.12)  
  Ph.D. in Computer Science  
  Research Interest: Natural Language Processing, Data Mining  
  Advisor: Prof. [Jiawei Han](http://hanj.cs.illinois.edu)  

* Tsinghua University (2014.08-2018.07)  
  B. Eng. in Electronic Engineering  
  Advisor: Prof. [Yong Li](http://fi.ee.tsinghua.edu.cn/~liyong/)  

* University of California, Los Angeles (2017.07-2017.09)  
  CSST summer program  
  Advisor: Prof. [Wei Wang](http://web.cs.ucla.edu/~weiwang/)  
--->



<!--- # Experience
======
* Google Core-ML (2022.06-2022.09)  
  Research Intern  
  Host: Dr. [Le Hou](https://scholar.google.com/citations?user=kQ0HeQIAAAAJ&hl=en) and Dr. [Yuexin Wu](https://scholar.google.com/citations?user=sd0nprMAAAAJ&hl=en)

* Google Research (2021.05-2021.08)  
  Research Intern  
  Host: Dr. [Tianqi Liu](https://scholar.google.com/citations?user=pUKhiMIAAAAJ&hl=en) and Dr. [Jialu Liu](https://jialu.info/)

* Microsoft Research Redmond (2020.06-2020.09)  
  Research Intern  
  Host: Dr. [Chunyuan Li](http://chunyuan.li/) and Krishan Subudhi  --->







