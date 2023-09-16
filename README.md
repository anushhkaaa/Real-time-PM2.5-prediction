# Real-time-PM2.5-prediction
## Overview
This project leverages the Seasonal Autoregressive Integrated Moving Average (SARIMA) algorithm to provide real-time predictions of PM2.5 levels across 34 major cities in India. These predictions are made at 4-hour intervals over a 24-hour period for three days (1st January to 3rd January, 2023), spanning three years of data collected during the Covid-19 pandemic. 
### SARIMA Algorithm
The Seasonal Autoregressive Integrated Moving Average (SARIMA) algorithm is a sophisticated time series forecasting method. It takes into account the seasonality and trend in the data, making it particularly well-suited for predicting PM2.5 levels, which exhibit recurring patterns and dependencies on time and weather conditions.

## Project Goals
- Develop a robust SARIMA-based forecasting model for accurate PM2.5 predictions.
- Provide real-time updates on PM2.5 levels, helping citizens make informed decisions about air quality.
- Analyze the impact of Covid-19-related restrictions on air quality trends across Indian cities.

## Key Features
- Real-time data collection and prediction.
- Interactive visualization of PM2.5 levels.
- Historical data analysis.
- Geospatial mapping of pollutant levels across Indian cities.

## Data Source
This project utilizes an extensive and comprehensive dataset encompassing three years of observations. The dataset includes a wealth of information across 40+ variables, such as PM2.5 and other emissions' measurements, meteorological factors, and demographic information of 34 Indian cities. The dataset used for this project has been sourced from the EXL EQ Case Study Challenge, 2023, ensuring the reliability and credibility of the information used in our predictions.

## Installation
To set up this project locally, follow these steps:
1. Clone the repository: `git clone https://github.com/anushhkaaa/Real-time-PM2.5-prediction.git`
2. Install the required Python libraries: `pip install -r requirements.txt`
3. Download the dataset and start working right away!

## Contribution Guidelines
Contributions to this project are welcome. If you'd like to contribute, please follow these guidelines:
1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature-name`
3. Make your changes and commit them: `git commit -m 'Add feature'`
4. Push to your forked repository: `git push origin feature-name`
5. Create a pull request to the main repository.

## Author Credits
- Arghadeep Mukherjee
- Anushka Biswas

## Disclaimer
Due to the huge size of the dataset and the CPU/GPU limitations of our systems on which we developed this project, the predictions for all the 34 cities could not be shown at once in a consolidated manner, but were instead shown individually, city by city. Manipulate the code as per the requirements to get all the predictions together. 

## Acknowledgments
We would like to thank EXL for providing the valuable data used in this project.

## Contact
For questions or inquiries, please contact [anushkaa.b28@gmail.com].
