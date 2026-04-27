[English](README.md) | [中文](README_zh.md)

## Introduction

The dataset is released as part of the academic research conducted for the master’s thesis entitled:

**Design and Value Realization of a Digital Solution for Tightening Process Quality Management**.

**Author:** YANG Zhenye (yang.zhenye@foxmail.com or zhen.ye.yang@atlascopco.com)  
**Supervisor:** TIAN Yingjie  
**Institution:** University of Chinese Academy of Sciences(UCAS)  
**Date:** June 2026

This is a real-world industrial dataset designed for anomaly analysis in threaded fastener tightening processes. The dataset is constructed from actual tightening operation data collected at industrial production sites, where synchronized torque–angle time-series signals are recorded during each tightening process. It aims to support research on anomaly detection, quality assessment, and time-series modeling in industrial tightening applications.

To ensure consistency in process conditions, each sub-dataset is collected from the same workstation, the same tightening tool, and the same tightening program, while different sub-datasets correspond to different tightening joints or operating conditions. For representative anomaly types within each dataset, a **SMALL** number of samples are manually labeled based on engineering expertise, providing reference labels for algorithm validation and analysis. Since multiple abnormal phenomena may occur simultaneously during a single tightening operation, the dataset adopts a multi-label annotation scheme to better reflect the complexity of real industrial scenarios.

This dataset is intended for research on anomaly detection, weakly supervised learning, and industrial time-series analysis, and can be used for both academic research and engineering-oriented method evaluation.

| Dataset | Method | Total | A1 | A2 | A3 | A4 | A5 | A6 | A7 | 
|:-------:|:----:|------:|---:|---:|---:|---:|---:|---:|---:|
| D1 | T | 22413 | 24 | / | 4 | 46 | 4 | 24 | / | 
| D2 | T | 10000 | 12 | / | / | / | 12 | 6 | / | 
| D3 | T | 4996 | / | 11 | 5 | 36 | 2 | 8 | / | 
| D4 | TA | 10000 | 15 | / | 34 | / | / | / | / | 
| D5 | T | 51 | / | / | / | / | / | / | 1 | 
| D6 | TA | 4933 | / | 8 | / | / | / | / | / | 
| D7 | T | 10000 | 21 | / | / | / | 2 | 14 | / | 
| D8 | T | 40000 | 24 | / | 50 | / | 12 | / | / | 

**Note:**  
- Dataset **D6** corresponds to yield tightening. Therefore, part of the necking-related samples are labeled as **A2**.
- T: Torque only method; TA: Torque+Angle method.

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

Due to GitHub size limits, raw data is not stored in this repository, raw data is available at:

[https://zenodo.org/records/18007039]

---

## License

This dataset is licensed under the  
**Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license.

You are free to use, share, and adapt the data for non-commercial purposes,
provided that appropriate credit is given.

For commercial use, please contact the author.



---

