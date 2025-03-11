# IBM-Applied-Data-Science-Capstone
This repository contains the work done for the Applied Data Science Capstone Project, offered by IBM on Coursera. It’s the final course in the IBM Data Science Professional Certificate program, providing an opportunity to apply the skills learned to a real-world data science problem.


# Applied Data Science Capstone Project

## Project Overview

This repository contains the work completed for the Applied Data Science Capstone Project, part of the IBM Data Science Professional Certificate series. The project is structured into multiple modules, each building on the previous one, culminating in a strong predictive model.

## Modules and Objectives

### 1. API Request and Data Preparation
- **Data Collection**: The project begins with a GET request to the SpaceX API to retrieve historical launch data. This data includes various parameters essential for analysis.
- **Data Cleaning**: After collecting the data, cleaning and formatting were performed to remove anomalies, handle missing values, and prepare it for analysis.

### 2. Web Scraping Falcon 9 Launch Data
- **Web Scraping**: Falcon 9 launch records were scraped from Wikipedia using the BeautifulSoup library, a powerful tool for web scraping in Python.
- **Data Parsing**: The HTML table extracted from Wikipedia was parsed and converted into a Pandas DataFrame for easier manipulation and analysis.

### 3. Exploratory Data Analysis (EDA) and Labeling
- **Exploratory Data Analysis (EDA)**: In-depth EDA was conducted using visualization tools such as Matplotlib and Seaborn to uncover patterns and correlations in the data.
- **Training Labels**: The training data was labeled to prepare for machine learning models, which is crucial for the modeling phase.

### 4. Database Integration
- **Loading Data into Db2**: The cleaned dataset was uploaded into a Db2 database, enabling structured querying and analysis with SQL.
- **Executing SQL Queries**: Various SQL queries were executed to derive insights and answer specific questions related to the launch data.

### 5. Feature Engineering and Visualization
- **Feature Engineering**: New features were created from the existing data to improve the predictive power of the models.
- **Geographical Visualization with Folium**: Interactive maps were generated using the Folium library to visualize launch sites and success/failure rates, helping to identify geographical patterns.

### 6. Interactive Data Analytics with Plotly Dash
- **Dash Application Development**: An interactive Plotly Dash application was built to allow real-time analysis of the SpaceX launch data.
- **User Interaction Features**: Features like dropdown menus and range sliders were incorporated to enhance user interaction with pie charts and scatter plots, making the analysis more intuitive and engaging.

### 7. Machine Learning Models and Tuning
- **Data Standardization and Splitting**: The dataset was standardized, then split into training and testing sets to ensure robust evaluation of the models.
- **Hyperparameter Tuning**: Hyperparameter tuning was performed using GridSearchCV on various models, including SVM, Classification Trees, and Logistic Regression.
- **Model Evaluation**: Each model was evaluated using test data to determine the best-performing model for predicting SpaceX launch success.

## Conclusion

This project allowed for the application of a wide range of data science techniques, from data collection and cleaning to advanced machine learning and interactive visualization. The final model is capable of predicting the success of SpaceX launches based on historical data, providing valuable insights for future launches.
