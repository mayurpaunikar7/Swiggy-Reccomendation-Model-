# Swiggy Recommendation Model Project

## About the Project

In this project, I developed a recommendation model for aspiring restaurant owners looking to open a new restaurant in Bangalore using data scraped from Swiggy, a popular food delivery platform. The project involves data extraction, preprocessing, analysis, visualization, and the implementation of machine learning algorithms to provide insights and recommendations.

![alt text](https://github.com/mayurpaunikar7/Swiggy-Reccomendation-Model-/blob/main/Images/download.png)

## Project Overview

- **Objective**: Develop a recommendation model for restaurant owners in Bangalore.
- **Data Source**: Scrape data from Swiggy using Python.
- **Libraries Used**: NumPy, Pandas, Seaborn, Matplotlib.
- **Machine Learning Algorithms**: RandomForestRegressor, GradientBoostingRegressor.
- **Recommendation Model**: Predict preferred price and suggest a suitable location based on cuisine and price.

## Table of Contents

- [Project Details](#project-details)
- [Data Extraction](#data-extraction)
- [Data Preprocessing](#data-preprocessing)
- [Machine Learning Algorithms](#machine-learning-algorithms)
- [Webpage](#webpage)
- [Power BI Dashboard](#power-bi-dashboard)
- [Presentation](#presentation)
- [Usage](#usage)
- [Acknowledgments](#acknowledgments)

## Project Details

### Data Extraction

- Utilized Python to scrape data from Swiggy, collecting information in a specified format.
- Gathered restaurant details including cuisine, location, and price information.

### Data Preprocessing

- Cleaned and organized the scraped data for analysis.
- Prepared two tables using NumPy and Pandas for further analysis.

### Machine Learning Algorithms

- Applied RandomForestRegressor and GradientBoostingRegressor models.
- Utilized the models to predict preferred prices and suggest suitable locations.

### Webpage

- Created an interactive webpage for users to input cuisine, preferred location, and preferred price.
- Utilized Flask to build the user interface.
- Stored model predictions using Pickle.
- https://github.com/mayurpaunikar7/Swiggy-Reccomendation-Model-/blob/main/Web%20Page/web.html
![alt text](https://github.com/mayurpaunikar7/Swiggy-Reccomendation-Model-/blob/main/Images/%7BE4DA319D-1E2C-473F-B66E-80D5E4749D7E%7D.png)

### Power BI Dashboard

- Developed a Power BI dashboard to visualize data insights and model predictions.
- Visualizations include popular cuisine, average price, most popular restaurant, and more.
![alt text](https://github.com/mayurpaunikar7/Swiggy-Reccomendation-Model-/blob/main/Images/Dashboard.jpeg)

### Presentation

- Prepared a presentation summarizing the project's objectives, methods, findings, and recommendations.

## Challenges Faced

- **Data Collection**: Gathering and cleaning data from Swiggy required web scraping techniques, handling dynamic content, and managing data quality.

- **Algorithm Complexity**: Developing a recommendation algorithm that considers multiple factors while ensuring scalability and real-time performance was challenging.

- **User Engagement**: Encouraging users to engage with the recommendation system and provide feedback for continuous improvement.

## Insights Derived

- **Personalized Recommendations**: The recommendation model provides personalized restaurant suggestions based on user preferences, determines best location for opening restaurent.

- **User Engagement**: Analyzing user interactions with recommended restaurants and tracking user feedback helps refine the recommendation algorithm.

- **Restaurant Insights**: By analyzing user preferences, restaurant owners can gain insights into customer preferences, leading to menu optimization and targeted promotions.

## Future Scope

- **Enhanced Personalization**: Incorporate machine learning techniques such as collaborative filtering and deep learning to enhance recommendation accuracy.

- **User Feedback Loop**: Implement a feedback mechanism to capture user preferences and continuously update the recommendation model.

- **Geo-Location Integration**: Integrate real-time location data to recommend nearby restaurants and delivery options.

- **Market Expansion**: Extend the recommendation system to other cities and regions to reach a broader user base.

## Usage

1. Clone this repository to your local machine.
2. Explore the Jupyter Notebook (https://github.com/mayurpaunikar7/Swiggy-Reccomendation-Model-/blob/main/Ml%20Model/ml_project.ipynb) to understand the data analysis process and machine learning implementation.
3. Check out the interactive webpage by running the Flask application.
4. Explore the Power BI dashboard for visualized insights.
5. Review the presentation for a comprehensive overview of the project.

For inquiries or feedback, feel free to reach out.

## Acknowledgments

I would like to express my sincere gratitude to the following individuals:

- **Mentor**: Rishabh Sengar for his invaluable guidance, continuous support, and insightful feedback throughout the project.
- **Team Members**: Saurav Kumar, Aditya Tomar, and Saikiran Chakala for their collaboration, contributions, and teamwork, which enriched the project significantly.

Your encouragement and expertise were instrumental in making this project a success. Thank you for your time, knowledge, and dedication.




