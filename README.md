# GENGAT

**[S Ratna¹, Sukhdeep Singh², Anuj Sharma¹*]** 
[1 Department of Computer Science and Applications, Panjab University, Chandigarh, India
sratna@pu.ac.in, anujs@pu.ac.in
2 Department of Computer Science, D.M. College (affiliated to Panjab University, Chandigarh), Moga, Punjab, India
sukha13@ymail.com]    
> 📦 Framework: PyTorch Geometric  
> 🧪 Task: Node Classification

---

## Overview

This repository contains the official implementation of **GenGAT framework**, evaluated on **6 benchmark datasets** from PyTorch Geometric for the node classification task.


## Datasets

All 6 datasets are loaded directly from [PyTorch Geometric (PyG)](https://pytorch-geometric.readthedocs.io/):

| # | Dataset | type | Category |
|---|---------|-----------|----------|
| 1 | Chameleon |`heterophilic` | Wikipedia Network |
| 2 | Squirrel | `heterophilic` | Wikipedia Network |
| 3 | Actor | `heterophilic` | Co-occurence Network |
| 4 | Amazon Photo | `homophilic` | Co-purchase Graph |
| 5 | Amazon Computers | `homophilic` | Co-purchase Graph |
| 6 | Coauthor Physics | `homophilic` |  |Co-authored network



> **Note:** All datasets are automatically downloaded by PyG on first run — no manual download needed.


---

## File Structure

```
.
├── CODE.ipynb         # Main code file
├── training1.ipynb         
├── training2.ipynb         
│
├── training3.ipynb            
├── training4.ipynb            
└── README.md
``` 
> All the experiments have been performed on GPU server

---

## Running the Code

### Main Experiments

```
CODE.ipynb  
```

### Visualization

```
training1.ipynb
training2.ipynb
training3.ipynb
training4.ipynb  
```

Install dependencies by running the first cell:

```python
!pip install torch_geometric
```




## Installation

```bash
pip install torch torch_geometric scikit-learn matplotlib
```

---

---

## Results

Results are reported as **Mean ± Std** over **10 runs** with two random node splits, 80:10:10 (train:validate:test) and 70:15:15.

| Dataset | Accuracy (%) |
|---------|-------------|
| Chameleon | XX.XX ± X.XX |
| Squirrel | XX.XX ± X.XX |
| Actor | XX.XX ± X.XX |
| Amazon Photo | XX.XX ± X.XX |
| Amazon Computers | XX.XX ± X.XX |
| Coauthor Physics | XX.XX ± X.XX |


---


## System Requirements


| Component | Specification |
|-----------|--------------|
| OS |Windows 10 (Version 10.0.20348) |
| GPU | 2 × NVIDIA L4 |
| CUDA | 11.8 |
| RAM | 137.18 GB |
| Python |3.11.7 |
| PyTorch | 2.7.1+cu118 |
| PyG (torch_geometric) | 2.6.1 |
| VRAM | 23.91 GB (each) |


---



## Installation

```bash
pip install torch torch_geometric scikit-learn matplotlib
```

---




 
## Acknowledgment
 
The work presented in this paper is supported by the Department of Computer Science and Applications (DCSA), Panjab University, Chandigarh, India, which provided the necessary GPU resources to conduct the experiments.
 
- **[PyTorch](https://pytorch.org/)** — The deep learning framework used for all model implementation and training.
- **[PyTorch Geometric (PyG)](https://pytorch-geometric.readthedocs.io/)** — The graph neural network library used for dataset loading, graph convolutions, and sparse operations.
- GENConv — Li, Guohao, et al. "Deepergcn: All you need to train deeper gcns." arXiv preprint arXiv:2006.07739 (2020).
- GAT - Veličković, Petar, et al. "Graph attention networks." arXiv preprint arXiv:1710.10903 (2017).
- UMAP used for visulaization : McInnes, Leland, John Healy, and James Melville. "Umap: Uniform manifold approximation and projection for dimension reduction." arXiv preprint arXiv:1802.03426 (2018).
  

 
---
 
