# Pune-Smart-City-Environmental-Data-Analysis-2019
Exploratory Data Analysis of Pune Smart City Environmental Sensor Dataset (2019) to identify pollution hotspots, temporal trends, and data-driven environmental insights.

## 📌 Project Overview

This project analyzes the Pune Smart City Environmental Sensor Dataset (2019) to understand air pollution patterns, environmental behavior, and location-based risk factors.

The goal is to support data-driven environmental monitoring under the Smart City initiative by:

- Identifying pollution hotspots

- Understanding pollutant relationships

- Detecting peak pollution times

- Ranking high-risk locations

- Providing actionable recommendations

## 🏙 Problem Statement

Pune is experiencing increasing environmental challenges due to:

- Rapid urbanization

- Heavy traffic congestion

- Industrial and commercial growth

City authorities require structured environmental insights to:

- Monitor urban air quality

- Detect critical pollution zones

- Understand hourly and daily trends

- Take targeted corrective action

This project transforms raw sensor data into meaningful environmental intelligence.

## 📊 Dataset Information

Dataset Name: Pune Smart City Environmental Sensor Dataset (2019)
Source:

- Pune Smart City Development Corporation Limited (PSCDCL)

- IISc Bangalore

Dataset Structure

- 📈 103,205 Records

- 🧾 28 Features

- 🕒 Time-Series + Location-Based Sensor Data

Each row represents environmental readings recorded at a specific location and timestamp.

## 🧾 Feature Classification
#### 📍 Location Features

- Name

- Latitude

- Longitude

#### 🌫 Air Pollutants (AQI Drivers)

- PM2.5

- PM10

- NO

- NO₂

- SO₂

- CO

- CO₂

- Ozone

#### 🌦 Environmental Parameters

- Temperature

- Humidity

- Air Pressure

- Sound

- Light

- UV

#### ⏳ Time-Based Features

- Timestamp

- Hour

- Day

- Weekday

## 🧹 Data Cleaning & Preprocessing

The dataset was cleaned and prepared using the following steps:

- ✔ Handled missing values

- ✔ Removed zero and unrealistic sensor readings

- ✔ Treated outliers using IQR method

- ✔ Converted timestamp into meaningful time features

- ✔ Validated environmental parameter ranges

This ensured accurate and reliable analysis.

## 🔍 Exploratory Data Analysis (EDA)

The analysis answers 25 structured problem statements, including:

### 📈 Univariate Analysis

- Distribution of key pollutants (PM2.5, PM10, NO₂, CO)

- Environmental factor distributions

- Variability analysis across pollutants

### 🔗 Bivariate & Correlation Analysis

- Correlation heatmap of pollutants

- PM2.5 vs Temperature & Humidity

- Traffic-related pollution (CO, NO₂) vs Sound

- AQI priority parameter identification

### 🗺 Spatial Analysis

- Identification of pollution hotspots

- Most polluted locations ranking

- Stability vs fluctuation zones

- Location-based clustering

### ⏱ Temporal Analysis

- Hourly pollution trends

- Daily variation

- Weekday vs Weekend comparison

- Peak pollution time detection

## 🚨 Key Insights

- PM2.5 and PM10 are the most critical pollutants.

- Strong correlation between PM2.5 and PM10.

- CO and NO₂ indicate traffic-related pollution.

- Morning and evening hours show peak pollution.

- Certain transport hubs consistently show higher pollution.

- Some locations show unstable pollution patterns (risk zones).

## 🏆 Advanced Analysis

- Top 5 most polluted locations identified

- Safe limit exceedance analysis performed

- Pollution-based clustering using K-Means

- Early warning environmental indicators identified

## 🛠 Tools & Technologies Used

- Python

- Pandas

- NumPy

- Matplotlib

- Seaborn

- Scikit-learn (Clustering)

- Jupyter Notebook

- PowerPoint (Presentation)

## 🎯 Recommendations

Based on analysis:

- Focus monitoring on PM2.5 and PM10.

- Implement targeted traffic control in hotspot areas.

- Prioritize high-variability zones for intervention.

- Use time-based control measures during peak hours.

- Monitor early warning indicators for AQI spikes.

## 🌱 Conclusion

This project demonstrates the importance of data-driven environmental analytics in smart city governance.

By leveraging sensor data, authorities can:

- Detect pollution patterns early

- Identify high-risk zones

- Improve urban environmental planning

- Enhance public health outcomes
