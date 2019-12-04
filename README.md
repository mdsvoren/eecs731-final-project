# Final Project

Reducing clothing return rates by optimizing size recommendations.
https://www.kaggle.com/rmisra/clothing-fit-dataset-for-size-recommendation#renttherunway_final_data.json

## Project Organization
```bash
.
├── README.md
├── data
│   ├── body_type_encoding.pkl
│   ├── bra_sizes.csv
│   ├── category_encoding.pkl
│   ├── rented_for_encoding.pkl
│   ├── renttherunway_final_data.json
│   ├── renttherunway_final_data.pkl
│   └── reviews.pkl
└── notebooks
    └── Feature_Engineering.ipynb
```

## Project Foci
* Classification - User puts in data and we'll return whether we think the product will fit them, be too small, or be too large. - Thor and Alex
* Martin recommended thinking about should RentTheRunWay not recommend certain projects (if similar people report different fits, then we might not want to reccommend this to others because return rate is likely higher) - grouped under Clustering
* Anomaly Detection - Use to clean data of user typos - Daniel and Melody
* Clustering - Recommend products that are for similar occassions and are recent (date) - Michael and Andre

## Notes from Martin
* Mention things that we considered, but didn't do.
* Discuss why we chose each in depth
* 20 - 25 minutes presentation 