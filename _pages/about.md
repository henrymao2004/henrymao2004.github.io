---
permalink: /
author_profile: true
stylesheets:
  - /assets/css/home.css
redirect_from: 
  - /about/
  - /about.html
---
<h1 class="main-heading">Hi there <img src="images/Hi.gif" width="40px"> Welcome to my Homepage!</h1>

Hi! My name is **Xutao Mao**. I am a first-year Ph.D. student at the City University of Hong Kong, advised by Prof. [Cong Wang](https://www.cs.cityu.edu.hk/~congwang/). I also closely work with Prof. [Xiang Zheng](https://x-zheng16.github.io) and Prof. [Bo Han](https://bhanml.github.io/). Before that, I received my B.S. in Computer Science and Mathematics from Vanderbilt University.

My research focuses on the principles for building **trustworthy AI** — especially the safety and alignment of agentic and multimodal language models. Feel free to reach out if you are interested in collaboration or potential opportunities.

News
---------------
<div class="news-box">
  <ul class="news-list">
<li><span class="news-date"><em>2026.09</em></span> 🎓🎓 I am starting my Ph.D. at the City University of Hong Kong.</li>
<li><span class="news-date"><em>2026.07</em></span> 🚀🚀 We released two agent-safety projects: <strong>AHA</strong> (Agent Hacks Agent) and <strong>PASB</strong> (Persistent Sycophancy Benchmark).</li>
<li><span class="news-date"><em>2026.05</em></span> 🎉🎉 Our paper <strong>STARE</strong> accepted to <strong>ICML 2026</strong> (Poster).</li>
<li><span class="news-date"><em>2025.11</em></span> 🎉🎉 Our paper <strong>MindVote</strong> and <strong>LogicCat</strong> accepted to <strong>AAAI 2026</strong> as Oral and Poster.</li>
  </ul>
</div>

Experience
--------------

<div class="experience-container">

  <div class="experience-card">
      <img src="images/cityu.png" alt="CityU logo" class="experience-logo">
      <div class="experience-info">
          <strong>City University of Hong Kong</strong><br>
          <em>2026.09 - Present</em><br>
          Ph.D. in Computer Science, advised by <a href="https://www.cs.cityu.edu.hk/~congwang/"><em>Prof. Cong Wang</em></a><br>
          <span style="color:#888;">Research: agent safety and trustworthy AI.</span>
      </div>
  </div>

  <div class="experience-card">
      <img src="images/vanderbilt.png" alt="Vanderbilt logo" class="experience-logo">
      <div class="experience-info">
          <strong>Vanderbilt University</strong><br>
          <em>2022.08 - 2026.04</em><br>
          B.S. in Computer Science &amp; Mathematics
      </div>
  </div>
</div>


Publications
--------------
<button class="pub-button active" onclick="filterPublications(event, 'all')">Core Publications</button>
<button class="pub-button" onclick="filterPublications(event, 'list')">Full Publications List</button>

(* equal contribution · &dagger; corresponding author)

<div id="core-publications" class="publication-view" data-publication-view="core">

<div class="publication-card" data-category="all"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;"> 
      <img src="images/stare.png" alt="STARE" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;"> 
    </div> 
    <div>
      <strong>STARE: Step-wise Temporal Alignment and Red-teaming Engine for Multi-modal Toxicity Attack</strong><br>
      <i style="font-size: 13px;"><strong>Xutao Mao</strong>, Liangjie Zhao, Tao Liu, Xiang Zheng&dagger;, Hongying Zan, Cong Wang&dagger;</i><br> 
      A hierarchical-RL red-team engine with step-wise temporal attribution for multi-modal toxicity attacks, exceeding baselines by ~68% attack success rate with strong transferability.
      <br> 
      <b><i style="color:#83a1c7;">ICML 2026 Poster &nbsp;</i></b> 
      <a href="https://arxiv.org/abs/2605.00699" target="_blank"><em>[arXiv]</em></a> 
      <a href="https://github.com/henrymao2004/STARE" target="_blank"><em>[code]</em></a> 
    </div>
  </div> 
</div>

<div class="publication-card" data-category="all"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;"> 
      <img src="images/mindvote.png" alt="MindVote" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;"> 
    </div> 
    <div>
      <strong>MindVote: When AI Meets the Wild West of Social Media Opinion</strong><br>
      <i style="font-size: 13px;"><strong>Xutao Mao</strong>&dagger;, Ezra Xuanru Tao, Leyao Wang</i><br> 
      A benchmark probing how large language models predict and reason about real-world social-media opinion.
      <br> 
      <b><i style="color:#83a1c7;">AAAI 2026 Oral &nbsp;</i></b> 
      <a href="https://arxiv.org/abs/2505.14422" target="_blank"><em>[arXiv]</em></a> 
      <a href="https://github.com/henrymao2004/MindVote_AAAI" target="_blank"><em>[code]</em></a> 
    </div>
  </div> 
</div>

<div class="publication-card" data-category="all"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;"> 
      <img src="images/aha.png" alt="AHA" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;"> 
    </div> 
    <div>
      <strong>Agent Hacks Agent: Autoresearch for Production-Agent Red-Teaming</strong><br>
      <i style="font-size: 13px;"><strong>Xutao Mao</strong>, Xiang Zheng&dagger;, Cong Wang&dagger;</i><br> 
      An autoresearch red-team framework that discovers reusable vulnerability concepts (a Vulnerability Concept Graph) in production LLM agents; the frozen graph, deployed single-shot on held-out data, beats the strongest baseline by 14.2 points.
      <br> 
      <b><i style="color:#83a1c7;">Preprint · Under Review &nbsp;</i></b> 
      <a href="https://arxiv.org/abs/2607.11698" target="_blank"><em>[arXiv]</em></a> 
      <a href="https://github.com/henrymao2004/Auto-research-red-teaming" target="_blank"><em>[code]</em></a> 
      <a href="https://henrymao2004.github.io/Auto-research-red-teaming/" target="_blank"><em>[project]</em></a> 
    </div>
  </div> 
</div>

<div class="publication-card" data-category="all"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;"> 
      <img src="images/pasb.png" alt="PASB" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;"> 
    </div> 
    <div>
      <strong>Agents Don't Just Agree, They Remember: Benchmarking Persistent Sycophancy in Stateful Personal Agents</strong><br>
      <i style="font-size: 13px;"><strong>Xutao Mao</strong>*, Liangjie Zhao*, Leyao Wang, Rui Qian, Qiang Huang, Wentao Wang, Bo Han&dagger;, Xiang Zheng&dagger;, Cong Wang&dagger;</i><br> 
      A 1,600-task benchmark for persistent sycophancy in stateful personal agents; crossing the commit boundary is the single largest downstream-failure jump (+27 points), driven by attribution stripping.
      <br> 
      <b><i style="color:#83a1c7;">Preprint · Under Review &nbsp;</i></b> 
      <a href="https://arxiv.org/abs/2607.10526" target="_blank"><em>[arXiv]</em></a> 
      <a href="https://github.com/henrymao2004/agent-sycophancy" target="_blank"><em>[code]</em></a> 
      <a href="https://henrymao2004.github.io/agent-sycophancy/" target="_blank"><em>[project]</em></a> 
      <a href="https://huggingface.co/datasets/sevens2004/pasb" target="_blank"><em>[dataset]</em></a> 
    </div>
  </div> 
</div>

<div class="publication-card" data-category="all"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;"> 
      <img src="images/tame.png" alt="TAME" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;"> 
    </div> 
    <div>
      <strong>Taming CoT Obfuscation in VLMs: From Mechanistic Evidence to Activation-Level Enforcement</strong><br>
      <i style="font-size: 13px;"><strong>Xutao Mao</strong>, Jianing Zhu, Jinman Zhao, Tongliang Liu, Xiaowen Chu, Cong Wang&dagger;, Bo Han&dagger;</i><br> 
      Mechanistic analysis and activation-level enforcement that tame chain-of-thought obfuscation in RL-trained VLMs, improving reasoning monitorability by ~60% over GRPO.
      <br> 
      <b><i style="color:#83a1c7;">Preprint · Under Review &nbsp;</i></b> 
    </div>
  </div> 
</div>

<div class="publication-card" data-category="all"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;"> 
      <img src="images/agentmemory.png" alt="What Happens Inside Agent Memory?" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;"> 
    </div> 
    <div>
      <strong>What Happens Inside Agent Memory? Circuit Analysis from Emergence to Diagnosis</strong><br>
      <i style="font-size: 13px;"><strong>Xutao Mao</strong>, Jinman Zhao, Gerald Penn, Cong Wang&dagger;</i><br> 
      A mechanistic circuit analysis tracing how agent-memory features emerge and specialize inside LLMs — from first-person subject anchoring to category-aggregation hubs — enabling diagnosis of memory behavior.
      <br> 
      <b><i style="color:#83a1c7;">Preprint · Under Review &nbsp;</i></b> 
      <a href="https://arxiv.org/abs/2605.03354" target="_blank"><em>[arXiv]</em></a> 
    </div>
  </div> 
</div>

</div>


<div id="full-publications" class="publication-view" data-publication-view="list" hidden>
  <ul class="full-publication-list">
    <li>
      <span class="pub-list-badge">ICML 2026 Poster</span>
      <span class="pub-list-title">STARE: Step-wise Temporal Alignment and Red-teaming Engine for Multi-modal Toxicity Attack</span><br>
      <span class="pub-list-authors"><strong>Xutao Mao</strong>, Liangjie Zhao, Tao Liu, Xiang Zheng&dagger;, Hongying Zan, Cong Wang&dagger;</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2605.00699" target="_blank">[arXiv]</a><a href="https://github.com/henrymao2004/STARE" target="_blank">[code]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">AAAI 2026 Oral</span>
      <span class="pub-list-title">MindVote: When AI Meets the Wild West of Social Media Opinion</span><br>
      <span class="pub-list-authors"><strong>Xutao Mao</strong>&dagger;, Ezra Xuanru Tao, Leyao Wang</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2505.14422" target="_blank">[arXiv]</a><a href="https://github.com/henrymao2004/MindVote_AAAI" target="_blank">[code]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">AAAI 2026 Poster</span>
      <span class="pub-list-title">LogicCat: A Text-to-SQL Benchmark for Multi-Domain Reasoning Challenges</span><br>
      <span class="pub-list-authors">Tao Liu*, <strong>Xutao Mao*</strong>, Hongying Zan&dagger;, Dixuan Zhang, Yifan Li, Haixin Liu, Lulu Kong, Jiaming Hou, Rui Li, YunLong Li, Aoze Zheng, Zhiqiang Zhang, Luo Zhewei, Kunli Zhang, Min Peng</span>
      <span style="display:block; font-size:12px; color:#9aa0a6; font-style:italic; margin-top:2px;">* equal contribution, listed in alphabetical order</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2505.18744" target="_blank">[arXiv]</a><a href="https://github.com/Ffunkytao/LogicCat" target="_blank">[code]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">Preprint &middot; Under Review</span>
      <span class="pub-list-title">Agent Hacks Agent: Autoresearch for Production-Agent Red-Teaming</span><br>
      <span class="pub-list-authors"><strong>Xutao Mao</strong>, Xiang Zheng&dagger;, Cong Wang&dagger;</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2607.11698" target="_blank">[arXiv]</a><a href="https://github.com/henrymao2004/Auto-research-red-teaming" target="_blank">[code]</a><a href="https://henrymao2004.github.io/Auto-research-red-teaming/" target="_blank">[project]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">Preprint &middot; Under Review</span>
      <span class="pub-list-title">Agents Don't Just Agree, They Remember: Benchmarking Persistent Sycophancy in Stateful Personal Agents</span><br>
      <span class="pub-list-authors"><strong>Xutao Mao</strong>*, Liangjie Zhao*, Leyao Wang, Rui Qian, Qiang Huang, Wentao Wang, Bo Han&dagger;, Xiang Zheng&dagger;, Cong Wang&dagger;</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2607.10526" target="_blank">[arXiv]</a><a href="https://github.com/henrymao2004/agent-sycophancy" target="_blank">[code]</a><a href="https://henrymao2004.github.io/agent-sycophancy/" target="_blank">[project]</a><a href="https://huggingface.co/datasets/sevens2004/pasb" target="_blank">[dataset]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">Preprint &middot; Under Review</span>
      <span class="pub-list-title">Taming CoT Obfuscation in VLMs: From Mechanistic Evidence to Activation-Level Enforcement</span><br>
      <span class="pub-list-authors"><strong>Xutao Mao</strong>, Jianing Zhu, Jinman Zhao, Tongliang Liu, Xiaowen Chu, Cong Wang&dagger;, Bo Han&dagger;</span>
      <span class="pub-list-links"></span>
    </li>
    <li>
      <span class="pub-list-badge">Preprint &middot; Under Review</span>
      <span class="pub-list-title">What Happens Inside Agent Memory? Circuit Analysis from Emergence to Diagnosis</span><br>
      <span class="pub-list-authors"><strong>Xutao Mao</strong>, Jinman Zhao, Gerald Penn, Cong Wang&dagger;</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2605.03354" target="_blank">[arXiv]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">Preprint &middot; Under Review</span>
      <span class="pub-list-title">MemMark: State-Evolution Attribution Watermarking for Agent Long-Term Memory Systems</span><br>
      <span class="pub-list-authors">Haobo Zhang*, <strong>Xutao Mao*</strong>, Guangyuan Dong, Ziwei Li&dagger;, Xuanbo Su, Kaijie Chen, Jing Yang, Zheng Lin</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2605.25002" target="_blank">[arXiv]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">Preprint</span>
      <span class="pub-list-title">Practice Makes Unsafe: Skill Misevolution in Self-Improving LLM Agents</span><br>
      <span class="pub-list-authors"><strong>Xutao Mao</strong>, Liangjie Zhao, Xiang Zheng&dagger;, Cong Wang&dagger;</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2608.12851" target="_blank">[arXiv]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">Preprint</span>
      <span class="pub-list-title">Towards Bridging Review Sparsity in Recommendation with Textual Edge Graph Representation</span><br>
      <span class="pub-list-authors">Leyao Wang*, <strong>Xutao Mao*</strong>, Xuhui Zhan, Yuying Zhao, Bo Ni, Ryan A Rossi, Nesreen K Ahmed, Tyler Derr&dagger;</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2508.01128" target="_blank">[arXiv]</a></span>
    </li>
  </ul>
</div>

<script src="assets/js/show_publications.js"></script>
<script src="assets/js/pub_media_rotator.js"></script>


Scholarships
--------
- *2026*, Hong Kong Postgraduate Scholarships (during PhD study).
- *2025*, Vanderbilt Summer Research Program Scholarship.


Services
--------
- Reviewer, AAAI 2026 / 2027 · TheWebConf 2026 · NeurIPS 2026.


Collaboration
-------------
<div class="collaboration-card">
  <div class="collaboration-copy">
    <strong>Let's discuss ideas and build something meaningful together.</strong>
    <p>I'm always happy to discuss new research ideas and explore potential collaborations, especially around trustworthy AI, agent safety, and multimodal language models. If our interests overlap, feel free to reach out.</p>
  </div>
  <a class="collaboration-email" href="mailto:xutao.henry.mao@gmail.com" aria-label="Email Xutao Mao at xutao.henry.mao@gmail.com">
    <i class="fas fa-envelope" aria-hidden="true"></i>
    xutao.henry.mao@gmail.com
  </a>
</div>


<div class="map-visitors" style="margin-top: 2em; max-width: 480px;">
  <script type='text/javascript' id='mapmyvisitors' src='https://mapmyvisitors.com/map.js?cl=ffffff&w=a&t=n&d=DCa6ULHsNj3zYmDapx000MdQojF3P-iPExrQbWUOnq8&co=2d78ad&cmo=ea8d8d&cmn=1ed9e2&ct=ffffff'></script>
</div>
