# 🚀Adult Income Machine Learning Project for Intel 

Welcome to the Adult Income Machine Learning Project. This project aims to analyze the Adult Census Income dataset and build a predictive model for income classification using Logistic Regression. The app also includes features for data visualization and an interactive chat interface for querying the dataset. 

  ### 🔗LIVE NOW- 
  #### Version 1: (Chat with Dataset working using Google AI)
  

##
The dataset used in this project is the [Adult Census Income dataset](https://archive.ics.uci.edu/dataset/2/adult). It is a public dataset provided by the UCI Machine Learning Repository, containing demographic information about individuals along with their income levels.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
   - [Data Overview](#data-overview)
   - [Visualizations](#visualizations)
   - [Prediction](#prediction)
   - [Chat with Dataset](#chat-with-dataset)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Running the App](#running-the-app)
6. [Important Notice: API and LangChain Considerations](#important-notice-api-and-langchain-considerations)


## 1. Project Overview 📝
The Project uses the Adult Census Income dataset to explore various demographic features and their relationships with income levels. The app provides a comprehensive set of tools for data analysis, visualization, and prediction.

## 2. Features 🛠️
### 1. Data Overview
Insert adult.csv dataset to proceed 

https://drive.google.com/file/d/1toTVZXSR3d0Vquna1p8DwjdL-8yvRBQT/view?usp=drive_link

Explore the dataset's structure, including summary statistics, missing values, and unique value counts for each feature

### 2. Visualizations 📊
Generate insightful visualizations such as correlation heatmaps, distribution plots, and more:
- Correlation Heatmap
- Age Distribution by Income
- Pie-Chart of Workclass Distribution
- Histograms and Boxplots for numerical features
And Many More!

### 3. Prediction 🎯
Predict income based on user-provided demographic information such as age, education, work hours, marital status, workclass, occupation, relationship, race, gender, and native country

### 4. Chat with Dataset 💬
Interactively query the dataset using natural language to get answers and visualizations based on your questions, utilising the power of Generative AI to provide answers to your questions. It is as simple as typing your query to get an answer!

## 3. Requirements
Ensure you have the following Python packages installed:
- streamlit
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- pandasai
- langchain_community
- python-dotenv
- google-generativeai

## 4. Installation 🛠️
Clone the repository:
```sh
git clone [https://github.com/yourusername/intel-ml-project.git](https://github.com/ArnuvRaina/Intel-ML)
cd Intel-ML
```
Install the required packages:

```sh
pip install -r requirements.txt
```

## 5. Running the App
To run the Streamlit app, execute the following command:
```sh
streamlit run app.py
```

  ### Example Queries
  Here are some example queries you can try in the "Chat with Dataset" section:
  
  -  List the top 5 most common native countries in the dataset.
  -  What is the average age of individuals based on their marital status?
  -  Show the top 5 oldest people with Private jobs and hourly weeks equal to 35 and are female.
  -  Show the distribution of income across different races.
  -  What is the percentage of people working in state gov jobs?
  -  Compare the income distribution between all genders.
  -  Do men or women tend to work longer hours per week on average, and how does this correlate with their income levels?
  -  Show age, workclass, occupation, and income of 5 males who work for 99 hours per week.
  -  How many individuals are in each relationship category (e.g., Husband, Wife, etc.)?  
  
 ### Note:
  - You can download the query output as a CSV file by clicking on the download button on the column header.
  - You can search for specific values within the output.
  - You can sort the results by tapping on the respective column headers.


## 6. Important Notice: API and LangChain Considerations

  ### API Reliability 🛠️
  
  The "Chat with Dataset" feature relies on the GenAI API (formerly GooglePalm), which may experience downtime or disruptions. In order to use this feature, you need to generate/obtain an API key from https://aistudio.google.com/app/apikey
  
  ### LangChain Deprecation ⚠️
  
  This application uses LangChain for integration with language models like GenAI. Please be aware that LangChain could undergo changes or be deprecated in the future. Stay updated with the [LangChain documentation](https://langchain.readthedocs.io/en/latest/) for compatibility and support information.
  
  For long-term reliability:
  - Update dependencies regularly and test with the latest versions.
  - Monitor GenAI API and LangChain repositories for updates and announcements.
  - Consider implementing fallback mechanisms for continuity in case of disruptions.
