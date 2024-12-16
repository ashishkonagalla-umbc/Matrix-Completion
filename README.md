# Matrix-Completion

## Project Overview

This project addresses the **Matrix Completion Problem**, a core challenge in recommendation systems, where missing entries in a user-item rating matrix are predicted to improve recommendations. The project implements and compares four advanced matrix completion techniques:

- **User-User and Item-Item Collaborative Filtering**: Predict ratings based on similarities between users or items.
- **Singular Value Decomposition (SVD)**: Uses matrix factorization to approximate the missing values.
- **Alternating Least Squares (ALS)**: Optimizes latent user and item factors alternately to minimize reconstruction error.
- **Nuclear Norm Minimization (NNM) with ADMM**: Enforces a low-rank structure using singular value thresholding.

### Key Features:
- Implementation of multiple matrix completion algorithms.
- Comprehensive evaluation and comparison of results.
- Ready-to-use scripts and notebooks for replicating the experiments.

### Metrics:
The performance of these methods is evaluated using:
- **Root Mean Squared Error (RMSE)** 
- **Mean Absolute Error (MAE)**





## How to Execute the Project

To run the project files, follow these steps:

### 1. Mount Google Drive
If you're using Google Colab or working with files stored in Google Drive, ensure you mount your Google Drive by adding the following lines at the start of your notebook:

from google.colab import drive
drive.mount('/content/drive')

### 2. Set the File Paths
Once Google Drive is mounted, update the file paths in the code to point to the correct locations in your drive. For example:

data_path = "/content/drive/MyDrive/YourProjectFolder/dataset.csv"
