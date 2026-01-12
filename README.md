# AI/ML Lab Experiments

This repository contains various Artificial Intelligence and Machine Learning experiments and lab exercises, segregated by topic for easier understanding and execution. The experiments cover fundamental concepts using libraries like Numpy, Pandas, scikit-learn, and more.

## Repository Structure

The code is organized in the `ai_ml_lab_experiments` directory:

*   **`01_numpy_intro.py`**: Introduction to Numpy arrays, operations, and broadcasting.
*   **`02_pandas_intro.py`**: Basics of Pandas DataFrames, data loading, and manipulation.
*   **`03_ecommerce_analysis.py`**: Exploratory data analysis on an Ecommerce Purchases dataset.
*   **`04_logistic_regression_ads.py`**: Logistic Regression implementation for predicting purchases from Social Network Ads.
*   **`05_classification_pipeline_final_data.py`**: A comprehensive classification pipeline (Naive Bayes, KNN) with PCA visualization using the "Life Style" dataset.
*   **`06_knn_iris.py`**: K-Nearest Neighbors (KNN) classification on the Iris dataset.
*   **`07_naive_bayes_iris.py`**: Naive Bayes classification on the Iris dataset.
*   **`08_kmeans_iris.py`**: K-Means Clustering on the Iris dataset.
*   **`09_pca_iris.py`**: Principal Component Analysis (PCA) for dimensionality reduction on the Iris dataset.

## Prerequisites

To run these experiments, you will need Python installed along with the following libraries:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Datasets

Some scripts require specific datasets to be present in the same directory. You can download them from Kaggle using the links below:

| Script | Dataset Name | Link | Note |
| :--- | :--- | :--- | :--- |
| `02_pandas_intro.py` | Pokemon Dataset | [Link](https://www.kaggle.com/datasets/abcsds/pokemon) | Expects `pokemon_data.csv` |
| `03_ecommerce_analysis.py` | Ecommerce Purchases | [Link](https://www.kaggle.com/datasets/jmmvutu/ecommerce-purchases) | Expects `Ecommerce Purchases.csv` |
| `04_logistic_regression_ads.py` | Social Network Ads | [Link](https://www.kaggle.com/datasets/rakeshrau/social-network-ads) | Expects `Social_Network_Ads1.csv` |
| `05_classification_pipeline...` | Life Style Dataset | [Link](https://www.kaggle.com/datasets/aditya08/life-style-dataset) | Expects `Final_data.csv` |

*Note: You may need to rename the downloaded CSV files to match the filenames expected by the scripts, or update the script code to match your filenames.*

## Usage

Navigate to the experiment directory and run the desired script:

```bash
cd ai_ml_lab_experiments
python 01_numpy_intro.py
python 06_knn_iris.py
# etc...
```
