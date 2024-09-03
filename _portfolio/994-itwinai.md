---
title: "itwinai - AI on cloud and HPC made simple for science"
excerpt: "itwinai is a python toolkit developed in the [interTwin project](https://intertwin.eu) to support large-scale Digital Twin applications in science."
collection: portfolio
---

Check itwinai's <a href="https://github.com/interTwin-eu/itwinai" target="_blank">repository</a> for more details! 

The interTwin project, funded by the European Commission, is at the forefront of leveraging 'Digital Twins' across various scientific domains, with a particular emphasis on earth observation and physics. This initiative encompasses core modules designed to address the intricacies of data-driven and compute-intensive applications. From real-time data acquisition, software quality and Artificial Intelligence (AI), interTwin aims to facilitate seamless communication and interoperability across High Performance Computing (HPC), High Throughput Computing (HTC), and cloud resources for the benefit of physics and earth observation research.

One of the core components of interTwin is [itwinai](https://github.com/interTwin-eu/itwinai) - the AI workflow and method lifecycle module. This module is a pivotal contribution within the interTwin project and plays a role in advancing interdisciplinary scientific research through the synthesis of learning and computing paradigms.

The itwinai module, a comprehensive solution for AI workflow and method lifecycle developed collaboratively by CERN and the Julich Supercomputing Center (JSC), serves as the linchpin for researchers, data scientists, and software engineers engaged in developing, training, and maintaining AI-based methods for scientific applications. This framework stands as a testament to the commitment of the interTwin project towards co-designing and implementing an interdisciplinary Digital Twin Engine. Its main functionalities and contributions are:

### Distributed Training

itwinai offers a streamlined approach to distributing existing code across multiple GPUs and nodes, automating the training workflow. Leveraging industry-standard backends, including PyTorch Distributed Data Parallel (DDP), TensorFlow distributed strategies, and Horovod, it provides researchers with a robust foundation for efficient and scalable distributed training. The successful deployment and testing of itwinai on JSC's HDFML cluster underscore its practical applicability in real-world scenarios.

### Hyperparameter Optimization

One of the core functionalities of itwinai is its hyperparameter optimization, which plays a crucial role in enhancing model accuracy. By intelligently exploring hyperparameter spaces, itwinai eliminates the need for manual parameter tuning. The functionality, empowered by RayTune, contributes significantly to the development of more robust and accurate scientific models.

### Model Registry

A key aspect of itwinai is its provision of a robust model registry. This feature allows researchers to log and store models along with associated performance metrics, thereby enabling comprehensive analyses in a convenient manner. The backend, leveraging MLFlow, ensures seamless model management, enhancing collaboration and reproducibility.
