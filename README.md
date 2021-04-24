# Awesome Benchmark

A list shown the applications used in the research projects.

## Edge Computing

### Cryptography

- [Secure MPC](https://github.gatech.edu/kernel-benchmark-suite/securempc-benchmark): Benchmarks for [EMP-Toolkit](https://github.com/emp-toolkit/emp-tool)'s [AGMPC](https://github.com/emp-toolkit/emp-agmpc), a maliciously secure BMR-style protocol tolerating an arbitrary number of corruptions.

### Video Analytics

- [Streamer](https://github.gatech.edu/kernel-benchmark-suite/streamer): A framework developed by CMU, used for building pipelines from video processing functional blocks. Streamer is designed to work with ML inference process, the analytics part.
TODO: currently linked to official SAF version, since not sure the legacy version is allowed to share or not.

### Industrial Automation

- [Robotic OS](https://github.gatech.edu/kernel-benchmark-suite/ros): A popular application used in robotic and IoT industry. 
This repo containerized the simple pub-sub example.

### Content Delivery Network

- [Apache Traffic Control](https://github.gatech.edu/kernel-benchmark-suite/trafficcontrol): The on-premise CDN system. This repo covers the configuration files of Kubernetes. To running an Apache CDN, you in k8s, you don't need to create an additional DNS server.

### Core Network

#### 4G

- [NextEPC](https://github.gatech.edu/kernel-benchmark-suite/nextepc): Open sourced LTE testbed. Containerized and k8s-friendly. 
In our project, we only use the RAN core network of NextEPC.
TODO: currently linked to a private team/organization, still need to fix some configurations.
- [SrsLTE](https://github.gatech.edu/kernel-benchmark-suite/srslte): Same as NextEPC. In our project, we only used the eNB and UE parts of SrsLTE.
TODO: currently linked to a private team/organization, still need to fix some configurations.

## Machine Learning

- [TensorFlow Model Builder](https://github.com/carol-hsu/tensorflow_model_builder): This repo shows some reference steps of formatting official trained TensorFlow models into protobuf files.


## Memory System

## Others

### TA tools

- [Canvas API](https://github.com/carol-hsu/canvas_submission_api): A python tool to submit scores automatically through HTTP requests.
