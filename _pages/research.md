---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<div class="research-page">
<p>My research interests lie in analytical operations management, particularly <strong>stochastic modeling and sequential decision-making</strong>. I am interested in how operational systems evolve over time and how decisions interact with uncertainty and changing system states.</p>

<p>My work so far has focused on <strong>combinatorial optimization</strong> and the evaluation of LLM-based decisions and human response simulation. Through these projects, I have become increasingly interested in mathematical modeling: how a problem can be represented from different perspectives, and how the choice of representation affects the decisions we can study.</p>

<nav class="research-quick-links" aria-label="Research projects">
 <a href="#transportation">Transportation reallocation</a>
 <a href="#human-responses">Synthetic persona simulation</a>
 <a href="#routing">LLM vehicle routing</a>
</nav>
<h2>Research Interests</h2>
<div class="research-grid research-focus-grid">
  <section class="research-panel">
    <h3>Research Focus</h3>
    <ul><li>Sequential decision-making</li><li>Combinatorial optimization</li><li>Decision-making under uncertainty</li></ul>
  </section>
  <section class="research-panel">
    <h3>Methodological Interests</h3>
    <ul><li>Stochastic modeling</li><li>MDPs and dynamic programming</li><li>Optimization, simulation, and reinforcement learning</li></ul>
  </section>
  <section class="research-panel">
    <h3>Application Areas</h3>
    <ul><li>Supply chains and logistics</li><li>Inventory and pricing</li><li>Retail and service operations</li></ul>
  </section>
</div>

<h2>Current Research</h2>

<article id="transportation" class="research-project research-primary">
  <h3>Transportation Volume Reallocation in Automotive Supply Chains</h3>
  <p class="research-meta">Research in progress with Seokgi Lee and Yuncheol Kang</p>
  <ul class="research-record">
    <li><strong>Principal Investigator:</strong> NRF Master’s Student Research Fellowship, Sep 2026–Aug 2027</li>
    <li><strong>Scheduled presentation:</strong> INFORMS Annual Meeting, November 4, 2026, San Francisco</li>
  </ul>
  <ul class="research-highlights" aria-label="Project highlights">
    <li><strong>Problem:</strong> Consolidate deliveries without changing the production schedule.</li>
    <li><strong>Approach:</strong> Simplified MILP initialization followed by MILP-based LNS.</li>
    <li><strong>Result:</strong> Lower costs than the full MILP on all largest tested instances under the same short time limit.</li>
  </ul>
  <p class="research-short-perspective">Exploring an <strong>MDP formulation</strong> of this problem strengthened my interest in mathematical modeling and sequential decision-making, even though the final method uses MILP-based LNS.</p>
  <details class="research-expanded"><summary>Contribution, findings, and research perspective</summary>
  <dl>
    <dt>Problem</dt><dd>This project studies how deliveries can be consolidated to improve truck utilization while keeping the production schedule unchanged. Packing and timing decisions interact through transportation, unused capacity, holding, and other operating costs.</dd>
    <dt>My Contribution</dt><dd>I designed and implemented a two-stage matheuristic. A simplified MILP minimizes the unused truck capacity penalty to generate an initial feasible solution; MILP-based large neighborhood search then improves that solution under the full cost objective. I also designed and conducted the computational experiments.</dd>
    <dt>Findings</dt><dd>The framework achieved lower total costs than the full MILP solved with Gurobi on all largest tested instances under the same short time limit.</dd>
  </dl>
  <div class="research-reflection">
    <h4>Research Perspective</h4>
    <p>One of the most intellectually engaging parts of this project was exploring an MDP formulation of the original optimization problem. Representing the problem through states, actions, and transitions led me to think more carefully about how decisions affect subsequent choices. Although the final solution method uses MILP-based LNS, this experience strengthened my interest in mathematical modeling and sequential decision-making. It also taught me to choose a method according to the structure of the problem rather than remain committed to an initial approach.</p>
  </div>
  </details>
</article>

<article id="human-responses" class="research-project research-secondary">
  <h3>LLM-Based Synthetic Persona Simulation</h3>
  <p class="research-meta">Ongoing research project · AI Applications Lab (AAPL)</p>
  <p>This project develops an <strong>LLM-based simulator using synthetic personas</strong> to model human responses and behavior. My contributions include persona and prompt design, experimental execution, and the interpretation and synthesis of results.</p>
  <p class="research-takeaway">The project connects my experience in behavioral simulation with my longer-term interest in operational decision-making.</p>
  <h4>Working Paper from This Project</h4>
  <p class="research-paper-title">“Beyond Averages: Evaluating LLMs on Human Survey Replication at the Distributional Level”</p>
  <p class="research-meta">With J. Moon, Y. Lah, H. Jin, Y. Han, and Y. Kang</p>
  <p class="jw-paper-links"><a href="https://arxiv.org/abs/2606.09013" target="_blank" rel="noopener">arXiv</a></p>
  <p class="research-takeaway"><strong>An initial study evaluates whether simulated survey responses reproduce human response distributions beyond average-level agreement.</strong></p>
  <details class="research-expanded"><summary>Study and my contribution</summary>
  <p>This working paper evaluates one application of the broader simulator project: replicating human survey response distributions. I contributed to experimental execution, persona and prompt design, and the interpretation and synthesis of results across experimental conditions.</p>
  <p>This experience broadened my interest from selecting operational actions to modeling the human responses those actions may elicit.</p>
  </details>
</article>

<h2>Published Research</h2>

<article id="routing" class="research-project research-secondary">
  <h3>Prompt-Based Vehicle Routing with Large Language Models</h3>
  <p class="research-meta">With Daiki Min · Korean Management Science Review, 43(2), 29–47 (2026)</p>
  <p class="jw-paper-links"><a href="https://doi.org/10.7737/KMSR.2026.43.2.029" target="_blank" rel="noopener">Journal article / DOI</a></p>
  <p class="research-takeaway"><strong>Evaluating AI-generated routes against operational constraints.</strong></p>
  <details class="research-expanded"><summary>Study and my contribution</summary>
  <p>This study evaluates whether prompting LLMs can produce useful solutions for capacitated vehicle routing problems and vehicle routing problems with time windows. I developed and implemented prompting approaches and conducted experiments assessing feasibility, objective values, and route structure.</p>
  <p>The project shaped my interest in assessing AI-generated decisions against explicit operational constraints and objectives, and in understanding where these tools can complement optimization.</p>
  </details>
</article>



<h2>Future Research Interests</h2>
<p>I would like to study operational systems in which decisions affect future system states and must adapt to uncertain demand and changing conditions. Building on my experience in optimization and human response simulation, I hope to explore these problems through stochastic modeling, Markov decision processes, and simulation-based approaches.</p>
<p>I am particularly interested in <strong>inventory management, dynamic pricing, and retail operations.</strong> More broadly, I hope to understand how the structure of a system shapes effective decision policies, as well as which policies perform well.</p>
</div>
