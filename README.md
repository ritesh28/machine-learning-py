<p align="center">
  <a href="https://github.com/ritesh28/ml-dl-py" target="_blank">
    <img data-source="github" loading="lazy" alt="Machine Learning" src="https://github.com/ritesh28/ml-dl-py/raw/main/banner.png" width="750"/>
  </a>
</p>

# ML-DL-py

A curated collection of Python notebooks for Machine Learning (ML) and Deep Learning (DL) applications, covering end-to-end workflows, model development, experimentation, and deployment pipelines.

## Description

This repository contains a comprehensive collection of Python notebooks focused on Machine Learning (ML) and Deep Learning (DL) applications, workflows, and end-to-end pipelines. It includes practical implementations of data preprocessing, feature engineering, regression, classification, clustering, model training, evaluation, optimization, and deployment techniques using modern AI frameworks and libraries. From classical ML algorithms to advanced neural network architectures, the notebooks provide a structured and scalable approach to experimenting with AI and automation solutions.

## Project Structure

```
machine-learning-py/
├── source/         # ML code (.ipynb files)
├── data/           # Datasets
├── .gitignore
└── README.md
```

## Setup

1. Create conda environment:

```bash
conda create -n ml-env python=3.10
conda activate ml-env
```

2. Install packages as needed:

```bash
conda install jupyter pandas numpy scikit-learn matplotlib seaborn
```

3. Start Jupyter:

```bash
jupyter notebook
```

## Files

| Name                                                                          | Description                    | Tags                                 |
| ----------------------------------------------------------------------------- | ------------------------------ | ------------------------------------ |
| [classify-text.ipynb](source/classify-text.ipynb)                             | Text classification using ML   | Classification, ML, Naive Bayes      |
| [face-detection-pipeline.ipynb](source/face-detection-pipeline.ipynb)         | Face detection and recognition | feature extraction, negative dataset |
| [generate-new-data-using-gmm.ipynb](source/generate-new-data-using-gmm.ipynb) | Generate synthetic data        | Data Generation, Clustering, GMM     |
| [handwritten-digits.ipynb](source/handwritten-digits.ipynb)                   | Handwritten digit recognition  | Classification, MNIST                |
