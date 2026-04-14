# Prognostica Market Insights: Early Lung‑Cancer Risk Detection Using Cloud‑Based Machine Learning

<img width="1000" height="600" alt="68747470733a2f2f63646e2e63616e63657263656e7465722e636f6d2f2d2f6d656469612f637463612f696d616765732f666561747572652d626c6f636b2d696d616765732f6d65646963616c2d696c6c757374726174696f6e732f6c756e672d63616e6365722d696c6c757374726174696f6e2d666561" src="https://github.com/user-attachments/assets/0ec89b8f-137b-4c9b-af84-8d1e72485d70" />

# Installation

1. Clone this repository inside SageMaker Studio

    cd ~/SageMaker

    git clone https://github.com/clynch1086/ads-508-prognostica-project.git

    cd ads-508-prognostica-project


2. Open the notebooks

    In SageMaker Studio, open the notebooks and run them in order:

       01_cancer_data_ingestion_exploration.ipynb   

       02_data_preprocessing.ipynb

       03_training_evaluation.ipynb
   

# Contributors

- Celina Velazquez 

- Christopher Lynch

- Danitza Loya
  
# Abstract

We aim to design a cloud-based data science solution that helps the company identify patterns and insights within large datasets to improve operational decision-making. Using publicly available datasets and AWS cloud technologies, the team will explore, prepare, and analyze data to develop a predictive model that addresses a key business challenge. Prognostica operates in multiple markets and will focus on the cancer market for this project. 

# Problem Statement

Many organizations struggle to convert large volumes of raw data into actionable insights that improve business performance. As companies grow and collect more data, identifying trends, predicting outcomes, and making data-driven decisions becomes increasingly difficult without scalable analytical tools. 


This project proposes building a cloud-based data science pipeline using AWS services to analyze publicly available datasets and develop predictive insights that can support business decision-making. By leveraging cloud storage, scalable data processing, and machine learning tools such as Amazon SageMaker, the company will be able to transform raw data into meaningful insights that improve efficiency, reduce risk, or increase revenue depending on the selected business case. 

Prognostica provides market insights for B2B companies in various markets. Cancer medicine spending is expected to reach $441 B by 2029 (Global Oncology Trends 2025, 2025). To address this need, Prognostica will conduct a project to determine cancer trends and identify personas of affected persons to inform marketing and market strategies for Prognostica’s customers. 

# Goals

- Develop a scalable data pipeline capable of ingesting large datasets into AWS cloud storage. 

- Explore and analyze the data to identify trends, relationships, and potential predictive variables. 

- Prepare the data for machine learning training through data cleaning, transformation, and feature engineering. 

- Train and evaluate a predictive model using AWS SageMaker to generate insights relevant to the business problem. 

# Non-Goals

- Building a fully productionized enterprise system with real-time deployment. 

- Developing a user-facing web application or dashboard interface. 

- Implementing multiple competing machine learning models beyond the scope required for the project. 

# Data Sources

The data collected from multiple public sources: 

- Kaggle - Lung Cancer Dataset

  https://www.kaggle.com/datasets/chandanmsr/lung-cancer-dataset 

- CDC Wonder- U.S. Cancer Statistics (2001-2022)

  https://wonder.cdc.gov/cancer-v2022.html 

- Global Oncology Trends 2025 - IQVIA

  https://www.iqvia.com/insights/the-iqvia-institute/reports-and-publications/reports/global-oncology-trends-2025 


- EOA TRI program - Dioxin and TEQ data files. 

  https://www.epa.gov/toxics-release-inventory-tri-program/tri-dioxin-and-dioxin-compounds-and-teq-data-files-calendar 

# Presentation

https://www.loom.com/share/d1bd121f2e28451bbfe2fce850f384d8
