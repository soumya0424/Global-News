# GLOBAL-NEWS

_Classify, Explain, and Understand — News Intelligence with Machine Learning_

[![Last Commit](https://img.shields.io/badge/last%20commit-october%202025-black)]()  [![Jupyter Notebook](https://img.shields.io/badge/jupyter%20notebook-4.3%25-blue)]()  [![HTML](https://img.shields.io/badge/html-95.7%25-orange)]()  [![Languages](https://img.shields.io/badge/languages-2-blue)]()

Built with the tools and technologies:

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) ![LIME](https://img.shields.io/badge/LIME-green?style=flat)

---

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)

---

## Overview

Global-News is a machine learning project that classifies global news articles and explains the model's predictions using LIME (Local Interpretable Model-agnostic Explanations). It provides visual breakdowns of why the model made each classification decision.

### Why Global-News?

This project turns black-box classification models into interpretable, trustworthy systems. The core features include:

- 🌍📰 **News Classification**: Multi-class classification of global news articles by category.
- 🔍🧠 **LIME Explainability**: Per-prediction explanations showing which words influenced the model.
- 📊🧩 **Confusion Matrix**: Visual performance evaluation of the classifier.
- 🌐📊 **HTML Visual Outputs**: Interactive LIME explanation reports saved as standalone HTML files.
- 📈💬 **Model Evaluation**: Precision, recall, and F1-score analysis across news categories.

---

## Getting Started

### Prerequisites

This project requires the following dependencies:

- **Programming Language**: Python 3.8+
- **Packages**: `scikit-learn`, `lime`, `pandas`, `numpy`, `jupyter`

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/soumya0424/Global-News
   cd Global-News
   ```

2. **Install dependencies:**

   ```bash
   pip install scikit-learn lime pandas numpy jupyter
   ```

### Usage

```bash
jupyter notebook GN.ipynb
```

Open any `lime_explanation_sample_*.html` file in a browser to view per-prediction model explanations.
