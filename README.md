# Heart and Diabetes Disease Detection

This repository contains Jupyter Notebooks and resources for detecting heart disease and diabetes using machine learning techniques. The objective is to help in early diagnosis by leveraging data-driven models built on publicly available healthcare datasets.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Datasets](#datasets)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Early detection of heart disease and diabetes is critical for effective treatment and management. This project applies various machine learning algorithms to predict the likelihood of these diseases based on health indicators. All experiments and results are documented in Jupyter Notebooks.

## Features

- Data preprocessing (cleaning, normalization, feature selection)
- Exploratory Data Analysis (EDA)
- Model training using algorithms such as Logistic Regression, Decision Trees, Random Forests, etc.
- Model evaluation with accuracy, precision, recall, F1-score, ROC curves
- Interactive visualizations
- Separate notebooks for heart disease and diabetes detection

## Datasets

- **Heart Disease:** [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
- **Diabetes:** [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

> _Please download the datasets from the provided links and place them in the `data/` directory._

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/Jaspinder26/Heart-and-Diabetes-Disease-Detection.git
    cd Heart-and-Diabetes-Disease-Detection
    ```

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```
    Or, set up via Jupyter Notebook:
    ```python
    # In a notebook cell
    !pip install -r requirements.txt
    ```

## Usage

1. Ensure the datasets are present in the `data/` folder.
2. Open the desired notebook:
    - `Heart_Disease_Detection.ipynb`
    - `Diabetes_Detection.ipynb`
3. Run the cells step by step to explore the data, train models, and evaluate results.

## Project Structure

```
Heart-and-Diabetes-Disease-Detection/
├── data/
│   ├── heart.csv
│   └── diabetes.csv
├── Heart_Disease_Detection.ipynb
├── Diabetes_Detection.ipynb
├── requirements.txt
└── README.md
```

## Results

- **Heart Disease Model:** _[Add your best achieved metrics here, e.g., 85% accuracy, ROC AUC, etc.]_
- **Diabetes Model:** _[Add your best achieved metrics here.]_

## Contributing

Contributions, issues and feature requests are welcome!  
Feel free to check the [issues page](https://github.com/Jaspinder26/Heart-and-Diabetes-Disease-Detection/issues).

## License

This project is [MIT](LICENSE) licensed.

---

**Note:** _This project is for educational and research purposes only and should not be used for actual medical diagnosis without validation by healthcare professionals._
