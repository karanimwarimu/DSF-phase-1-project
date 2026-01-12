# Aviation Risk Analysis Project
![alt text](5a5b9102-e6b8-4938-bb62-0b02c104f099.jfif)

## Overview
This project analyzes historical aviation accident data to support data-driven aircraft acquisition decisions. The primary objective is to identify aircraft types that demonstrate lower operational risk, helping guide the company’s expansion into new aviation ventures.

Using data from the National Transportation Safety Board (NTSB), the analysis examines accident frequency, severity, and contributing factors across multiple dimensions, including aircraft category, make and model, engine type, and weather conditions.


## Business Problem

Aircraft acquisition represents a significant capital investment, where safety performance is a critical decision factor. Understanding historical accident patterns helps reduce exposure to operational, financial, and reputational risk.

This analysis addresses the following business-driven questions:

* Which aircraft categories, considering make, model, and engine type, exhibit the lowest historical accident risk?

* How does engine type influence accident severity, including fatal and non-fatal outcomes?

* Which aircraft makes and operational models are consistently associated with safer outcomes?

* The insights generated are intended to support strategic fleet planning, procurement decisions, and risk mitigation efforts.


## Data Source

Provider: National Transportation Safety Board (NTSB)

Dataset: Aviation Accident and Incident Data

Time Period: 1962–2023

Access Method: Kaggle


## Data Description

The dataset contains over 90,000 aviation accident and incident records, with more than 30 variables describing aircraft characteristics, operational context, and accident outcomes.

Key variables include:

* Aircraft category

* Aircraft make and model

* Engine type

* Operator type

* Damage severity

* Injury outcomes (minor, serious, fatal)

* Geographic location

* Event and publication dates

* Weather conditions at the time of the event


## Data Preparation

To ensure analytical reliability and consistency, the following preprocessing steps were performed:

* Removal of duplicate records

* Standardization and conversion of date and numeric fields from object data types

* Handling of missing values using appropriate statistical imputation techniques

* Validation of categorical fields to ensure consistent labeling

These steps ensured a clean and structured dataset suitable for exploratory and comparative analysis.


### Analysis Approach

The analysis focuses on identifying safety trends and risk patterns by:

Comparing accident frequency across aircraft categories and engine types

Evaluating accident severity distributions by aircraft make and model

Assessing the impact of operational and environmental factors, such as weather conditions

Highlighting aircraft configurations associated with lower historical risk


### Key Outcomes

The results of this analysis provide:

A comparative safety profile of aircraft categories and engine types

Evidence-based insights into safer aircraft makes and operational models

Actionable guidance to support aircraft acquisition and risk management decisions


### Tools and Technologies

* Python

* Pandas & NumPy for data manipulation

* Matplotlib & Seaborn for visualization

* Jupyter Notebook for exploratory analysis
---

## Key Visualizations

### 1. Acciddent Distribution According to Weather conditions 
This visualization shows that most aircraft accidents occur during normal weather conditions. Faulty instruments and plane gaugues might not be the case.
So pilot decisions and experience contribute to most accidents. 

### 2. Top 50 Aircraft Makes by Total Accidents
Some of the makes with less  accidents include : 
    * Zilz
    * zukowaski
    * Zwart
    * drone
    * Zlin Aviation

### 3.  Top 50 Aircraft Models by Total Accidents
Some of the models with less  accidents include : 
    * Zenith CH-701 
    * zodiac 
    * Zodiac CH-601-H
    * Zodiac CH601XL
    * Sportstar

### 4.  AIRCRAFT (MAKE AND MODEL) AND ACCIDENT OCCURENCE CONCLUSION

The aircraft with the highest uninjured count was : 
 * MCDONNEL DOUGHLAS | DC9
 
There were several  aircrafts  with very few uninjured which include : 
   * Cesna | 140 
   * Cesna | 4018
   * Piper | 94-28-161
   * Beech | V358
   * Cesna | 172
   * Cesna | 150L
   * Bell  | 206L
   * Piper | 24-180


## Conclusion

### Key Findings:
1. Pilot decisions and experience contribute to most accidents. 
2. Modern Aircraft makes and models with newer engine make technologies are associated with reduced accident severity.
3. Commercial aviation frameworks provide safer operational environments.

### Business Recommendation:
The company should prioritize multi-engine, turbine-powered aircraft and operate under commercial aviation standards when entering the aviation market.


### Interactive Dashboard 
* Under visualizations folder ou will get the interactive dashboard
*The link below leads to tableau public with an interactive dashboard with some of the visuals gotten from the data ::
     https://public.tableau.com/views/AirlineDashboard_17662150490000/Dashboard1?:language=enUS&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
