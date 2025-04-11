---
title: "Energy Efficient Software-hardware Co-design of Quantized Recurrent Convolutional Neural Network for Continuous Cardiac Monitoring"
authors: "<b>Jinhai Hu</b>, Cong Sheng Leow, Wang Ling Goh, Yuan Gao"
collection: publications
category: conferences
permalink: /publication/2023-06-11-Energy_Efficient_Software-hardware_Co-design_of_Quantized_Recurrent_Convolutional_Neural_Network_for_Continuous_Cardiac_Monitoring
excerpt:
date: 2023-06-11
venue: 'IEEE International Conference on Artificial Intelligence Circuits and Systems (AICAS)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10168601'
citation:
abstract: "This paper presents an electrocardiogram (ECG) signal classification model based on Recurrent Convolutional Neural Network (RCNN). With recurrent connections and data buffers, a single convolutional layer is reused to implement multiple layers function. Using a 5-layers CNN network as an example, this approach reduces the number of parameters by more than 50% while achieving the same feature extraction size. Furthermore, quantized RCNN (QRCNN) is proposed where the input signal, interlayer output, and kernel weights are quantized to unsigned INT8, INT4, and signed INT4 respectively. For hardware implementation, pipelining and data reuse within the 1-D convolution kernel can potentially reduce latency. QRCNN model achieved 98.08% validation accuracy on MIT-BIH datasets with only 1% degradation due to quantization. The estimated dynamic power consumption of the QRCNN is less than 60% of a conventional quantized CNN when implemented on a Xilinx Artix-7 FPGA, showing the potential for resource-constraint edge devices."
---
