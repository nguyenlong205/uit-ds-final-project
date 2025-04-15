# [UIT@HealthQA] HCM Public Health Q&A Dataset

## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Acknowledgement](#acknowledgement)

## Overview
This GitHub repository includes a project in subjects - namely Data Collecting and Preprocessing, Computational Thinking for Data Science, and Statistical Machine Learning.


## Project Structure
```tex
building-dataset-project/
│
├── data/                   # Raw and processed dataset files
│   ├── raw/                # Original, unmodified data
│   │   └── building_data.csv
│   └── processed/          # Cleaned and processed data ready for analysis or model training
│       └── cleaned_data.csv
│
├── notebooks/              # Jupyter Notebooks for data exploration, cleaning, and analysis
│   ├── 01-data-exploration.ipynb
│   ├── 02-data-cleaning.ipynb
│   └── 03-modeling.ipynb   # If you're building predictive models (e.g., predicting building costs)
│
├── src/                    # Custom scripts for data processing, modeling, etc.
│   ├── __init__.py         # To mark the directory as a package
│   ├── data_preprocessing.py
│   ├── data_visualization.py
│   └── model.py            # If using machine learning or regression models
│
├── outputs/                # Output results (e.g., graphs, model predictions, etc.)
│   ├── visualizations/     # Plots and graphs
│   │   └── building_heights_distribution.png
│   └── predictions/        # Model output or analysis results
│       └── building_cost_predictions.csv
│
├── requirements.txt        # List of dependencies to replicate the environment
├── README.md               # Project documentation
└── LICENSE                 # License for the project (optional)

```

## Acknowledgement
I would like to express my heartfelt gratitude to the following individuals for their invaluable guidance and support throughout this course and project:
- Ph.D. Nguyen Gia Tuan Anh – Dean of the Faculty of Information Science and Engineering, UIT
- Teaching Assistant Tran Quoc Khanh – Faculty of Information Science and Engineering, UIT

Their expertise and encouragement were instrumental in helping us navigate challenges and achieve our objectives.

I would also like to extend my appreciation to my dedicated teammates for their significant contributions to the successful completion of this project:
- Dung Ho Tan, 23520327@gm.uit.edu.vn
- An Pham Dang, 22520027@gm.uit.edu.vn
