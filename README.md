# Machine-Learning-Exploratory-Data-Analysis-with-Python
This project explores a house sales dataset from King County, USA and builds regression models to predict house prices.   It was originally developed as part of a data analysis / machine learning lab and demonstrates an end-to-end workflow:  data loading → cleaning → exploratory data analysis (EDA) → model training → regularization.

## Objectives

- Explore the relationship between house features and sale price.
- Clean and preprocess a real-world dataset with missing values.
- Build and evaluate **linear regression** and **ridge regression** models.
- Experiment with **polynomial features** to capture non-linear relationships.

## Dataset

The dataset is loaded from the following source:

- `kc_house_data_NaN.csv` – House sales in King County, including prices and various property attributes.

The original dataset comes from an IBM Data Science course and is similar to the public King County House Sales dataset.

> **Note:** The CSV is not included by default.  
> You can download the dataset from the course resources or from a public King County housing dataset and adjust the file path in the notebook.

## Tools & Libraries

- **Language:** Python
- **Environment:** Jupyter Notebook (`.ipynb`)
- **Main libraries:**
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
  - `scikit-learn` (`LinearRegression`, `Ridge`, `PolynomialFeatures`, `train_test_split`)
