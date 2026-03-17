# Amazon Product Recommendation System

This project builds a scalable **product recommendation system** using over **436,000 Amazon products**.

Users can search for a product and receive recommendations based on **product similarity and popularity signals**.

The system demonstrates an end-to-end machine learning pipeline including **data cleaning, feature engineering, recommendation modelling, and an interactive demo interface**.

---

## Project Overview

The recommendation pipeline consists of:

1. Data cleaning and preprocessing
2. Exploratory data analysis
3. Feature engineering using product text
4. TF-IDF vectorization
5. Fast similarity retrieval using Nearest Neighbors
6. Hybrid recommendation ranking
7. Interactive search and recommendation interface

---

## Dataset

Dataset: **Amazon Products Dataset (Kaggle)**  
https://www.kaggle.com/datasets/lokeshparab/amazon-products-dataset

Dataset size:

- **436,000+ products**
- 17 features including:
  - product title
  - category
  - description
  - price
  - rating
  - review count
  - image URL

The dataset is **not included in the repository** due to size.

---

## Dataset Setup (Kaggle API)

To download the dataset automatically:

### Step 1
Create a Kaggle account.

### Step 2
Go to: Kaggle → Account → API → Create New Token
This downloads a file: kaggle.json

### Step 3
Run the notebook and upload `kaggle.json` when prompted.
The dataset will download automatically.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Natural Language Processing (TF-IDF)
- Nearest Neighbors
- Matplotlib / Seaborn
- Jupyter Notebook
- ipywidgets (interactive demo)

## Interactive Demo

The notebook includes an interactive interface:

1. Search for a product
2. Browse search results with product images
3. Select a product
4. View recommended products


---

## Future Improvements

Possible improvements include:

- collaborative filtering using user behavior
- recommendation diversity optimization
- typo-tolerant semantic search
- deploying the system as a **Streamlit web application**

---

## Author

Tracy Nguyen  
MSc Artificial Intelligence and Data Analytics  
Loughborough University London
