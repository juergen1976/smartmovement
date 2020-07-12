# Smart movement

## Based on my article in 05/2020: Kubernetes - Smarte Orchestrierung von Docker & Co. (25.09.2020)


This example project will cover a Smartphone extension to track movement data and process the Machine Learning pipeline
on Kubernetes using Kubeflow.

The goal is to design a blueprint for a scaleable Mobile data and Machine Learning pipeline to capture data and build
smart recommendations features.

Focus:
* Scalable capture and processing of mobile data in a Kubernetes setup
* On premise or cloud data processing
* Fully automated Machine Learning pipeline to process mobile data



Used Frameworks:
1. Flutter for the mobile application with different sensor packages
2. Kubeflow on Kubernetes
3. SciKitLearn


## Simplified architecture:

![Architecture](images/Architecture.png)

