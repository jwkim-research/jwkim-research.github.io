---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<div class="research-overview">
  <h2>Understanding operational problems.<br>Building better decision models.</h2>
  <p>I am interested in how decisions interact, which constraints matter, and how uncertainty unfolds over time. What draws me to research is turning a complex operational problem into a model that makes its decision logic clear.</p>
  <p><strong>My guiding question:</strong> How can we build computational models that capture the features of a problem that matter for making decisions?</p>
</div>

<h2>Research Interests</h2>
<p>My interests lie in <strong>analytical operations management</strong>, particularly settings in which a decision changes the conditions for later decisions. I would like to study how optimization, simulation, and learning can work together in these settings.</p>

<div class="research-grid">
  <section class="research-panel">
    <h3>Core Questions</h3>
    <ul><li>Sequential decision-making</li><li>Stochastic modeling and optimization</li><li>Decision-making under uncertainty</li></ul>
  </section>
  <section class="research-panel">
    <h3>Methods to Explore</h3>
    <ul><li>Markov decision processes</li><li>Approximate dynamic programming</li><li>Reinforcement learning and simulation</li></ul>
  </section>
  <section class="research-panel">
    <h3>Application Interests</h3>
    <ul><li>Supply chains and logistics</li><li>Inventory and dynamic pricing</li><li>Queueing and service operations</li></ul>
  </section>
  <section class="research-panel">
    <h3>Research Experience</h3>
    <ul><li>Mixed-integer programming and matheuristics</li><li>Vehicle routing and AI-generated decisions</li><li>LLM-based human response simulation</li></ul>
  </section>
</div>

<h2>How My Projects Connect</h2>
<p>My work has approached operational decision-making from three complementary perspectives.</p>
<div class="research-path">
  <div><strong>Designing Decisions</strong><span>Use problem structure to develop optimization methods.</span></div>
  <div><strong>Evaluating Decisions</strong><span>Assess AI-generated solutions against constraints and objectives.</span></div>
  <div><strong>Modeling Responses</strong><span>Understand the human responses that operational actions may elicit.</span></div>
</div>

<h2>Research Projects</h2>

<article class="research-project">
  <h3>Transportation Volume Reallocation in Automotive Supply Chains</h3>
  <p class="research-meta">Working manuscript · With Seokgi Lee and Yuncheol Kang</p>
  <dl>
    <dt>Question</dt><dd>How can deliveries be consolidated to improve truck utilization while keeping the production schedule unchanged?</dd>
    <dt>My Contribution</dt><dd>I designed and implemented a two-stage matheuristic: simplified MILP initialization followed by MILP-based large neighborhood search under the full cost objective.</dd>
    <dt>Key Finding</dt><dd>The framework achieved lower total costs than the full MILP solved with Gurobi on all largest tested instances under the same short time limit.</dd>
    <dt>Connection</dt><dd>This project deepened my interest in using problem structure to guide algorithm design, and in reconsidering a method when it does not address the main source of difficulty.</dd>
  </dl>
  <details><summary>Model and approach</summary><p>The problem couples packing and timing decisions, with trade-offs among transportation, unused capacity, holding, and other operating costs. The first stage minimizes the unused truck capacity penalty to obtain an initial feasible solution. The second stage improves that solution using the full cost objective.</p></details>
</article>

<article class="research-project">
  <h3>Prompt-Based Vehicle Routing with Large Language Models</h3>
  <p class="research-meta">Published · With Daiki Min · Korean Management Science Review, 43(2), 29–47 (2026)</p>
  <dl>
    <dt>Question</dt><dd>Can prompting LLMs produce useful routes for vehicle routing problems with capacity and time-window constraints?</dd>
    <dt>My Contribution</dt><dd>I developed and implemented prompting approaches and conducted experiments evaluating feasibility, objective values, and route structure.</dd>
    <dt>Connection</dt><dd>This study shaped my interest in evaluating AI-generated decisions against explicit operational constraints and objectives, and in identifying where learning-based tools can complement optimization.</dd>
  </dl>
</article>

<article class="research-project">
  <h3>LLM-Based Human Response Simulation</h3>
  <p class="research-meta">Working paper · With J. Moon, Y. Lah, H. Jin, Y. Han, and Y. Kang</p>
  <dl>
    <dt>Question</dt><dd>What are the capabilities and limitations of LLM-based human response simulation?</dd>
    <dt>My Contribution</dt><dd>I contributed to experimental execution, persona and prompt design, and the interpretation and synthesis of results.</dd>
    <dt>Connection</dt><dd>This experience broadened my interest from choosing operational actions to understanding the responses those actions may elicit. It motivates my longer-term interest in connecting consumer behavior models with simulation, pricing, and product allocation.</dd>
  </dl>
  <details><summary>Working paper</summary><p>“Beyond Averages: Evaluating LLMs on Human Survey Replication at the Distributional Level.”</p></details>
</article>

<h2>Looking Ahead</h2>
<p>I would like to develop models for operational systems in which <strong>uncertainty, evolving system states, and human responses</strong> jointly affect decisions. Building on my optimization experience, I hope to explore stochastic and dynamic models that explain not only which decisions perform well, but why they do.</p>
