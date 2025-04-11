---
title: "Classification of ECG Anomaly with Dynamically-biased LSTM for Continuous Cardiac Monitoring"
authors: "<b>Jinhai Hu</b>, Wang Ling Goh, Yuan Gao"
collection: publications
category: conferences
permalink: /publication/2023-05-21-Classification_of_ECG_Anomaly_with_Dynamically-biased_LSTM_for_Continuous_Cardiac_Monitoring
excerpt:
date: 2023-05-21
venue: 'IEEE International Symposium on Circuits and Systems (ISCAS)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10181690'
citation:
abstract: "This paper presents an electrocardiogram (ECG) signal classification model based on dynamically-biased Long Short-Term Memory (DB-LSTM) network. Compared to conventional LSTM networks, DB-LSTM introduces a set of parameters C which save the previous time-step cell gate states of the unit cell. Hence, more feature information is preserved and a smaller size network is required for the classification task. Comprehensive simulations using MIT-BIH ECG datasets show that this model can perform ECG feature classification with shorter time window, faster training convergence while achieving comparable training and classification accuracy with much lower weigh resolution. Compared to the other state-of- art ECG analysis algorithms, this model only requires 4 layers, and it achieved 96.74% accuracy when weights are truncated from FP32 to INT4 with only 2.4% accuracy degradation. Implemented on Xilinx Artix-7 FPGA, the proposed design is estimated to consume only 40μW dynamic power, which is a promising candidate for resource constrained edge devices."
---
