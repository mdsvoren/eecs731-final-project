# EECS 731 - Final Project

Reducing clothing return rates by optimizing size recommendations.
https://www.kaggle.com/rmisra/clothing-fit-dataset-for-size-recommendation#renttherunway_final_data.json

## Team Members
* Andre Kurait
* Michael Svoren
* Melody Yu
* Daniel Zolotor
* Thor Lyche
* Alex Kunz

## Project Goal
Using a dataset from RentTheRunway which consists of customer reviews for various products, use data science techniques and machine learning models to derive value from the data in three ways:

1. Anomaly Detection - Remove misleading data and data which will substantially reduce the accuracy of and diminish the value of the following two models.

2. Classification - Determine if a certain size will fit, be too large, or be too small for a user, given their body type details.

2. Clustering - Recommend the most relevant products based on body type and purpose for shopping.


## Project Organization
```bash
.
├── README.md
├── data
│   ├── body_type_encoding.pkl
│   ├── bra_sizes.csv
│   ├── category_encoding.pkl
│   ├── rented_for_encoding.pkl
│   ├── reviews.pkl
│   ├── renttherunway_final_data.pkl
│   └── reviews_anomalies_removed.pkl
└── notebooks
    └── Feature_Engineering.ipynb
```


## Project code
The code exists on Jupyter notebooks in the notebooks folder. All the data is held in the data folder. A more detailed project organization is above.

### Installation
To run the python code, download the zip file of this project. The notebooks have embedded outputs of the code that was run previously on kernels.

### Models
Multiple SKLearn models for classification, anomaly detection, and clustering were used primarily in this project. Additionally, statistical methods such as the three sigma approach were employed.
