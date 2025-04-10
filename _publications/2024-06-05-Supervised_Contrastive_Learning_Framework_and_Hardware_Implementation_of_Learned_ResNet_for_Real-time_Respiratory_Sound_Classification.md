---
title: "Supervised Contrastive Learning Framework and Hardware Implementation of Learned ResNet for Real-time Respiratory Sound Classification"
authors: "<b>Jinhai Hu</b>*, Cong Sheng Leow*, Shuailin Tao, Wang Ling Goh, Yuan Gao"
collection: publications
category: manuscripts
permalink: /publication/2024-06-05-Supervised_Contrastive_Learning_Framework_and_Hardware_Implementation_of_Learned_ResNet_for_Real-time_Respiratory_Sound_Classification
excerpt: 
date: 2024-06-05
venue: 'IEEE Transactions on Biomedical Circuits and Systems'
slidesurl:
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10550005'
citation: 
abstract: "This paper presents a supervised contrastive learning (SCL) framework for respiratory sound classification and the hardware implementation of learned ResNet on field programmable gate array (FPGA) for real-time monitoring. At the algorithmic level, multiple techniques such as features augmentation and MixUp are combined holistically to mitigate the impact of data scarcity and imbalanced classes in the training dataset. Bayesian optimization further enhances the classification accuracy through parameter tuning in pre-processing and SCL. The proposed framework achieves 0.8725 total score (including runtime score) on a ResNet-18 model in both event and record multi-class classification tasks using the SJTU Paediatric Respiratory Sound Database (SPRSound). In addition, algorithm-hardware co-optimizations including Quantization-Aware Training (QAT), merge of network layers, optimization of memory size and number of parallel threads are performed for hardware implementation on FPGA. This approach reduces 40% model size and 70% computation latency. The learned ResNet is implemented on a Xilinx Zynq ZCU102 FPGA with 16ms latency and less than 2% inference score degradation compared to the software model."
---
