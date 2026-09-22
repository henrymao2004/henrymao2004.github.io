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

My research asks **how AI agents fail as they grow more capable—and how to keep that evolution safe.** As they start to act in the world, they also begin to coordinate with other agents, then keep memory. I study the safety surface that appears at each of those steps, with a focus on **agent safety**. Feel free to reach out if you are interested in collaboration.

Research Interests
------------------
Each new ability grows a new safety surface. My papers follow that surface in order.

- **Acting and coordinating.** I red-team agents while they are doing work. [AHA](https://arxiv.org/abs/2607.11698) turns that red-teaming into autoresearch: one agent spends the night attacking a production agent and comes back with reusable explanations of why it breaks. [TrustFork](https://github.com/henrymao2004/agent-orchestration-safety) studies subagent orchestration, where a fake identity on a worker's nametag can hijack whom the main agent trusts and allows to act. [CAVE](https://github.com/henrymao2004/agent-over-correction) studies the reply *you're right, let me fix it*: after the job is already done, a false accusation can make an agent undo a working system. [STARE](https://arxiv.org/abs/2605.00699) carries the same attack question into multimodal models, along the generation timeline.

- **Remembering and improving.** Once an agent keeps state, a failure can outlive the chat that caused it. [PASB](https://arxiv.org/abs/2607.10526) shows sycophancy writing itself into memory and bossing later conversations. [MisEvolve](https://arxiv.org/abs/2608.12851) follows one unsafe lesson as it becomes a skill the agent keeps reusing. [MemMark](https://arxiv.org/abs/2605.25002) watermarks who wrote a memory, so long-term state can be attributed.

- **Looking inside and stepping in.** I trace the circuits that decide what an agent writes into memory and what it pulls back out ([Agent Memory](https://arxiv.org/abs/2605.03354)), then turn that kind of internal evidence into tools that watch and steer activations, including chain-of-thought obfuscation in VLMs ([TAME](https://arxiv.org/abs/2609.24243)).

News
---------------
<div class="news-box">
  <ul class="news-list">
<li><span class="news-date"><em>2026.09</em></span> 🚀🚀 <a href="https://arxiv.org/abs/2609.24243" target="_blank">activation enforcement for CoT obfuscation in VLMs</a> is now on arXiv.</li>
<li><span class="news-date"><em>2026.09</em></span> 🎓🎓 I am starting my Ph.D. at the City University of Hong Kong.</li>
<li><span class="news-date"><em>2026.08</em></span> 🎉🎉 <a href="https://arxiv.org/abs/2605.25002" target="_blank">state-evolution attribution watermarking for agent long-term memory</a> was accepted to <strong>Findings of EMNLP 2026</strong>.</li>
<li><span class="news-date"><em>2026.08</em></span> 🚀🚀 <a href="https://arxiv.org/abs/2608.12851" target="_blank">skill misevolution in LLM agents</a> is now on arXiv.</li>
<li><span class="news-date"><em>2026.07</em></span> 🚀🚀 <a href="https://arxiv.org/abs/2607.11698" target="_blank">autoresearch for production-agent red-teaming</a> and <a href="https://arxiv.org/abs/2607.10526" target="_blank">persistent sycophancy in stateful personal agents</a> are now on arXiv.</li>
<li><span class="news-date"><em>2026.05</em></span> 🎉🎉 <a href="https://arxiv.org/abs/2605.00699" target="_blank">step-wise temporal red-teaming for multi-modal toxicity</a> accepted to <strong>ICML 2026</strong> (Poster).</li>
<li><span class="news-date"><em>2025.11</em></span> 🎉🎉 <a href="https://arxiv.org/abs/2505.14422" target="_blank">social-media opinion prediction</a> (Oral) and <a href="https://arxiv.org/abs/2505.18744" target="_blank">multi-domain text-to-SQL</a> (Poster) accepted to <strong>AAAI 2026</strong>.</li>
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
          <span style="color:#888;">Research: agent safety.</span>
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
      A hierarchical-RL red-team engine with step-wise temporal attribution for multi-modal toxicity attacks; it reveals how harmful content develops across generations, enabling more precise safety evaluation.
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
      <img src="images/trustfork.png" alt="TrustFork" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;"> 
    </div> 
    <div>
      <strong>Trust the Brand, Lose Control: How Identity Hijacks LLM Agent Orchestration</strong><br>
      <i style="font-size: 13px;"><strong>Xutao Mao</strong>, Rui Qian, Linghan Chen, Yudong Gao, Junchi Liao, Junlin Cai, Jinman Zhao, Cong Wang&dagger;</i><br> 
      A benchmark for identity hijack in subagent orchestration: a fake model name or tier on a worker can change whom the main agent trusts and allows to act.
      <br> 
      <b><i style="color:#83a1c7;">Preprint &nbsp;</i></b>
      <a href="https://github.com/henrymao2004/agent-orchestration-safety" target="_blank"><em>[code]</em></a> 
      <a href="https://henrymao2004.github.io/agent-orchestration-safety/" target="_blank"><em>[project]</em></a> 
      <a href="https://huggingface.co/datasets/sevens2004/trustfork" target="_blank"><em>[dataset]</em></a> 
    </div>
  </div> 
</div>

<div class="publication-card" data-category="all"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;"> 
      <img src="images/cave.png" alt="CAVE-Bench" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;"> 
    </div> 
    <div>
      <strong>You're Right, Let Me Fix It: How LLM Agents Damage Correct Work When Falsely Accused</strong><br>
      <i style="font-size: 13px;"><strong>Xutao Mao</strong>, Rui Qian, Longxiang Wang, Xinjian Yi, Mingxuan Li, Linghan Chen, Yudong Gao, Xiang Zheng&dagger;, Cong Wang&dagger;</i><br> 
      A benchmark for false blame after the work is already correct: the reply <em>you're right, let me fix it</em> can make an agent undo a working system.
      <br> 
      <b><i style="color:#83a1c7;">Preprint &nbsp;</i></b>
      <a href="https://github.com/henrymao2004/agent-over-correction" target="_blank"><em>[code]</em></a> 
      <a href="https://henrymao2004.github.io/agent-over-correction/" target="_blank"><em>[project]</em></a> 
      <a href="https://huggingface.co/datasets/sevens2004/cave_bench" target="_blank"><em>[dataset]</em></a> 
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
      An autoresearch framework that turns agent red-teaming discoveries into a reusable Vulnerability Concept Graph; it makes transferable vulnerability knowledge actionable against unseen production agents.
      <br> 
      <b><i style="color:#83a1c7;">Preprint &nbsp;</i></b>
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
      A 1,600-task benchmark tracing how sycophancy persists through stateful agent memory; it shows how unsafe agreement survives interaction boundaries and compounds into downstream failures.
      <br> 
      <b><i style="color:#83a1c7;">Preprint &nbsp;</i></b>
      <a href="https://arxiv.org/abs/2607.10526" target="_blank"><em>[arXiv]</em></a> 
      <a href="https://github.com/henrymao2004/agent-sycophancy" target="_blank"><em>[code]</em></a> 
      <a href="https://henrymao2004.github.io/agent-sycophancy/" target="_blank"><em>[project]</em></a> 
      <a href="https://huggingface.co/datasets/sevens2004/pasb" target="_blank"><em>[dataset]</em></a> 
    </div>
  </div> 
</div>

{% comment %}
Temporarily hidden from Core Publications. Remove these Liquid comment tags to restore the Taming card.
<div class="publication-card" data-category="all"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;"> 
      <img src="images/tame.png" alt="TAME" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;"> 
    </div> 
    <div>
      <strong>Taming CoT Obfuscation in VLMs: From Mechanistic Evidence to Activation-Level Enforcement</strong><br>
      <i style="font-size: 13px;"><strong>Xutao Mao</strong>, Jianing Zhu, Jinman Zhao, Tongliang Liu, Xiaowen Chu, Cong Wang&dagger;, Bo Han&dagger;</i><br> 
      A mechanistic framework that diagnoses and suppresses chain-of-thought obfuscation in RL-trained VLMs; it improves the transparency and enforceability of model reasoning.
      <br> 
      <b><i style="color:#83a1c7;">Preprint &nbsp;</i></b>
    </div>
  </div> 
</div>
{% endcomment %}

</div>


<div id="full-publications" class="publication-view" data-publication-view="list" hidden>
  <ul class="full-publication-list">
    <li>
      <span class="pub-list-badge">EMNLP 2026 Findings</span>
      <span class="pub-list-title">MemMark: State-Evolution Attribution Watermarking for Agent Long-Term Memory Systems</span><br>
      <span class="pub-list-authors">Haobo Zhang*, <strong>Xutao Mao*</strong>, Guangyuan Dong, Ziwei Li&dagger;, Xuanbo Su, Kaijie Chen, Jing Yang, Zheng Lin</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2605.25002" target="_blank">[arXiv]</a><a href="https://github.com/zhb0119/MemMark" target="_blank">[code]</a><a href="https://henrymao2004.github.io/MemMark/" target="_blank">[project]</a></span>
    </li>
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
      <span class="pub-list-badge">Preprint</span>
      <span class="pub-list-title">Agent Hacks Agent: Autoresearch for Production-Agent Red-Teaming</span><br>
      <span class="pub-list-authors"><strong>Xutao Mao</strong>, Xiang Zheng&dagger;, Cong Wang&dagger;</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2607.11698" target="_blank">[arXiv]</a><a href="https://github.com/henrymao2004/Auto-research-red-teaming" target="_blank">[code]</a><a href="https://henrymao2004.github.io/Auto-research-red-teaming/" target="_blank">[project]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">Preprint</span>
      <span class="pub-list-title">Agents Don't Just Agree, They Remember: Benchmarking Persistent Sycophancy in Stateful Personal Agents</span><br>
      <span class="pub-list-authors"><strong>Xutao Mao</strong>*, Liangjie Zhao*, Leyao Wang, Rui Qian, Qiang Huang, Wentao Wang, Bo Han&dagger;, Xiang Zheng&dagger;, Cong Wang&dagger;</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2607.10526" target="_blank">[arXiv]</a><a href="https://github.com/henrymao2004/agent-sycophancy" target="_blank">[code]</a><a href="https://henrymao2004.github.io/agent-sycophancy/" target="_blank">[project]</a><a href="https://huggingface.co/datasets/sevens2004/pasb" target="_blank">[dataset]</a></span>
    </li>
    <li id="tame-paper">
      <span class="pub-list-badge">Preprint</span>
      <span class="pub-list-title">Taming CoT Obfuscation in VLMs: From Mechanistic Evidence to Activation Enforcement</span><br>
      <span class="pub-list-authors"><strong>Xutao Mao</strong>, Jianing Zhu, Jinman Zhao, Tongliang Liu, Xiaowen Chu, Cong Wang&dagger;, Bo Han&dagger;</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2609.24243" target="_blank">[arXiv]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">Preprint</span>
      <span class="pub-list-title">What Happens Inside Agent Memory? Circuit Analysis from Emergence to Diagnosis</span><br>
      <span class="pub-list-authors"><strong>Xutao Mao</strong>, Jinman Zhao, Gerald Penn, Cong Wang&dagger;</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2605.03354" target="_blank">[arXiv]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">Preprint</span>
      <span class="pub-list-title">Practice Makes Unsafe: Skill Misevolution in Self-Improving LLM Agents</span><br>
      <span class="pub-list-authors"><strong>Xutao Mao</strong>, Liangjie Zhao, Xiang Zheng&dagger;, Cong Wang&dagger;</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2608.12851" target="_blank">[arXiv]</a><a href="https://github.com/henrymao2004/misevolve" target="_blank">[code]</a></span>
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
    <p>I'm always happy to discuss new research ideas and explore potential collaborations, especially around agent safety as agents grow more capable. If our interests overlap, feel free to reach out.</p>
  </div>
  <a class="collaboration-email" href="mailto:xutao.henry.mao@gmail.com" aria-label="Email Xutao Mao at xutao.henry.mao@gmail.com">
    <i class="fas fa-envelope" aria-hidden="true"></i>
    xutao.henry.mao@gmail.com
  </a>
</div>


<div class="map-visitors" style="margin-top: 2em; max-width: 480px;">
  <script type='text/javascript' id='mapmyvisitors' src='https://mapmyvisitors.com/map.js?cl=ffffff&w=a&t=n&d=DCa6ULHsNj3zYmDapx000MdQojF3P-iPExrQbWUOnq8&co=2d78ad&cmo=ea8d8d&cmn=1ed9e2&ct=ffffff'></script>
</div>
