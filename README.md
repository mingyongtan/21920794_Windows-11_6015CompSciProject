## README

Last Updated: May 28, 2025  
Author: Ming Yong Tan

### Description
This dataset presents system performance data under both Single User and Multiple User environments. Metrics such as CPU, memory, disk, and network usage were collected using SysGauge and other tools at 10-minute, 15-minute, and 20-minute intervals. Applications monitored include Discord, Microsoft Edge, and Excel. The structure is designed to support comparative analysis, system benchmarking, and resource usage evaluations under varying workloads.

### Directory Structure
```text
DATA/
├── Multiple User/                             # Multi-user simulation dataset
│   ├── CPU-Memory-DiskManagement/             # Performance data by app
│   │   ├── Discord/                           
│   │   │   ├── 10 mins/                       # Discord resource usage at 10 mins
│   │   │   │   ├── 10mins.xlsx
│   │   │   │   ├── 10mins - Copy.xlsx
│   │   │   │   └── discord 10 mins updated.xlsx
│   │   │   ├── 15 mins/
│   │   │   │   └── discord 15 mins updated.xlsx
│   │   │   ├── 20 mins/
│   │   │   │   └── discord 20 mins updated.xlsx
│   │   │   └── Disk/
│   │   │       ├── 10 mins excel.csv
│   │   │       ├── 15 mins excel.csv
│   │   │       ├── 20 mins excel.csv
│   │   │       └── Summary Discord.xlsx
│   │   ├── Excels/
│   │   │   ├── 10 mins/
│   │   │   │   └── 10 mins updated.xlsx, excel 10 mins.csv, etc.
│   │   │   ├── 15 mins/
│   │   │   ├── 20 mins/
│   │   │   └── Disk/
│   │   │       ├── 10 mins excel.csv
│   │   │       ├── 15 mins excel.csv
│   │   │       ├── 20 mins excel.csv
│   │   │       └── Disk Summary.xlsx
│   │   └── Microsoft Edge/
│   │       ├── 10 mins/
│   │       ├── 15 mins/
│   │       ├── 20 mins/
│   │       └── Disk/
│   │           ├── 10 mins excel.csv
│   │           ├── 15 mins excel.csv
│   │           ├── 20 mins excel.csv
│   │           └── Summary Edge.xlsx
│   └── Network/
│       ├── Discord/
│       │   ├── 10 mins/
│       │   │   └── DC 10mins.xlsx
│       │   ├── 15 mins/
│       │   │   └── DC 15.xlsx
│       │   └── 20 mins/
│       │       ├── DC 20 mins.xlsx
│       │       └── DC 20mins updated.xlsx
│       └── Edge/
│           ├── 10 mins/
│           │   └── microsoft edge 10 min.xlsx
│           ├── 15 mins/
│           │   └── edge 15mins.xlsx
│           └── 20 mins/
│               └── 20 mins.xlsx

├── Single User (Base Set)/                   # Baseline system metrics (1 user only)
│   ├── CPU-Memory/
│   │   ├── 10 mins CPU/
│   │   │   ├── SysGauge Process Monitor *.xlsx
│   │   │   └── Summary of 10 mins.xlsx
│   │   ├── 15 mins CPU/
│   │   │   └── Summary 15 mins.xlsx
│   │   └── 20 mins CPU/
│   │       └── Summary 20 mins.xlsx
│   ├── Disk management/
│   │   ├── 10 mins/
│   │   │   ├── Disk management 10 mins {1–10}.csv
│   │   │   └── Disk management 10 mins Summary.xlsx
│   │   ├── 15 mins/
│   │   │   ├── Disk management 15 mins {1–10}.csv
│   │   │   └── Disk management 15 mins Summary.xlsx
│   │   └── 20 mins/
│   │       ├── Disk management 20 mins {1–10}.csv
│   │       └── Summary Disk management 20 mins.xlsx
│   └── Network/
│       ├── 10 mins/
│       │   ├── 10 mins base.xlsx
│       │   └── 10 mins base - Copy.xlsx
│       ├── 15 mins/
│       │   └── 15 mins.xlsx
│       └── 20 mins/
│           └── 20 mins.xlsx
```
