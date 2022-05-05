# Members

1. Ayushi Mundra
2. Jay Bhatt
3. Nehal Kathale
4. Shivashish Naramdeo

# Public URL

https://share.streamlit.io/ayushi1019/openaq-aws/main/main.py

# Dataset

_OpenAQ_

Global, aggregated physical air quality data from public data sources provided by government, research-grade and other sources.

# Business Problem

Air pollution is a global public health concern that kills more people each year than HIV/AIDS and malaria combined. According to the WHO, one out of every eightdeaths in the world is due to air pollution. Air pollution has various health effects. The health of susceptible and sensitive individuals can be impacted even on low air pollution days. Short-term exposure to air pollutants is closely related to COPD (Chronic Obstructive Pulmonary Disease), cough, shortness of breath, wheezing, asthma, respiratory disease, and high rates of hospitalization (a measurement of morbidity).

# Project Objective

Often, specific solutions to improving air quality are local and sustained through public engagement, policy and monitoring. Both the overarching science of air quality and health and local solutions rely on access to reliable, timely air quality data. Following are the some points which will discussed:

- Descriptive analysis of air pollution index of different countries.
- How the parameters in the dataset like CO2,CO,NO etc. affect different places?
- How these parameteres affected during COVID-19?
- Predict air quality based on historical data.

# Tech Stack

- AWS: S3, Quicksight, Sagemaker.
- Python
- Pandas
- PySpark
- Streamlit
- Plotly
- Altair
- Stats Model for Prediction

# Exploratory Analysis

It is a good practice to understand the data first and try to gather as many insights from it, that is called as Exploratory Analysis. We have used Pandas library to figure out the insights from our dataset. Code to our exploratory data analysis - [Exploratory data anlysis](openAQ-exploratory-analytics.ipynb)

# Dashboards

We have created our dashboard using AWS Quicksight as well as Plotly and Streamlit.
This is the folder to look for the Quicksight dashboards - [Quicksight Dashboard](Dashboard)

In order to run the streamlit app and view the graphs and charts, you'll need to run the following after cloning the repository-

```
pip install -r requirements.txt
```

```
streamlit run main.py
```
