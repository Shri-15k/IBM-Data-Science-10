# 📌 Applied Data Science Capstone

This Capstone project is the final course in the IBM Data Science Professional Certificate specialization. It applies all the skills and concepts learned throughout the specialization in a real-world scenario.

## 📄 Project Overview
SpaceX has revolutionized space travel by making it more cost-effective through reusable rocket technology. A Falcon 9 rocket launch costs approximately $62 million, significantly lower than other providers charging over $165 million per launch. The cost savings largely depend on the successful landing and reuse of the first-stage booster. The goal of this project is to predict whether the first-stage booster will successfully land, using machine learning techniques applied to publicly available data.

## 📄 Key Questions
- How do factors such as payload mass, launch site, number of flights, and orbit type impact the success of first-stage landings?
- Has the success rate of first-stage landings improved over time?
- Which machine learning algorithm is best suited for this binary classification problem?

## 📄 Methodology
### 1. Data Collection
- Extracting launch data from the SpaceX REST API
- Web scraping launch records from Wikipedia

### 2. Data Wrangling
- Filtering relevant data fields
- Handling missing values
- Encoding categorical variables using One-Hot Encoding for machine learning

### 3. Exploratory Data Analysis (EDA)
- Visualizing trends in launch data
- Querying data using SQL for deeper insights

### 4. Interactive Data Visualization
- Using **Folium** for geographical visualizations of launch sites
- Leveraging **Plotly Dash** to create interactive dashboards

### 5. Machine Learning for Prediction
- Building, tuning, and evaluating classification models
- Comparing models to determine the best performing one for predicting first-stage landings

## 📄 Tools & Technologies Used
- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly, Folium)
- **APIs & Web Scraping** (BeautifulSoup, Requests)
- **SQL** (for querying structured data)
- **Machine Learning Models** (Logistic Regression, Decision Trees, Support Vector Machines, and more)
- **Dash & Folium** (for interactive data visualization)

## 📄 Project Structure
```
|-- data/                 # Contains raw and processed datasets
|-- notebooks/            # Jupyter notebooks for analysis and model building
|-- models/               # Trained machine learning models
|-- app/                  # Interactive visualization using Dash
|-- README.md             # Project documentation
|-- requirements.txt      # List of dependencies
```

## 📄 Results & Insights
- Identified key factors influencing first-stage landings
- Observed an increasing trend in successful landings over time
- Determined the most effective machine learning model for prediction

## 📄 Conclusion
By leveraging data science and machine learning, this project provides insights into SpaceX's launch success, enabling better predictions and cost estimations for future missions.
