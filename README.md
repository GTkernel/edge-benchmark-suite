# Mobile Edge Computing (MEC) Benchmark Suite

A list shown the applications used in the research projects.

## Artificial Intelligence

- [CLIP with Jina AI](https://github.com/GTkernel/jina-clip): Microservice CLIP application in Jina AI framework. This repo would cover the generation of deployment files on Kubernetes.

## Content Delivery Network

- [Apache Traffic Control](https://github.com/GTkernel/trafficcontrol): The on-premise CDN system. This repo covers the configuration files of Kubernetes. To running an Apache CDN, you in k8s, you don't need to create an additional DNS server.

## Core Network

### 4G

- [NextEPC](https://github.com/GTkernel/nextepc): Open sourced LTE testbed. Containerized and k8s-friendly. 
In our project, we only use the RAN core network of NextEPC.

- [SrsRAN](https://github.com/GTkernel/srsRAN): Same as NextEPC. In our project, we only used the eNB and UE parts of SrsRAN.

### 5G

- Magma: Fork from [official repo](https://github.com/magma/magma) to build on-premised AGW and Orc8r by Helm charts. Currently integrated with eNB function of SrsLTE for 4G testbed.
Repo is under processed.

## Cryptography

- [Secure MPC](https://github.com/GTkernel/secure-mpc): Benchmarks for [EMP-Toolkit](https://github.com/emp-toolkit/emp-tool)'s [AGMPC](https://github.com/emp-toolkit/emp-agmpc), a maliciously secure BMR-style protocol tolerating an arbitrary number of corruptions.

## Industrial Automation

- [Robotic OS](https://github.com/GTkernel/ros): A popular application used in robotic and IoT industry. 
This repo containerized the simple pub-sub example.


## IoT
- [IOTCOMMS](https://github.com/GTkernel/iotcomms): An framework used for creating IoT application with a variety of different workload configurations. This framework aims to caputure the diverse nature of IoT applications in every stage - the workload generator, the tranport layer protocols and the could server side components.


## Machine Learning

- [TensorFlow Model Builder](https://github.com/carol-hsu/tensorflow_model_builder): This repo shows some reference steps of formatting official trained TensorFlow models into protobuf files.


## Video 360

- [Video 360](https://github.com/GTkernel/omaf-video-360): A framework developed by Fraunhofer Heinrich Hertz Institute. JavaScript implementation of MPEG-OMAF viewport-dependent video profile with HEVC tiles.
We add containerized deploying methods as for our MEC benchmarking.


## Video Analytics

- [Object Detection TensorFlow Serving](https://github.com/GTkernel/object-detector-tf-serve) 
This ML model serving platform based on TensorFlow Serving, we refered to this public [repo](https://github.com/LanderMoerkerke/camera-feed-object-detector-tf-serve) and add our deployment for MEC benchmarking.
Checking the directory of `./k8s` for deployment details.

- [Streamer](https://github.com/GTkernel/streamer): A framework developed by CMU, used for building pipelines from video processing functional blocks. Streamer is designed to work with ML inference process, the analytics part.
TODO: currently linked to official SAF version, since not sure the legacy version is allowed to share or not.

- [YOLOv3 Tensorflow](https://github.com/GTkernel/yolov3-tf2): YOLOv3 application ported to python TensorFlow2. YOLOv3 is for real-time object detection developed by Joseph Redmon, a U of W student.

