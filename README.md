# MNIST Image Classification with Random Forest

## Overview
This repository contains a Jupyter Notebook (`your_notebook_name.ipynb`) that guides through the process of performing image classification on the classic MNIST dataset of handwritten digits (0-9) using a Random Forest Classifier from `scikit-learn`.

## Features
- Data extraction and preprocessing of the MNIST dataset.
- Image normalization for optimal model performance.
- Training a Random Forest Classifier for digit classification.
- Model evaluation using accuracy score and classification reports.
- Visualization of predicted vs. actual labels.

## Dataset
The project utilizes the `MNIST` dataset, a large collection of handwritten digits. The dataset files (`train-images-idx3-ubyte.gz`, `train-labels-idx1-ubyte.gz`, `t10k-images-idx3-ubyte.gz`, `t10k-labels-idx1-ubyte.gz`) are expected to be in the same directory as the notebook. These can be downloaded from [The MNIST Database](https://web.archive.org/web/20220331130319/https://yann.lecun.com/exdb/mnist/).

## Technologies Used
- Python
- NumPy
- scikit-learn (RandomForestClassifier, accuracy_score, classification_report)
- Matplotlib
- gzip

## How to Run
1.  **Clone the repository:**
    ```bash
    git clone https://github.com/YourGitHubUsername/mnist-image-classification-rf.git
    cd mnist-image-classification-rf
    ```
2.  **Download the MNIST data:** Download all four `.gz` files from [The MNIST Database](https://web.archive.org/web/20220331130319/https://yann.lecun.com/exdb/mnist/) and place them in the `mnist-image-classification-rf` directory.
3.  **Open the Jupyter Notebook:** Open the notebook in a Jupyter environment (e.g., Jupyter Lab, Google Colab) and run through the cells sequentially.

## Notebook Structure
The notebook is structured into several challenges:
- **Challenge 1: Extracting the data:** Loading and normalizing image data.
- **Challenge 2: Training the model:** Fitting a Random Forest Classifier.
- **Challenge 3: Testing the model:** Evaluating performance with accuracy and classification reports.

  Feel free to experiment with different parameters for the `RandomForestClassifier` or explore other classification models!
