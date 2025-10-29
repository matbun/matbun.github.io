---
title: "Enabling Lattice QCD Normalizing Flows in HPC Infrastructures"
collection: talks
type: "Poster"
permalink: /talks/2025-06-16-pasc-normflow
venue: "PASC"
date: 2025-06-16
location: "Brugg, Switzerland"
---

This poster was presented at [PASC25](https://pasc25.pasc-conference.org/) conference and summarized our
integration work with [itwinai](https://github.com/interTwin-eu/itwinai/) and a physics use case applying
generative AI methods (normalizing flows) to lattice quantum chromodynamics (QCD).

The original abstract:

> The Horizon Europe project interTwin aims at developing a prototype for a multidisciplinary Digital Twin Engine, applicable across a whole spectrum of scientific disciplines: High Energy Physics (HEP), Environment, Climate, etc. As part of this effort we explore the extent to which Machine Learning (ML) methods can speed up Lattice Gauge Theory Simulations in challenging areas of the parameter space where Monte Carlo methods suffer from severe critical slowing down. The overall goal is progressing towards designing the digital twin of a HEP detector, where Lattice QCD simulations could provide future realistic simulations of the Standard model. We are exploiting the advantages of the tools developed in the project interTwin, notably intertwinai, to scale up and support the deployment of our simulations in HPC systems, while enabling as well several code features. The itwinai toolkit provides functionalities for distributed machine learning on HPC, supporting different distributed frameworks (DeepSpeed, Horovod, and PyTorch DistributedDataParallel) implementing different communication protocols across different GPUs, suited to different infrastructures. Furthermore, itwinai also offers a profiling feature based on the PyTorch profiling backend, enabling it to identify communication and computation shares. This profiler will enable the identification of bottlenecks, and hence optimize the code to improve performance.

Find the poster [here](https://pasc25.pasc-conference.org/presentation/?id=pos110&sess=sess149).

![pasc-normflow](https://github.com/user-attachments/assets/d58ef731-a925-47b2-af1a-395fe562eb95)
