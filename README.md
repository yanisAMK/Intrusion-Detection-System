# Intrusion Detection System using Deep Learning & Federated Learning

## Introduction
This repository contains the implementation of an Intrusion Detection System (IDS) using deep learning techniques. The IDS is designed to detect and classify various types of network intrusions. The system leverages the power of deep learning algorithms and federated learning to achieve accurate and robust intrusion detection.


## Dataset
The IDS utilizes two popular datasets for training and evaluation:
1. NSL-KDD: This dataset is widely used for network intrusion detection research. It provides a large number of pre-processed network traffic samples with various attack types.
   - [NSL-KDD Dataset](https://www.unb.ca/cic/datasets/nsl.html)
2. CIC IDS 2017: This dataset contains labeled network traffic data captured from a real-world environment. It offers a comprehensive collection of network traffic features for effective intrusion detection.
   - [CIC IDS 2017 Dataset](https://www.unb.ca/cic/datasets/ids-2017.html)

## Framework for Federated Learning
The framework used for federated learning is [Flower](https://flower.dev/), which supports multiple aggregation algorithms including FedAvg, FedAvgM, and FedAdam.
