# Using GNN to predict mutation-causing genes.
## Overview
Mô hình được training bằng bộ dữ liệu MUTAG, bộ dữ liệu về các Gene đã được số hoá thành các Vector, mang các đặc điểm tính chất của Gene đó, Sử dụng bộ dữ liệu này để huấn luyện mô hình học máy.  
## Table of Contents
- [Using GNN to predict mutation-causing genes.](#using-gnn-to-predict-mutation-causing-genes)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Folder Structure](#folder-structure)
    - [Explanation](#explanation)
  - [Usage](#usage)
## Installation
Install libraries and dependencies

```bash
pip install -r requirements1.txt
```
## Folder Structure
.  
├── backups  
├── HW5_GNN  
│   ├── HW5_GNN_pre.ipynb  
│   └── img  
│       ├── graph-1.png  
│       ├── graph-2.png  
│       └── graph-3.png  
├── HW5_GNN-lib  
│   ├── data  
│   │   └── MUTAG  
│   │       ├── processed  
│   │       │   ├── data.pt  
│   │       │   ├── pre_filter.pt  
│   │       │   └── pre_transform.pt  
│   │       └── raw  
│   │           ├── MUTAG_A.txt  
│   │           ├── MUTAG_edge_labels.txt  
│   │           ├── MUTAG_graph_indicator.txt  
│   │           ├── MUTAG_graph_labels.txt  
│   │           ├── MUTAG_node_labels.txt  
│   │           └── README.txt  
│   ├── requirements1_post.sh  
│   ├── requirements1.txt  
│   ├── requirements2.txt  
│   ├── requirements3.txt  
│   └── requirements4.txt  
└── Readme.md  
### Explanation
- **`backups`**: Backups các file quan trọng
- **`HW5_GNN`**: Source code chính
- **`HW5_GNN-lib`**: Data và cấu hình các thư viện
## Usage
Run **W5_GNN.ipynb**