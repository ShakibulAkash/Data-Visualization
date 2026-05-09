# Evolution-Aware Dynamic Graph Layout for Stable and Adaptive Visualization

## Overview

This repository contains the implementation of an evolution-aware dynamic graph layout framework designed to improve temporal stability and adaptive visualization for evolving graph structures.

The project combines:

* Dynamic graph processing
* Temporal graph neural networks
* Prediction-aware layout computation
* Stable graph visualization

The framework is designed to reduce unnecessary node movement while preserving structural consistency across time-evolving graph snapshots.

---

## Features

* Temporal graph representation learning
* Prediction-aware dynamic graph layout
* Stable node positioning across time steps
* Reduced layout drift
* Adaptive visualization for evolving networks
* Support for real-world dynamic graph datasets

---

## Repository Structure

```text
Evolution-Aware-Dynamic-Graph-Layout/
│
├── data/
│   ├── reddit/
│   ├── enron/
│   └── hep-th/
│
├── images/
│   ├── framework.png
│   ├── comparison.png
│   └── evolution.png
│
├── models/
│   ├── temporal_gnn.py
│   ├── layout_model.py
│   └── prediction_module.py
│
├── notebooks/
│   └── experiments.ipynb
│
├── results/
│   ├── figures/
│   └── metrics/
│
├── train.py
├── evaluate.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/ShakibulAkash/Evolution-Aware-Dynamic-Graph-Layout-for-Stable-and-Adaptive-Visualization.git
```

Move into the project directory:

```bash
cd Evolution-Aware-Dynamic-Graph-Layout-for-Stable-and-Adaptive-Visualization
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Requirements

```text
numpy
pandas
networkx
matplotlib
scikit-learn
torch
torch-geometric
jupyter
```

---

## Usage

### Train the Model

```bash
python train.py
```

### Evaluate the Model

```bash
python evaluate.py
```

### Run Notebook Experiments

```bash
jupyter notebook
```

---

## Framework Pipeline

<p align="center">
  <img src="images/framework.png" width="850"/>
</p>

The framework follows these stages:

1. Dynamic graph construction
2. Temporal representation learning
3. Prediction-aware layout generation
4. Constraint-based refinement
5. Stable visualization rendering

---

## Visualization Examples

### Dynamic vs Proposed Layout

<p align="center">
  <img src="images/comparison.png" width="900"/>
</p>

### Temporal Evolution

<p align="center">
  <img src="images/evolution.png" width="900"/>
</p>

---

## Results

| Method          | Stability  | Node Movement |
| --------------- | ---------- | ------------- |
| Static Layout   | High Drift | High          |
| Dynamic Layout  | Moderate   | Moderate      |
| Proposed Layout | Stable     | Reduced       |

---

## Datasets

This project supports:

* Reddit Hyperlink Network
* Enron Email Network
* arXiv Hep-Th Citation Network

---

## Future Improvements

* Large-scale graph optimization
* Faster temporal processing
* Real-time graph rendering
* Interactive visualization support
* Better scalability for dense dynamic graphs

---

## License

This project is licensed under the MIT License.

---

## Author

### Shakibul Islam Akash

* GitHub: [https://github.com/ShakibulAkash](https://github.com/ShakibulAkash)
* AIUB, Bangladesh
