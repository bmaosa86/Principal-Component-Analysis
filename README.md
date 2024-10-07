# PCA and Logistic Regression for Cancer Dataset

## Overview
This project aims to analyze the breast cancer dataset using Principal Component Analysis (PCA) to identify essential variables for securing donor funding at the Anderson Cancer Center. Additionally, logistic regression is implemented to predict the malignancy of tumors based on the PCA-reduced dataset.

## Table of Contents
- [Introduction](#introduction)
- [Dataset Description](#dataset-description)
- [Installation](#installation)
- [Usage](#usage)
- [Implementation Steps](#implementation-steps)
  - [Step 1: Load the Dataset](#step-1-load-the-dataset)
  - [Step 2: Data Preprocessing](#step-2-data-preprocessing)
  - [Step 3: PCA Implementation](#step-3-pca-implementation)
  - [Step 4: Logistic Regression](#step-4-logistic-regression)
- [Results](#results)
- [Conclusion](#conclusion)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The Anderson Cancer Center is facing a growing number of referrals. This project utilizes PCA to reduce the complexity of the cancer dataset and help identify key features that can influence donor funding decisions. The logistic regression model provides predictions on tumor malignancy based on the PCA results.

## Dataset Description
The dataset used in this project is the breast cancer dataset available from the `sklearn.datasets` module. It contains various features about tumors, including radius, texture, perimeter, area, smoothness, and others. The target variable indicates whether the tumor is malignant (1) or benign (0).

## Installation
To run this project, ensure you have Python installed on your system. You can install the required libraries using pip. Here’s how to set it up:

1. Clone the repository or download the ZIP file.
2. Navigate to the project directory in your terminal.
3. Install the required dependencies:

```bash
pip install -r requirements.txt
