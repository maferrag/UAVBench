# UAVBench: An Open Benchmark Dataset for Autonomous and Agentic AI UAV Systems via LLM-Generated Flight Scenarios

## Overview
**UAVBench** is an open, physically grounded benchmark dataset for evaluating **autonomous aerial systems** enhanced by **Large Language Models (LLMs)**.  
It provides a unified framework for generating, validating, and reasoning over UAV flight scenarios, enabling systematic assessment of **agentic AI reasoning** in mission planning, perception, and decision-making.

UAVBench introduces:
- **50,000 validated UAV flight scenarios**, generated using taxonomy-guided LLM prompting and multi-stage safety validation.  
- **UAVBench_MCQ**, a reasoning-oriented extension containing **50,000 multiple-choice questions (MCQs)** across ten reasoning styles—from aerodynamics and navigation to ethics and hybrid cognition.

Together, these datasets establish a **reproducible, interpretable, and physics-grounded foundation** for benchmarking cognitive and ethical reasoning in UAV autonomy.

---

## Motivation
Modern UAVs increasingly depend on **LLMs** for autonomous decision-making, yet the field lacks **standardized and physically consistent benchmarks** to measure reasoning quality.  
Most existing UAV datasets are limited by simplified environments, low-fidelity simulators, or narrow task scopes that overlook real-world physics and safety constraints.

**UAVBench** addresses this gap by:
- Capturing realistic 3D flight dynamics, environmental variability, and mission-level goals.
- Enforcing **schema compliance**, **physical feasibility**, and **risk labeling** across all generated scenarios.
- Enabling structured reasoning tasks to evaluate **LLM-based UAV cognition** in real-world operational contexts.

---

## Key Features

### 🧩 1. Unified UAV Scenario Schema
A mathematically defined schema encodes each UAV mission as a structured tuple, integrating:
- Simulation dynamics  
- Vehicle configuration  
- Environmental conditions  
- Mission objectives and safety constraints  

This ensures **interoperability**, **physical validity**, and **semantic diversity** across applications.

### 🌦️ 2. Taxonomy-Guided Scenario Generation
Using taxonomy-driven LLM prompting, UAVBench samples from a factorized space of:
- Mission types  
- Airspace configurations  
- Weather conditions  
- UAV designs and payloads  

This yields **50,000 validated, safety-aware flight scenarios** suitable for both model training and evaluation.

### ⚙️ 3. Multi-Stage Validation and Risk Labeling
Each scenario undergoes:
- Schema validation  
- Physical and geometric consistency checks  
- Safety and hazard-aware risk scoring  

Scenarios are labeled with **quantitative risk levels** and categorical tags such as:
`Weather`, `Navigation`, `Energy`, and `Collision-Avoidance`.

### 🧠 4. UAVBench_MCQ: Structured Reasoning Benchmark
The UAVBench_MCQ extension transforms validated scenarios into **50,000 reasoning tasks**, covering ten UAV reasoning domains:
1. Aerodynamics & Physics  
2. Navigation & Path Planning  
3. Policy & Compliance  
4. Environmental Sensing  
5. Multi-Agent Coordination  
6. Cyber-Physical Security  
7. Energy Management  
8. Ethical Decision-Making  
9. Comparative Systems  
10. Hybrid Integrated Reasoning  

Each MCQ is machine-readable, logically consistent, and aligned with real-world UAV operations.

### 🤖 5. Large-Scale LLM Evaluation
UAVBench evaluates **32 state-of-the-art LLMs**, including:
- GPT-5, ChatGPT-4o, Gemini-2.5-Flash  
- DeepSeek-V3, Qwen3-235B, ERNIE-4.5-300B  

Results reveal strong perception and policy reasoning but ongoing challenges in **ethics-aware** and **resource-constrained** decision-making.

---

## Research Questions
UAVBench is designed to answer key questions in autonomous aerial reasoning:
- How can LLM-generated UAV scenarios remain physically consistent and safety-aware?  
- What methods ensure interpretable and risk-labeled UAV missions?  
- How can reasoning tasks evaluate ethical and cognitive dimensions of UAV autonomy?  
- How do model architectures influence grounded reasoning and decision reliability?

---

<h2 align="center">📖 Citation</h2>

If you use <b>AgentDrive</b> or any of its benchmark datasets in your research, please cite it as:

```bibtex
@misc{Ferrag2025UAVBench,
  title = {UAVBench: An Open Benchmark Dataset for Autonomous and Agentic AI UAV Systems via LLM-Generated Flight Scenarios},
  author = {Mohamed Amine Ferrag, Abderrahmane Lakas, Merouane Debbah},
  howpublished = {GitHub repository},
  year = {2025},
  note = {Available at: \url{https://github.com/maferrag/UAVBench}},
  url = {https://github.com/maferrag/UAVBench}
}
```


<h2 align="center">📫 Contact</h2>

<p align="center">
  <b>Dr. Mohamed Amine Ferrag</b><br>

  <a href="mailto:mohamed.amine.ferrag@gmail.com">mohamed.amine.ferrag@gmail.com</a><br><br>

  🌐 <a href="https://scholar.google.fr/citations?user=IkPeqxMAAAAJ&hl=fr&oi=ao">Google Scholar</a> |
  🔗 <a href="https://www.scopus.com/authid/detail.uri?authorId=56115001200">Scopus</a> |
  🧭 <a href="https://www.webofscience.com/wos/author/rid/M-2909-2016">Web of Science</a> |
  💼 <a href="https://www.linkedin.com/in/mohamed-amine-ferrag-phd-36390243/">LinkedIn</a>
</p>


