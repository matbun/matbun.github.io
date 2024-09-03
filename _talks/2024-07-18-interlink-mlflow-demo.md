---
title: "MLFlow while running on a SuperComputer with Matteo Bunino from CERN"
collection: talks
type: "Live stream"
permalink: /talks/2024-07-18-interlink-mlflow-demo
venue: "Online"
date: 2024-07-18
location: "Geneva, Switzerland"
---

This live stream was organized by Diego Ciangottini (INFN) and showcased a demo on
how to to employ [interLink](https://github.com/interTwin-eu/interLink), a software component
developed in the [interTwin](https://www.intertwin.eu/) project, meant to enable cloud-HPC
integration. Matteo showed how interLink can be used to offload to remote HPC resources
compute-intensive AI workflows used in scientific applications, with a particular focus on
maintaining consistent ML metadata across different computing infrastructures using MLFlow.

Being able to submit a compute-intensive job to a remote HPC system is not sufficient for AI
jobs, as we are interested in "bringing" back the results produced when runnin on remote infrastructure,
namely ML metadata. Such results include ML metric timeseries (e.g, loss, accuracy), model checkpoints,
and other artifacts (e.g., data samples in case of generative AI).
In this live stream Matteo shows how ML metadata can be seamlessly relayed back to cloud by deploying
a central MLFlow tracking server on cloud, reachable from anywhere.

<iframe width="560" height="315" src="https://www.youtube.com/embed/UcqiW69aPO4" title="interTwin demo: itwinai (WP6)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

If you have troubles visualizing the live stream above, [watch it on YouTube](https://www.youtube.com/watch?v=UcqiW69aPO4).
