<<<<<<< HEAD
normal:   No attack
attack1:  Malicious command injection(Manipulated Variable:Production Setpoint)
attack2:  Malicious command injection(Manipulated Variable:Stripper Level Setpoint)
attack3:  Malicious command injection(Manipulated Variables:yA Setpoint、yAC Setpoint)
attack4:  Physical process disturbance(Manipulated Variable:A and C feed ratio)
attack5:  Physical process disturbance(Manipulated Variable:Cooling water outlet valve of reactor)
attack6:  Physical process disturbance(Manipulated Variable:Cooling water outlet valve of separator)
attack7:  False data injection(Manipulated Variable:Stripper level)
attack8:  Dos(Manipulated Variable:PLC for controlling the separator unit)

In the file normal.csv, the data are all under normal working conditions, and their labels are 0.

In the file attack1~8.csv, the data label when it is not attacked is 0, and the label after it is attacked is not 0, which is 1-8, corresponding to different attack conditions respectively.
=======
# TE-CUP-SEC-datasets

## 介绍

TE-CUP-SEC数据集是一个面向工业控制系统（ICS）安全研究的增强型多源数据集，旨在支持异常检测、故障溯源分析和安全防御等方向的研究。该数据集由中国石油大学（北京）工控安全监测实验室构建，依托经典的 Tennessee Eastman (TE) 过程模型，融合工业网络设备、控制器与通信协议，实现了物理过程、控制逻辑与通信网络三层架构的虚实融合建模。通过模拟包括恶意命令注入、拒绝服务（DoS）攻击、虚假数据注入与过程扰动等多种典型威胁，数据集同步采集了物理状态变量与网络流量信息，全面覆盖网络层、控制层与物理层的关键特征。

## Introduction

The TE-CUP-SEC dataset is an enhanced multi-source dataset for industrial control system (ICS) security research, aiming to support studies in anomaly detection, fault tracing, and security defense. Constructed by the Industrial Control Security Monitoring Laboratory at China University of Petroleum (Beijing), this dataset is based on the classic Tennessee Eastman (TE) process model and integrates industrial network devices, controllers, and communication protocols, achieving a virtual-physical fusion of the three-layer architecture: physical process, control logic, and communication network. By simulating multiple typical threats including malicious command injection, denial-of-service (DoS) attacks, false data injection, and process disturbances, the dataset synchronously collects physical state variables and network traffic information, comprehensively covering key features of the network layer, control layer, and physical layer.

## 数据集内容 / Dataset Contents

- **工艺过程数据 / Process data**：Process_data、Process_data_Updated_attack4
- **流量数据 / Traffic data**：TE_CUP_SEC_data，链接 / Link: https://pan.baidu.com/s/1VT1x56k2RN9tKlXdk5nq4Q 提取码 / Access code: S2SL

## 引用格式 / Citation Format

若使用本数据集，请引用以下文献 / If you use this dataset, please cite the following paper:

X. Wang, J. Wang, W. Song, Z. Wang. TE-CUP-SEC: Modelling and dataset for industrial control system security. *Can. J. Chem. Eng.* 2026, 1. https://doi.org/10.1002/cjce.70341

## 相关参考文献 / Related References

- [1] 王新伟,王金江,汪征,等.流程制造工控网络安全虚实融合仿真技术及应用研究[J].系统仿真学报,2026,38(01):84-98.DOI:10.16182/j.issn1004731x.joss.24-1395.  
Wang X., Wang J., Wang Z., et al. Research on CSTR industrial control security virtual reality fusion simulation method[J]. Journal of System Simulation, 2026, 38(01): 84-98. DOI: 10.16182/j.issn1004731x.joss.24-1395.

- [2] 何广汇,王金江,魏振强,等.CSTR工控安全虚实融合仿真方法研究[J].化工学报,2025,76(9):4524-4538.  
He G., Wang J., Wei Z., et al. Research on CSTR industrial control security virtual reality fusion simulation method[J]. CIESC Journal, 2025, 76(9): 4524-4538.

- [3] Ji S, Wang J, Wang Z, Zhang F. Explainable Causal Graph‐based Method for Diagnosis and Root Cause Analysis in Process Systems. Process Safety and Environmental Protection. 2025;203:107953.

>>>>>>> a4e2dcf0f69c77bef1d0b6b7943279607db49d60
