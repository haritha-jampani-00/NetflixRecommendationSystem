# Netflix Analytics Project
<img width="1025" height="578" alt="Screenshot 2025-09-26 at 10 37 41 PM" src="https://github.com/user-attachments/assets/4e11f75a-e428-4552-b95e-578e4a809b2c" />
<img width="1024" height="577" alt="Screenshot 2025-09-26 at 10 38 36 PM" src="https://github.com/user-attachments/assets/2feb9b43-9db0-41bd-b761-81e5f16611b0" />
<img width="1026" height="569" alt="Screenshot 2025-09-26 at 10 38 55 PM" src="https://github.com/user-attachments/assets/d3a9e84f-967d-4089-a5b5-79714597027c" />
<img width="1031" height="582" alt="Screenshot 2025-09-26 at 10 41 22 PM" src="https://github.com/user-attachments/assets/b9ce57e5-ddea-4741-8946-d435d394d8ab" />
<img width="1030" height="584" alt="Screenshot 2025-09-26 at 10 44 23 PM" src="https://github.com/user-attachments/assets/1452498e-f831-4aaa-85d3-cfd5877d5c35" />
<img width="1023" height="577" alt="Screenshot 2025-09-26 at 10 44 45 PM" src="https://github.com/user-attachments/assets/c032ef8d-01ca-45f0-9e68-1e07c6d6c289" />
<img width="1025" height="578" alt="Screenshot 2025-09-26 at 10 45 02 PM" src="https://github.com/user-attachments/assets/1b6a67d8-1723-418d-8956-f194af01a91b" />
<img width="1026" height="574" alt="Screenshot 2025-09-26 at 10 45 18 PM" src="https://github.com/user-attachments/assets/a4e78823-eb07-4e3d-b99c-bcc27e889075" />
<img width="1024" height="583" alt="Screenshot 2025-09-26 at 10 45 32 PM" src="https://github.com/user-attachments/assets/faa3f9bf-6dcd-448f-99cc-e3ede7e8676a" />
<img width="1023" height="576" alt="Screenshot 2025-09-26 at 10 45 56 PM" src="https://github.com/user-attachments/assets/e281283a-5f51-4b98-9eed-075336f08820" />
<img width="1027" height="579" alt="Screenshot 2025-09-26 at 10 46 12 PM" src="https://github.com/user-attachments/assets/6191ae5b-ef8e-4dae-910a-48f741652936" />
<img width="1024" height="578" alt="Screenshot 2025-09-26 at 10 46 28 PM" src="https://github.com/user-attachments/assets/e0dd4e4a-4576-4959-95cd-6196eff2ff37" />
<img width="1028" height="578" alt="Screenshot 2025-09-26 at 10 46 46 PM" src="https://github.com/user-attachments/assets/db9d7635-83ce-4d36-aa04-2c96666185d5" />
<img width="1026" height="578" alt="Screenshot 2025-09-26 at 10 47 01 PM" src="https://github.com/user-attachments/assets/080144bf-10aa-4354-88a2-ef24051e7af7" />
<img width="1026" height="576" alt="Screenshot 2025-09-26 at 10 49 10 PM" src="https://github.com/user-attachments/assets/62736bcb-69c5-4485-9ed2-6e372d053e8b" />









## Overview

This project involves analyzing Netflix data to gain insights and develop a content-based recommender system. The main steps include data preparation, exploratory data analysis (EDA), and building a recommender system using cosine similarity.

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Project Structure](#project-structure)
6. [Results](#results)
7. [Contributing](#contributing)
8. [Acknowledgements](#acknowledgements)

## Introduction

The Netflix Analytics project aims to provide insights into Netflix's content library and user preferences. By leveraging data preparation, EDA, and a content-based recommender system, this project showcases how data science techniques can be applied to streaming service data to enhance user experience.

## Features

- Data Preparation: Cleaning and preprocessing Netflix data.
- Exploratory Data Analysis (EDA): Visualizing and analyzing data to uncover patterns and insights.
- Recommender System: Implementing a content-based recommender system using cosine similarity.

## Installation

To get started with the project, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/your-username/netflix-analytics.git
cd netflix-analytics
pip install -r requirements.txt
```

## Usage

1. **Data Preparation**:
   - Load and clean the Netflix dataset.
   - Handle missing values and duplicates.
   - Normalize and preprocess data for analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Visualize data distributions and trends.
   - Analyze key metrics like genre popularity, release year distribution, and ratings.

3. **Recommender System**:
   - Build a content-based recommender system using cosine similarity.
   - Calculate similarity scores between content based on features like genres, directors, and cast.
   - Generate recommendations for users based on their viewing history.

To run the project, execute the main script:

```bash
python main.py
```

## Project Structure

```
netflix-analytics/
├── data/
│   └── netflix_titles.csv
├── notebooks/
│   ├── Data_Preparation.ipynb
│   ├── EDA.ipynb
│   └── Recommender_System.ipynb
├── src/
│   ├── data_preparation.py
│   ├── eda.py
│   └── recommender.py
├── main.py
├── requirements.txt
└── README.md
```

## Results

The project provides the following outputs:
- Cleaned and preprocessed Netflix dataset.
- Visualizations and insights from EDA.
- A functional content-based recommender system with recommendations based on cosine similarity.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## Acknowledgements

- [Netflix Data](https://www.kaggle.com/shivamb/netflix-shows) for providing the dataset.
- Python libraries like pandas, numpy, matplotlib, and scikit-learn for data manipulation and analysis.

---
