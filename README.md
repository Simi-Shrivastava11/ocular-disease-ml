# Ocular Disease Recognition using Machine Learning

This repository explores machine learning and deep learning approaches for recognizing ocular diseases from **retinal fundus images**. The project combines **exploratory data analysis**, **statistical analysis**, **image preprocessing**, and **CNN-based classification** using the **ODIR (Ocular Disease Intelligent Recognition)** dataset.

Originally completed as a collaborative graduate course project, this repository highlights the problem setting, methodology, and my contribution to the analysis and reporting workflow.

## Project Overview

Automated ocular disease screening can help support earlier diagnosis and more scalable medical workflows, especially when retinal image review is time-consuming and specialist availability is limited.

In this project, we used the **ODIR-5K dataset** to:
- study disease prevalence and demographic patterns
- preprocess retinal fundus images for modeling
- explore statistical relationships in the dataset
- train and evaluate a deep learning model for disease classification

The project combines structured data analysis with computer vision techniques to better understand both the **data patterns** and the **image-based classification task**.

## My Contribution

My primary contributions to this project included:

- performing **exploratory data analysis (EDA)** on the dataset
- proposing and testing hypotheses based on disease patterns
- creating visualizations to support the analysis
- contributing to interpretation and final reporting

## Dataset

This project uses the **Ocular Disease Intelligent Recognition (ODIR)** dataset, which includes:

- retinal fundus images
- patient demographic information such as age and gender
- diagnostic keywords and disease labels

The dataset supports analysis of multiple ocular conditions and enables both tabular analysis and image-based modeling.

## Project Objectives

The goals of this project were to:

- analyze a structured medical dataset to identify disease-related patterns
- preprocess retinal images for downstream modeling
- explore machine learning and deep learning approaches for disease recognition
- evaluate whether automated image-based classification can support ocular disease screening

## Methodology

### 1. Structured Data Analysis

The tabular portion of the project included:

- data cleaning and validation
- exploratory analysis of patient demographics
- disease distribution analysis
- hypothesis-driven statistical exploration
- creation of visualizations to support insights

### 2. Image Preprocessing

To prepare the retinal images for modeling, the project involved:

- quality assessment of images
- resizing and normalization
- blur detection and enhancement
- standardization for model input

### 3. Modeling

The classification component focused on **convolutional neural networks (CNNs)** for disease recognition from fundus images.

The broader project investigated the feasibility of deep learning for identifying ocular disease patterns and supporting image-based screening tasks.

## Repository Contents

- `Project_ocular_disease.ipynb` — main notebook containing analysis and modeling workflow
- `README.md` — project documentation

## Tech Stack

- **Python**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn**
- **scikit-learn**
- **TensorFlow / Keras or PyTorch** (depending on notebook implementation)

## Why This Project Matters

This project reflects an applied healthcare AI workflow that combines:

- real-world medical image data
- exploratory data analysis
- statistical reasoning
- image preprocessing
- deep learning for classification

For professor outreach, it shows experience with a research-style workflow involving hypothesis generation, analysis, and model evaluation. For recruiters, it demonstrates practical work in healthcare ML, computer vision, and end-to-end project communication.

## What I Learned

Through this project, I strengthened my understanding of:

- working with multimodal datasets containing both tabular and image data
- using EDA and statistical analysis to guide modeling decisions
- preprocessing medical imaging data
- applying CNN-based approaches to healthcare problems
- communicating technical findings through visualizations and written reporting

## Future Improvements

Potential next steps include:

- expanding the repo with a clearer results section and performance metrics
- adding sample visualizations and model outputs to the README
- separating preprocessing, training, and evaluation into reusable scripts
- exploring more advanced architectures and explainability methods such as Grad-CAM
- adding instructions for dataset download and reproducible execution

## Acknowledgment

This project was originally completed as part of a collaborative graduate course project. This repository reflects the project theme and my contribution to the analysis, visualization, and reporting components.
