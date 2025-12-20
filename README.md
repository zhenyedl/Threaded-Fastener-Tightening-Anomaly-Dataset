## Introduction

### English Introduction

The dataset is released as part of the academic research conducted for the master’s thesis entitled: **Tightening Analysis System for Threaded Fasteners in Intelligent Manufacturing**.

**Author:** YANG Zhenye  
**Supervisor:** TIAN Yingjie  
**Institution:** University of Chinese Academy of Sciences(UCAS)  
**Date:** June 2026

This is a real-world industrial dataset designed for anomaly analysis in threaded fastener tightening processes. The dataset is constructed from actual tightening operation data collected at industrial production sites, where synchronized torque–angle time-series signals are recorded during each tightening process. It aims to support research on anomaly detection, quality assessment, and time-series modeling in industrial tightening applications.

To ensure consistency in process conditions, each sub-dataset is collected from the same workstation, the same tightening tool, and the same tightening program, while different sub-datasets correspond to different tightening joints or operating conditions. For representative anomaly types within each dataset, a small number of samples are manually annotated based on engineering expertise, providing reference labels for algorithm validation and analysis. Since multiple abnormal phenomena may occur simultaneously during a single tightening operation, the dataset adopts a multi-label annotation scheme to better reflect the complexity of real industrial scenarios.

This dataset is intended for research on anomaly detection, weakly supervised learning, and industrial time-series analysis, and can be used for both academic research and engineering-oriented method evaluation.

| Dataset | Total | A1 | A2 | A3 | A4 | A5 | A6 | A7 | A8 | A9 |
|--------|-------:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| D1 | 178 | 16 | / | / | 21 | / | / | / | / | / |
| D2 | 10000 | 11 | / | / | / | / | 13 | 7 | / | / |
| D3 | 4996 | / | 11 | 6 | / | 47 | 2 | 8 | 1 | / |
| D4 | 10000 | 15 | / | 19 | 9 | / | / | / | 11 | / |
| D5 | 4933 | / | 9 | / | / | / | / | / | / | / |
| D6 | 10000 | 11 | 3 | 11 | 6 | / | 13 | / | / | / |

**Note:**  
Dataset **D5** corresponds to yield tightening. Therefore, part of the necking-related samples are labeled as **A2**.

---
### A1: Engagement or Slip-off
---
### A2: Yield or Crashing or Necking
---
### A3: Co-rotation
---
### A4: Stripping or Rounding
---
### A5: Thread crossing / Jamming / Floating / Seizing /（Abnoraml Prevailing Torque）
---
### A6: Stick–Slip
---
### A7: Re-tightening (Rehit)
---
### A8: Gap Closure or Stiffness Variation
---
### A9: Tool or Equipment Worn
---

## License

This dataset is licensed under the  
**Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license.

You are free to use, share, and adapt the data for non-commercial purposes,
provided that appropriate credit is given.

For commercial use, please contact the author.



---

