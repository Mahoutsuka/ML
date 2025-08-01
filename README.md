# World_Happiness_Prediction
This project builds a machine learning model to **predict a country's happiness score (Life Ladder)** for the following year (2012-2017) based on historical trends and socioeconomic factors. The goal is to explore how features like GDP, social support, and life expectancy influence national well-being as well as how these patterns evolve over time.


## 📌 Problem Statement

How can we predict **next year's happiness score** using data from previous years?

Using the **World Happiness Report** data, we aim to build a **time-aware regression model** that learns from past values to forecast future trends.


## 🧠 Key Features & Approach

- **Label:** Next year's *Life Ladder* score for each country
- **Input Features:**  
  - GDP per capita  
  - Social support  
  - Healthy life expectancy  
  - Freedom to make life choices  
  - Generosity  
  - Perceptions of corruption  
  - Confidence in national government  
  - Positive and negative affect measures
  
- **Time-Series Engineering:**  
  - Shifted label by -1 year to predict future  
  - Winsorized outliers **per country** for robustness  
  - Feature scaling and normalization per country  



## 🧪 Models Used

- **Multilayer Perceptron (MLP)**
- Evaluation using **mean absolute error**


## 🛠️ Tech Stack

- Python 🐍  
- pandas  
- NumPy  
- scikit-learn
- Keras 
- matplotlib / seaborn 
