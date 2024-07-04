# Breast Cancer Detection

This project leverages machine learning to classify and predict breast cancer using the Wisconsin Breast Cancer dataset. The dataset is sourced from Kaggle and includes features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. The goal is to use these features to build a model that can accurately classify whether a tumor is benign or malignant.

## Dataset

The dataset can be obtained from Kaggle: [Wisconsin Breast Cancer Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data).

### Data Description

The dataset contains 569 instances with 30 numerical features describing the characteristics of the cell nuclei present in the images. The target variable indicates whether the tumor is benign (B) or malignant (M).

The features are:

- radius_mean
- texture_mean
- perimeter_mean
- area_mean
- smoothness_mean
- compactness_mean
- concavity_mean
- concave points_mean
- symmetry_mean
- fractal_dimension_mean
- radius_se
- texture_se
- perimeter_se
- area_se
- smoothness_se
- compactness_se
- concavity_se
- concave points_se
- symmetry_se
- fractal_dimension_se
- radius_worst
- texture_worst
- perimeter_worst
- area_worst
- smoothness_worst
- compactness_worst
- concavity_worst
- concave points_worst
- symmetry_worst
- fractal_dimension_worst

The target variable is:

- diagnosis (B = benign, M = malignant)

## Requirements

To run the project, you'll need the following libraries:

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook (optional, for interactive exploration)

You can install the required libraries using pip:

```sh
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
