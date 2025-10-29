---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


Below you can find a summary of my career path.

Education
======
* **MSc. in Data Science and Engineering**, *EURECOM*, 2020 - 2022 (GPA: 17/20)
* **MSc. in Data Science and Engineering**, *Polytechnic University of Turin*, 2019 - 2022 (GPA: 110 cum laude/110)
* **BSc. in Computer Engineering**, *Polytechnic University of Turin*, 2016 - 2019 (GPA: 108/110)

Work experience
======

* **Fellow**, Jan 2023 – Present, *CERN, Geneva, Switzerland*
  * Main developer and Task 6.5 lead ([interTwin](https://www.intertwin.eu/)): architected and delivered **[itwinai](https://github.com/interTwin-eu/itwinai)**, an abstraction layer for distributed AI on HPC that combines data‑parallel training with scalable hyper‑parameter optimization while reducing engineering overheads for scientists.
  * Validated itwinai on European HPC by integrating **four physics** digital‑twin use cases (e.g., MLPF) and **three Earth‑observation** use cases; optimized code scalability and throughput.
  * Digital‑twin engineering at CERN openlab: coordinated two projects — **LHC infrastructure digital twin** with NVIDIA Omniverse and a **CMS ECAL DQM digital twin** with Imperial College London — and led technical discussions with NVIDIA, Google, and Imperial.
  * **Cloud‑HPC integration:** enabled large‑scale AI with the Ray Kubernetes Operator via **[interLink](https://github.com/interlink-hq/interLink)**; built cross‑infrastructure container CI/CD with **Dagger**; presented results at **KubeCon + CloudNativeCon EU 2025**.
  * **Benchmarking & energy:** measured performance and **energy consumption** of AI workloads for scientific digital twins on **LUMI (AMD MI250X)**, **Deucalion (Arm A64FX)**, **Jülich (NVIDIA A100/V100)**, and **Vega (NVIDIA A100)**; built Grafana dashboards for Prometheus telemetry.
  * EC‑funded projects: **interTwin (2023–2025)**, **ODISSEE (2025–present)** — gathered use‑case requirements; assessed digital‑twin frameworks for data‑centre operations (e.g., **ExaDigiT**); evaluated **Energy Aware Runtime (EAR)**; liaised with partners (SURF, LHCb, NextSilicon, SiPearl).
  * Community: organized a **Birds‑of‑a‑Feather** on scientific digital twins at **ISC 2025** (speakers from NVIDIA, SURF, CINES, ECMWF, CERN); presented work at **ISC 2024**, **CHEP 2024**, and **PASC 2025**.
  * Mentoring & recruiting: supervised **4 summer students** and **3 technical students**; supported hiring of new fellows.

* **Cyber‑security Data Scientist**, Jun 2022 – Dec 2022, *Huawei, Munich, Germany*
  * Co‑designed and co‑developed an **LLM‑based malware‑analysis** framework; scaled AI workloads on **Huawei Cloud**; authored periodic technical progress reports; applied **graph ML** and **NLP** methods.

* **Research Intern**, Sep 2021 – Feb 2022, *Huawei, Munich, Germany*
  * Built a **reinforcement learning** proof‑of‑concept to automate reverse engineering of evasive malware, improving dynamic‑analysis efficiency and accuracy. (Thesis available on request.)

* **Big Data Analyst Intern**, Mar 2019 – Jun 2019, *Technology Reply, Turin, Italy*
  * Extracted unstructured information from bank transfers with **Spark**; engineered NLP pipelines (document embeddings, clustering, semi‑supervised class discovery); delivered ML models for transaction classification and an **OWL ontology** for semantic queries.

Research projects
======

* **Digital twins at CERN openlab** (2023 – present)
  * **LHC infrastructure DT** with **NVIDIA Omniverse** for interactive 3D visualization and operations context.
  * **CMS ECAL DQM DT** with Imperial College London: AI‑assisted data‑quality monitoring and visualization.
  * **Cloud–HPC DT workflows** with **interLink** + Ray on Kubernetes; cross‑site CI/CD with **Dagger**.

* **itwinai (interTwin Task 6.5)** (2023 – present)
  * Open‑source framework to **scale AI workflows on HPC** (PyTorch/TensorFlow, DDP/Horovod/DeepSpeed, Ray Tune) with provenance and experiment management; validated on **physics** and **Earth‑observation** digital‑twin use cases.

* **Energy & performance benchmarking of DT AI workloads** (2023 – 2025)
  * Comparative measurements across **LUMI**, **Deucalion**, **Jülich**, **Vega**; telemetry via **Prometheus/Grafana**; analysis focused on throughput, scaling efficiency, and **energy consumption**.

Skills
======

* **Machine learning & deep learning**
  * Classification, regression, clustering; supervised/unsupervised/self‑supervised/semi‑supervised
  * NLP, CV, generative modeling, graph ML, RL
  * **PyTorch**, **TensorFlow**; scaling with **DDP**, **Horovod**, **DeepSpeed**; **Ray Tune** for HPO

* **HPC & Cloud for AI**
  * **SLURM**, **Kubernetes**; **Ray** on K8s; **interLink** for cloud–HPC workflows
  * **Containers & CI/CD:** Docker, Singularity/Apptainer, **Dagger**, GitHub Actions
  * **Observability & energy:** **Prometheus**, **Kepler**, **Grafana**; PUE/energy analysis

* **Digital twin tooling**
  * **NVIDIA Omniverse** for 3D/interactive visualization; **ExaDigiT** for DC modeling; Grafana dashboards

* **Programming & software engineering**
  * Python, Go, C++, Bash; Git; Agile/iterative delivery; Unix/Linux

* **Data management**
  * ETL pipelines; Hadoop/Spark; SQL/NoSQL


Selected talks & publications
======

* **Bunino M. et al.** *itwinai: Enabling Scalable AI Workflows on HPC for Digital Twins in Science*, **EPJ Conf., 2025**. DOI: [10.1051/epjconf/202533701361](https://doi.org/10.1051/epjconf/202533701361)
* **[Testing AI Containers for Digital Twins in Science: a Cloud‑HPC Workflow](https://kccnceu2025.sched.com/event/1tx7o/testing-ai-containers-for-digital-twins-in-science-a-cloud-hpc-workflow-matteo-bunino-cern-diego-ciangottini-infn)**, **KubeCon EU 2025** (talk)
* **BoF organiser & speaker** — *[Shaping the Future of Scientific Digital Twins](https://app.swapcard.com/event/isc-high-performance-2025/planning/UGxhbm5pbmdfMjU4NjExMw==)* (NVIDIA, SURF, CINES, ECMWF, CERN), **ISC 2025**
* **BoF speaker** — *[Synergistically Integrating HPC and Cloud](https://app.swapcard.com/event/isc-high-performance-2024/planning/UGxhbm5pbmdfMTgyNjc5Nw==)*, **ISC 2024**



Downloads
======
Download my CV <a href="../files/CV.pdf" target="_blank">here</a>!
