# Aviation Risk Analysis Project
![alt text](5a5b9102-e6b8-4938-bb62-0b02c104f099.jfif)

## Overview
This project analyzesrecent  historical aviation accident data to support data-driven aircraft acquisition decisions.
The goal is to identify aircraft types that present the lowest operational risk as the company expands into new ventures .

Using data from the National Transportation Safety Board (NTSB), this analysis evaluates accident frequency, severity, and contributing factors across aircraft categories, engine types, and weather conditions.


## Business Understanding

**Key Business Questions:**

1. Which aircraft categories(considering their make , model and engine types) have the lowest historical accident risk?
2. How does engine type influence accident severity?
3. What operational models and makes are associated with safer outcomes?

The answers to these questions inform strategic decisions around aircraft purchasing.

---

## Data Understanding and Analysis

### Data Source
* From the National Transportation Safety Board (NTSB)
* Aviation accidents and incidents (1962–2023)
* Extracted from Kaggle

### Data Description
- over 90,000 accident records
- 30+ variables including:
  - Aircraft category
  - Engine type
  - Operator type
  - Damage severity
  - Fatalities(minor , serious , fatal )
  - Geographic location
  - Event and publication dates
  - Weather conditions

### Data Preparation
Key cleaning steps included:
 ~ Removed duplicate records
~ Converted dates and numeric fields (from object data types)
~ Handled missing values with statistical imputation


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

*The link below leads to tableau public with an interactive dashboard with some of the visuals gotten from the data :: 