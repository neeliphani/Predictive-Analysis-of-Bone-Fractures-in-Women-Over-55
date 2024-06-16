Predictive Analysis of Bone Fractures in Women Over 55

This project identifies significant predictors of bone fractures in women aged 55 and above. By understanding these risk factors, healthcare providers can improve osteoporosis prevention and management strategies, potentially reducing healthcare costs and improving patient outcomes.

Narrative of Key Steps:

Data Collection and Preprocessing:

Data Sources: Collected data on 500 women, including variables like prior fractures, age, weight, height, BMI, and menopausal status.
Cleaning and Aggregation: Utilized R programming with dplyr for data manipulation and cleaning.

Exploratory Data Analysis (EDA):

Visualization: Used ggplot2 to create scatter plots and probability plots, visualizing relationships between variables.
Insights: Identified trends and outliers, focusing on prior fractures and need for arm assistance.

Model Building:

Logistic Regression: Applied logistic regression using the glm function to model the probability of fractures.
Feature Selection: Conducted residual analysis and variable significance testing to refine the model.

Model Evaluation:

Metrics: Assessed the model using statistical significance and goodness-of-fit tests.
Key Predictors: Found that prior fractures and arm assistance needs are the most significant predictors.

Results and Deployment:

Key Findings: Provided actionable insights for healthcare providers to focus on high-risk patients.
Business Value: Enhanced prevention strategies can lead to better patient care and reduced treatment costs.