# Midterm-Project
Team Members: 

	- Quoc Thach Nguyen
	- Franklin Anozie

## Project/Goals

	- Our midterm project aims to predict future weather trends, specifically the temperature, in Calgary, Canada, to inform jacket production strategy. Assume, as a sales manager for a jacket company, understanding whether the temperature will rise or fall in the coming years is pivotal. We specialize in season-specific apparel, producing winter jackets, light fall jackets, and spring sweaters. The objective is to align our production with the anticipated weather conditions to meet the city’s specific needs effectively.

## Process

### Step 1: Discussion on Logistics and Interests

	- Discuss Availability: Align team members’ schedules to set dedicated time for collaborative work.
	- Interest Exploration: Explore each team member's interests and expertise to leverage strengths.
	- Project Brainstorming: Begin brainstorming on how to approach the weather prediction and its impact on jacket production.

### Step 2:Finalize Problem Statement and Data

	- Problem Statement: Finalize the focus on predicting weather trends for Calgary, impacting jacket production.
	- Data Sources: Identify and confirm the datasets required for accurate weather predictions.
	- Repository Setup: Create a GitHub repository to store, manage, and share code and data.

### Step 3:Data Exploration and Initial Modeling

	- EDA: Clean and preprocess the data to prepare it for modeling.Conduct Exploratory Data Analysis to understand weather patterns and trends over the years in Calgary.
	- Model Development: Start models to predict future temperatures.

### Step 4:Dashboard Creation and Presentation Drafting

	- Data Visualization: Use Python libraries, Tableau to create visualizations showcasing predictions and insights.
	- Dashboard Development: Initiate the development of a dashboard to present the insights interactively.

## Results

### Insights from EDA:

	- During the Exploratory Data Analysis, we identified numerous instances of zero values in both temperature and precipitation columns. After careful consideration and analysis, we opted to retain these values as they are valid—temperatures and precipitation can indeed be zero, especially in colder climates like Calgary.

### Model Performance:

	- Initially, we employed a linear regression model to examine the correlation between the dependent variable (temperature) and the independent variable (precipitation). However, the resulting R-squared value was relatively low at approximately between 13% - 21%, indicating a weak explanatory power of the model.

	- Seeking to improve this, we experimented with various data transformation and scaling methods, including Log Transformations, StandardScaler, and Min-Max scaling. Despite these efforts, no significant improvement in the R-squared value was observed.

	- Given the limited success with linear regression, we transitioned to a more sophisticated modeling approach—ARIMA (AutoRegressive Integrated Moving Average). This model is renowned for its efficiency in handling time series data and offered a more promising avenue for predicting future weather patterns.

### Projected Weather Trends:

	-The temperature in the upcoming winter is expected to increase, as evidenced by the rise from -8.4°C in 2019 to -7.4°C in 2020.
	-Spring temperatures are forecast to decrease slightly, moving from 5.7°C in 2019 to 5.5°C in 2020.
	-The fall temperatures are predicted to increase, from 5.1°C in 2019 to 5.7°C in 2020.
    
## Challenges 

	- Encountered a low R-squared value in initial modeling, necessitating the exploration of advanced modeling techniques.
	- The constraint of time was a significant challenge.
	- We also faced limitations in resources.
	
## Future Goals

	- Refine the ARIMA model for enhanced predictive insights.
	- Explore additional variables and data sources for a comprehensive understanding of weather patterns such as wind speed, humidity, and, crucially, pollution indices can offer a more nuanced and comprehensive predictive model.
	