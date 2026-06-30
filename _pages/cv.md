---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

A PDF version of my full academic CV is available [here](/files/cv.pdf).

Education
======
* **Ph.D. in Machine Learning and Optimization**, Technical University of Denmark, 2021–2024
  * Thesis: *Prediction and Learning-based Control for Autonomous Mobility*
  * Advisors: Prof. Filipe Rodrigues, Prof. Francisco C. Pereira (DTU), Dr. Daniele Gammelli (Stanford)
* **M.Sc. Electrical Power Engineering and Operations Research**, RWTH Aachen University, 2018–2021
  * Grade 1.1, Honors (Springorum Commemorative Coin), Top 5% (Dean's List)
* **Semester abroad**, KTH Royal Institute of Technology, Stockholm, 2018
* **B.Sc. Electrical Power Engineering and Business Administration**, RWTH Aachen University, 2014–2018
  * Grade 1.8, Top 5% (Dean's List), RWTH Education Fund scholarship

Research Experience
======
* **Postdoctoral Researcher**, Technical University of Munich, Oct 2025 – Present
  * Professorship for Business Analytics & Intelligent Systems (Prof. Maximilian Schiffer)
  * Developing a fast-and-slow planning architecture for control, in joint work with Stanford Autonomous Systems Lab; leading the research direction as senior author.
  * Leading first-author project on offline reinforcement learning for combinatorial action spaces.
  * Delivered a structured RL solution for SAP, integrating learned policies with combinatorial optimization for feasible decisions at scale; led a two-person team.
  * Mentor Ph.D. and graduate researchers (10+ M.Sc. and 3 Ph.D. students supervised to date); co-lecture ML and RL courses.

* **Postdoctoral Researcher**, Technical University of Denmark, Feb 2025 – Jul 2025
  * Machine Learning for Smart Mobility Lab (Prof. Francisco C. Pereira)
  * Led end-to-end development of the RL training and evaluation infrastructure for a large-scale climate-adaptation project; the pipeline supported a case study presented to the Danish Parliament.

* **Visiting Researcher**, Stanford University, Oct 2023 – Apr 2024
  * Autonomous Systems Lab (Prof. Marco Pavone)
  * Developed OHIO, an offline RL framework for learning hierarchical, structured policies from logged data, with applications in robotic manipulation, goal-conditioned control, and network optimization.
  * Designed a learning-based robo-taxi fleet controller that outperforms classical optimization and end-to-end learning at city-scale in high-fidelity simulation.

* **Ph.D. Researcher**, Technical University of Denmark, Dec 2021 – Dec 2024
  * Built learning-based control frameworks for dynamic rebalancing and pricing of autonomous fleets across single-operator, multi-operator, and regulated-market settings.
  * Designed and deployed a cloud-based arrival-time prediction API for autonomous shuttles in live pilots within the EU Horizon 2020 SHOW consortium.

* **Research Intern**, FkA GmbH Aachen, May 2021 – Aug 2021
  * Automated Driving – Artificial Intelligence Team. Semi-supervised video object tracking and segmentation of road users from an aerial perspective for the safety validation of highly automated vehicles.

Technical Skills
======
* **Machine Learning**: Offline, hierarchical, structured & multi-agent RL; imitation learning; neural combinatorial optimization; NN architectures; time series forecasting; computer vision (object tracking & segmentation); robustness & OOD evaluation
* **Optimization & Control**: Model predictive control, operations research, constrained and combinatorial optimization
* **Software**: Python, PyTorch (Lightning), Ray/RLlib, Gurobi, CPLEX, JAX, Docker, GCP, FastAPI, Hydra, DVC, Git, custom-built simulation & synthetic environments

Honors and Grants
======
* **2025** — Independent Research Fund Denmark, *Control without Chaos: Safe Offline AI for Critical Infrastructure Networks* (collaborative funding proposal, under review)
* **2025** — Otto Mønsted Research Fond, Denmark — Mobility Grant for Conference Participation
* **2023** — Knud Højgaards Fond, Denmark — Mobility Grant for external research stay at Stanford
* **2023** — Otto Mønsted Research Fond, Denmark — Mobility Grant for external research stay at Stanford
* **2023** — Reinholdt W. Jorck og Hustrus Fond, Denmark — Mobility Grant for external research stay at Stanford
* **2018, 2021** — Dean's List, RWTH Aachen University (Top 5%)
* **2016, 2019** — RWTH Education Fund Scholarship

Research Co-supervision
======
* **Ph.D. students at TUM**: Georgina Nouli, Leonard Pleiss, Baptiste Vert (2025–)
* **M.Sc. theses (TUM)**: Korbinian Kügler, Justus Schneider (2026)
* **M.Sc. theses (DTU)**: Emil Kragh Toft (2025–2026), Melis Cemre Akyol (2025), Thomas Adamopoulos, Joachim Pors Andreasen, Frederik Møller Sørensen, Asger Sturis Tang (2023–2024)
* **M.Sc. thesis (EPFL)**: Xinling Li (now Ph.D. student at MIT)

Funded Projects
======
* **2025–** *AgiMo* — DFG Sonderforschungsbereich, Data-Driven Agile Planning for Responsible Mobility. Nominated by TUM to assume the role of Principal Investigator from Prof. Schiffer in September 2026.
* **2025–** *SAP* — Industrial project: Structured Reinforcement Learning for Supply Chain Optimization. Responsible for coordination, solution design, and implementation.
* **2025–** *MA'AT* — Maximizing Well-being with AI under Deep Climate Turmoil. Led RL infrastructure development.
* **2021–2024** *SHOW* — EU Horizon 2020, Shared Automation Operating Models for Worldwide Adoption.

Organized Workshops
======
* **ITSC 2024** — *Tutorial on Data-driven Methods for Network-level Coordination of Autonomous Mobility-on-Demand Systems Across Scales*. Co-organized with D. Gammelli (Stanford), G. Zardini (MIT), J. Harrison (Google DeepMind), L. Tresca (Politecnico di Torino), X. Li (MIT), M. Schiffer (TUM), F. Rodrigues (DTU), M. Pavone (Stanford).

Review Activities
======
*Transportation Research Part C; EURO Journal on Transportation and Logistics; IISE Transactions; Transportation Research Board Annual Meeting; IEEE International Conference on Intelligent Transportation Systems (ITSC); Conference on Neural Information Processing Systems (NeurIPS); Learning and Intelligent Optimization Conference (LION).*

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
