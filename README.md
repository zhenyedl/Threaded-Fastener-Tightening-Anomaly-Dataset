[English](README.md) | [中文](README_zh.md)

## Introduction

The dataset is released as part of the academic research conducted for the master’s thesis entitled:

**Tightening Analysis System for Threaded Fasteners in Intelligent Manufacturing**.

**Author:** YANG Zhenye(yang.zhenye@foxmail.com)  
**Supervisor:** TIAN Yingjie  
**Institution:** University of Chinese Academy of Sciences(UCAS)  
**Date:** June 2026

This is a real-world industrial dataset designed for anomaly analysis in threaded fastener tightening processes. The dataset is constructed from actual tightening operation data collected at industrial production sites, where synchronized torque–angle time-series signals are recorded during each tightening process. It aims to support research on anomaly detection, quality assessment, and time-series modeling in industrial tightening applications.

To ensure consistency in process conditions, each sub-dataset is collected from the same workstation, the same tightening tool, and the same tightening program, while different sub-datasets correspond to different tightening joints or operating conditions. For representative anomaly types within each dataset, a **SMALL** number of samples are manually labeled based on engineering expertise, providing reference labels for algorithm validation and analysis. Since multiple abnormal phenomena may occur simultaneously during a single tightening operation, the dataset adopts a multi-label annotation scheme to better reflect the complexity of real industrial scenarios.

This dataset is intended for research on anomaly detection, weakly supervised learning, and industrial time-series analysis, and can be used for both academic research and engineering-oriented method evaluation.

| Dataset | Total | A1 | A2 | A3 | A4 | A5 | A6 | A7 | 
|:-------:|------:|---:|---:|---:|---:|---:|---:|---:|
| D0 | 22773 | 1 | / | 29 | / | 6 | 2 | / | 
| D1 | 178 | 16 | / | 21 | / | / | / | / | 
| D2 | 10000 | 11 | / | / | / | 13 | 7 | / | 
| D3 | 4996 | / | 11 | 5 | 47 | 2 | 8 | / | 
| D4 | 10000 | 15 | / | 39 | / | / | / | / | 
| D5 | 51 | / | / | / | / | / | / | 1 | 
| D6 | 4933 | / | 9 | / | / | / | / | / | 
| D7 | 10000 | 11 | 3 | 17 | / | 13 | / | / | 

**Note:**  
Dataset **D6** corresponds to yield tightening. Therefore, part of the necking-related samples are labeled as **A2**.

---
### A1: Engagement or Slip-off

### A2: Yield or Crashing or Necking

### A3: Interfacial Instability
- **Co-rotation**
- **Thread stripping / Head rounding**  

### A4: Stick–Slip

### A5: Abnormal Prevailing Torque
- **Thread crossing / Jamming / Floating / Seizing**
- **Stiffness variation / Gap closure**  

### A6: Re-tightening (Rehit)

### A7: Tool or Equipment Worn
---

## Data Availability

Raw data is available at:
[https://zenodo.org/record/18006923]

Due to GitHub size limits, raw data is not stored in this repository.

## License

This dataset is licensed under the  
**Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license.

You are free to use, share, and adapt the data for non-commercial purposes,
provided that appropriate credit is given.

For commercial use, please contact the author.



---

