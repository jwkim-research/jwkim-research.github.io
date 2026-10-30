---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Research Perspective

I am interested in how operational decisions can be improved by understanding the structure of a problem: how decisions interact, which constraints matter, and how uncertainty unfolds over time. What draws me to research is the process of turning a complex problem into a model that makes its decision logic clear.

My interests lie in analytical operations management, particularly stochastic modeling and sequential decision-making. I am especially curious about settings in which a decision changes the conditions for later decisions, as in inventory management, dynamic pricing, and service operations. I would like to study how optimization, simulation, and learning can work together to support decisions in these settings.

My research so far has approached operational decision-making from three perspectives: designing optimization methods, evaluating AI-generated decisions, and examining models of human responses. These experiences have shaped a common question for me: how can we build computational models that capture the features of a problem that matter for making decisions?

## Research Interests

- **Core interests:** Analytical operations management; stochastic modeling and optimization; sequential decision-making; decision-making under uncertainty.
- **Methods I hope to explore further:** Markov decision processes; approximate dynamic programming; reinforcement learning; simulation.
- **Application interests:** Supply chains and logistics; inventory and pricing; queueing and service operations.
- **Related experience:** Mixed-integer programming; matheuristics; vehicle routing; LLM-based human response simulation.

## Research Projects

### Transportation Volume Reallocation in Automotive Supply Chains

*Working manuscript with Seokgi Lee and Yuncheol Kang*

How can deliveries be consolidated to improve truck utilization while keeping the production schedule unchanged? This problem involves interacting packing and timing decisions, with trade-offs among transportation, unused capacity, holding, and other operating costs.

I designed and implemented a two-stage matheuristic. The first stage uses a simplified MILP that minimizes the unused truck capacity penalty to obtain an initial feasible solution. The second stage applies MILP-based large neighborhood search to improve that solution under the full cost objective. In computational experiments, the framework achieved lower total costs than the full MILP solved with Gurobi on all largest tested instances under the same short time limit.

This project deepened my interest in using problem structure to guide algorithm design. It also taught me to reconsider a method when it does not address the main source of difficulty in the problem.

### Prompt-Based Vehicle Routing with Large Language Models

*Published with Daiki Min in Korean Management Science Review, 43(2), 29–47 (2026)*

This study examines whether prompting LLMs can produce useful vehicle routes for capacitated vehicle routing problems and vehicle routing problems with time windows. I developed and implemented prompting approaches and conducted experiments evaluating feasibility, objective values, and route structure.

The study made me interested in how AI-generated decisions should be evaluated against explicit operational constraints and objectives, and where learning-based tools can complement optimization.

### LLM-Based Human Response Simulation

*“Beyond Averages: Evaluating LLMs on Human Survey Replication at the Distributional Level” — working paper with J. Moon, Y. Lah, H. Jin, Y. Han, and Y. Kang*

This project investigates the capabilities and limitations of LLM-based human response simulation. I contributed to experimental execution, persona and prompt design, and the interpretation and synthesis of results.

This experience broadened my interest from choosing operational actions to understanding the responses those actions may elicit. It motivates a longer-term interest in connecting models of consumer behavior with simulation and operational decisions, including pricing and product allocation.

## Looking Ahead

I would like to develop models for operational systems in which uncertainty, evolving system states, and human responses jointly affect decisions. Building on my optimization experience, I hope to explore stochastic and dynamic models that explain not only which decisions perform well, but why they do.
