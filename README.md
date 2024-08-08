# Weather Analysis of Telangana State 

## Description
This project involves scraping, analyzing, and modeling weather conditions across the entire state. The goal is to uncover patterns, predict future weather, and provide actionable insights.

## Table of Contents
- [Project Objectives](#project-objectives)
- [Data Collection](#data-collection)
- [Data Exploration and Cleaning](#data-exploration-and-cleaning)
- [Feature Engineering](#feature-engineering)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling](#modeling)
- [Model Evaluation and Tuning](#model-evaluation-and-tuning)
- [Deployment and Automation](#deployment-and-automation)
- [Documentation](#documentation)
- [Reporting and Presentation](#reporting-and-presentation)
- [License](#license)

## Project Objectives
- Identify weather patterns and trends.
- Predict future weather conditions using machine learning models.

## Data Collection
- **Source:** Telangana Open Data Website
- **Scraping Tool:** Python with BeautifulSoup and Requests [find the scraping process notebook here](weather_analysis_notebooks/webscrape.ipynb)
- **Data Details:** 
                Organisation: Telangana State Development Planning Society

                Data available from 01-01-2023 to 30-06-2024

                This dataset provides information about the cumulative rainfall, minimum & maximum temperature, humidity & wind speed across 
                all weather stations in the state of Telangana

                Metadata: 

                'District': Name of the district,
                'Mandal': Name of the Mandal,
                'Date': Date in yyyy-mm-dd format,
                'Rainfall (mm)': Cumulative Rainfall in mm, 
                'temp_min (⁰C)': Minimum Temperature in celcius,
                'temp_max (⁰C)': Maximum Temperature in celcius,
                'humidity_min (%)':Minimum Humidity %, 
                'humidity_max (%)': Maximum Humidity %,
                'wind_speed_min (Kmph)': Minimum Wind Speed in kmph,
                'wind_speed_max (Kmph)': Maximum Wind Speed in kmph. 
    [to find out more about the original data click here](https://data.telangana.gov.in/)

## Data Exploration and Cleaning
- Initial analysis and cleaning steps are documented in [find the notebook here](weather_analysis_notebooks/data_exploration_and_cleaning.ipynb).

## Feature Engineering
- Created features such as "season" and "temperature difference" to enhance model performance.

## Exploratory Data Analysis
- Visualizations and insights are provided in [notebooks/EDA.ipynb](weather_analysis_notebooks/EDA.ipynb)

## Modeling
- Models used: ARIMA, Random Forest, XGBoost
- Details of model training and validation are in [notebooks/Modeling.ipynb](weather_analysis_notebooks/Modeling.ipynb).

## Model Evaluation and Tuning
- Hyperparameter tuning and evaluation metrics are discussed in [notebooks/Modeling.ipynb](weather_analysis_notebooks/Modeling.ipynb).
## Deployment and Automation
- **Scripts:** Automated data scraping is handled by [find the scraping process notebook here](weather_analysis_notebooks/webscrape.ipynb)
- **Deployment:** yet to be added

## Documentation
- Code comments and Jupyter Notebooks provide detailed explanations.

## Reporting and Presentation
- Final report and visualizations are available in `YET TO BE ADDED`.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
