# Heatwave Risk in India

## Project Title
**Heatwave Risk Prediction and Vulnerability Analysis in India**

## Introduction
Heatwaves are prolonged periods of excessively hot weather, which can have severe impacts on human health, agriculture, and the economy. With climate change, the frequency and intensity of heatwaves in India are increasing, posing significant risks to vulnerable populations.

## Description
This project analyzes heatwave risks in India by examining maximum temperatures, heatwave days, and reported casualties across multiple states. The objective is to understand patterns, identify high-risk states, and provide insights for climate risk management.

## Dataset
The dataset used is `heatwave_dataset.csv` containing the following columns:
- **Year**: Year of data record
- **State**: Indian state under observation
- **Max_Temperature_C**: Maximum temperature recorded (in Celsius)
- **Heatwave_Days**: Number of heatwave days in that year
- **Deaths_Reported**: Number of heatwave-related deaths

Example data:

| Year | State           | Max_Temperature_C | Heatwave_Days | Deaths_Reported |
|------|----------------|-------------------|---------------|-----------------|
| 2016 | Rajasthan      | 47.2              | 18            | 250             |
| 2021 | Odisha         | 46.5              | 16            | 200             |

## Steps in the Project
1. Import necessary libraries (pandas, matplotlib, seaborn)
2. Load dataset `heatwave_dataset.csv`
3. Explore dataset using `.head()`, `.info()`, `.describe()`
4. Visualize patterns (heatwave days by state, deaths by state, correlations)
5. Conclude insights on vulnerability and risk

## Conclusion
- States like **Rajasthan** and **Odisha** experience higher numbers of heatwave days and deaths.
- There is a positive correlation between maximum temperature, heatwave days, and casualties.
- Heatwave risks are intensifying with climate change and need effective management strategies.
