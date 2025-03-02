This Capstone project is the final course in the IBM Data Science Professional Certificate specialization. It consolidates all the skills learned throughout the specialization into a practical, hands-on project.

📄 Project Overview

SpaceX has revolutionized the commercial space industry by making space travel more affordable. The Falcon 9 rocket, which costs approximately $62 million per launch, significantly reduces costs compared to other providers charging around $165 million per launch. A key factor in cost reduction is reusability, specifically the successful landing of the first stage.

The objective of this project is to predict the likelihood of the first-stage landing using machine learning models. By analyzing publicly available data, we aim to understand the factors influencing reusability and determine the most effective classification algorithm.

📄 Research Questions

How do variables such as payload mass, launch site, number of flights, and orbits affect the success of the first-stage landing?

Does the rate of successful landings increase over the years?

Which classification algorithm is best suited for predicting first-stage landing success?

📄 Methodology

1. Data Collection

Extracted launch data using SpaceX REST API

Performed web scraping from Wikipedia for historical launch details

2. Data Wrangling

Cleaned and filtered relevant data

Handled missing values to ensure data integrity

Applied One-Hot Encoding to prepare data for binary classification

3. Exploratory Data Analysis (EDA)

Conducted visual and statistical analysis to identify key patterns

Used SQL for querying and summarizing the dataset

4. Interactive Visual Analytics

Developed interactive dashboards using Folium and Plotly Dash

Mapped launch sites and success rates visually

5. Predictive Modeling

Built and fine-tuned classification models to predict landing success

Compared different algorithms to select the most accurate model

📄 Technologies Used

Python (Pandas, NumPy, Scikit-Learn, BeautifulSoup, Requests)

SQL for querying structured data

Folium & Plotly Dash for interactive visualizations

Machine Learning (Logistic Regression, Decision Trees, Random Forest, SVM)

Jupyter Notebook & Google Colab for development and experimentation

📄 Conclusion

This project demonstrates the power of data science and machine learning in analyzing real-world problems. By predicting SpaceX first-stage reusability, we provide valuable insights into cost reduction strategies for space exploration.
