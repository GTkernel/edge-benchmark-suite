# Mobile Edge Computing (MEC) Benchmark Suite

A list shown the applications used in the research projects.

## Cryptography

- [Secure MPC](https://github.com/GTkernel/secure-mpc): Benchmarks for [EMP-Toolkit](https://github.com/emp-toolkit/emp-tool)'s [AGMPC](https://github.com/emp-toolkit/emp-agmpc), a maliciously secure BMR-style protocol tolerating an arbitrary number of corruptions.

## Video Analytics

- [Streamer](https://github.com/GTkernel/streamer): A framework developed by CMU, used for building pipelines from video processing functional blocks. Streamer is designed to work with ML inference process, the analytics part.
TODO: currently linked to official SAF version, since not sure the legacy version is allowed to share or not.

- [YOLOv3 Tensorflow](https://github.com/GTkernel/yolov3-tf2): YOLOv3 application ported to python TensorFlow2. YOLOv3 is for real-time object detection developed by Joseph Redmon, a U of W student.

## Video 360

- [Video 360](https://github.com/GTkernel/video360): A framework developed by Fraunhofer Heinrich Hertz Institute. JavaScript implementation of MPEG-OMAF viewport-dependent video profile with HEVC tiles.

## Industrial Automation

- [Robotic OS](https://github.com/GTkernel/ros): A popular application used in robotic and IoT industry. 
This repo containerized the simple pub-sub example.

## Content Delivery Network

- [Apache Traffic Control](https://github.com/GTkernel/trafficcontrol): The on-premise CDN system. This repo covers the configuration files of Kubernetes. To running an Apache CDN, you in k8s, you don't need to create an additional DNS server.

## Core Network

### 4G

- [NextEPC](https://github.com/GTkernel/nextepc): Open sourced LTE testbed. Containerized and k8s-friendly. 
In our project, we only use the RAN core network of NextEPC.
TODO: currently linked to a private team/organization, still need to fix some configurations.
- [SrsLTE](https://github.com/GTkernel/srslte): Same as NextEPC. In our project, we only used the eNB and UE parts of SrsLTE.
TODO: currently linked to a private team/organization, still need to fix some configurations.

### 5G

- Magma: Fork from [official repo](https://github.com/magma/magma) to build on-premised AGW and Orc8r by Helm charts. Currently integrated with eNB function of SrsLTE for 4G testbed.
Repo is under processed.

## Machine Learning

- [TensorFlow Model Builder](https://github.com/carol-hsu/tensorflow_model_builder): This repo shows some reference steps of formatting official trained TensorFlow models into protobuf files.

