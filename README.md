# PPI_Network_Multi_label_Node_Classfiaction

<p align="center">
<img src="https://img.shields.io/badge/scikitlearn-F7931E.svg?style&logo=scikit-learn&logoColor=white" alt="scikitlearn" />
<img src="https://img.shields.io/badge/Jupyter-F37626.svg?style&logo=Jupyter&logoColor=white" alt="Jupyter" />
<img src="https://img.shields.io/badge/YAML-CB171E.svg?style&logo=YAML&logoColor=white" alt="YAML" />
<img src="https://img.shields.io/badge/SciPy-8CAAE6.svg?style&logo=SciPy&logoColor=white" alt="SciPy" />

<img src="https://img.shields.io/badge/MLflow-0194E2.svg?style&logo=MLflow&logoColor=white" alt="MLflow" />
<img src="https://img.shields.io/badge/NumPy-013243.svg?style&logo=NumPy&logoColor=white" alt="NumPy" />
<img src="https://img.shields.io/badge/Markdown-000000.svg?style&logo=Markdown&logoColor=white" alt="Markdown" />
<img src="https://img.shields.io/badge/JSON-000000.svg?style&logo=JSON&logoColor=white" alt="JSON" />
</p>
</div>

---

## 📖 Table of Contents
- [📖 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [📦 Features](#-features)
- [📂 Repository Structure](#-repository-structure)
- [⚙️ Modules](#modules)
- [🚀 Getting Started](#-getting-started)
    - [🔧 Installation](#-installation)
    - [🤖 Running PPI_Network_Multi_label_Node_Classfiaction.git](#-running-PPI_Network_Multi_label_Node_Classfiaction.git)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)

---


## 📍 Overview

This project is aimed at performing multi-label node classification on a Protein-Protein Interaction (PPI) network. It leverages network embedding techniques to convert the network structure into a feature vector representation, which is then used to train a multi-label classification model. The project utilizes libraries such as NetworkX, Gensim, scikit-learn, and MLflow to facilitate data processing, model training, and experiment tracking.

---

## 📦 Features

- Network Embedding using Word2Vec.
- Multi-label Node Classification using Logistic Regression.
- Experiment tracking with MLflow.
- Interactive visualization of embeddings using t-SNE and Plotly.

---


## 📂 Repository Structure

```sh
└── PPI_Network_Multi_label_Node_Classfiaction.git/
    ├── README.md
    ├── mlruns/
    │   └── 0/
    ├── ppi-G.json
    ├── ppi-class_map.json
    ├── ppi-feats.npy
    ├── ppi-id_map.json
    ├── ppi-walks.txt
    └── ppi_node2vec_mlc.ipynb
```


---

## ⚙️ Modules

- `ppi_node2vec_mlc.ipynb`: Module for generating network embeddings using Word2Vec.
- `ppi_node2vec_mlc.py`: Module for training and evaluating the multi-label classification model.
- `ppi_node2vec_mlc.py`: Module for visualizing the embeddings and classification results.

---

## 🚀 Getting Started

***Dependencies***

Please ensure you have the following dependencies installed on your system:

`- ℹ️ python=3.11`

`- ℹ️ mlflow`

`- ℹ️ networkx`

`- ℹ️ numpy`

`- ℹ️ TSNE`

`- ℹ️ scikit-learn`

`- ℹ️ plotly`

`- ℹ️ pandas`

`- ℹ️ json`


### 🔧 Installation

1. Clone the PPI_Network_Multi_label_Node_Classfiaction.git repository:
```sh
git clone https://github.com/QsingularityAi/PPI_Network_Multi_label_Node_Classfiaction.git
```

2. Change to the project directory:
```sh
cd PPI_Network_Multi_label_Node_Classfiaction.git
```

3. Install the dependencies:
```sh
► INSERT-TEXT
```

### 🤖 Running PPI_Network_Multi_label_Node_Classfiaction.git

```sh
► ppi_node2vec_mlc.ipynb
```
---

## 🤝 Contributing

Contributions are always welcome! Please follow these steps:
1. Fork the project repository. This creates a copy of the project on your account that you can modify without affecting the original project.
2. Clone the forked repository to your local machine using a Git client like Git or GitHub Desktop.
3. Create a new branch with a descriptive name (e.g., `new-feature-branch` or `bugfix-issue-123`).
```sh
git checkout -b new-feature-branch
```
4. Make changes to the project's codebase.
5. Commit your changes to your local branch with a clear commit message that explains the changes you've made.
```sh
git commit -m 'Implemented new feature.'
```
6. Push your changes to your forked repository on GitHub using the following command
```sh
git push origin new-feature-branch
```
7. Create a new pull request to the original project repository. In the pull request, describe the changes you've made and why they're necessary.
The project maintainers will review your changes and provide feedback or merge them into the main branch.

---

## 📄 License

This project is licensed under the `ℹ️ MIT ` License. See the [MIT](LICENSE) file for additional info.

---

## 👏 Acknowledgments

`- ℹ️ This project build by Anurag Trivedi and code rebuild based on analysis give on node2vec paper examplea case study .`

[↑ Return](#Top)

---
