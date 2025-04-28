# IST 687 Introduction to Data Science - Sustainable Energy Usage Project

## Project Overview
This project focused on **analyzing and predicting energy consumption patterns** to assist eSC (an energy provider) in managing peak summer electricity demand without building new infrastructure.

- **Course:** IST 687 Introduction to Data Science
- **Author:** Abhi Chakraborty (Group 2)

---

## Project Goals
- Understand drivers of energy consumption during peak periods (July).
- Build predictive models for hourly energy usage.
- Simulate impacts of global warming (+5°C scenario).
- Provide actionable insights and tools (via Shiny app) for decision-makers.

---

## Project Steps

### Step 1: Data Preparation
- **Datasets:**
  - Static House Data
  - Energy Usage Data (per house, hourly)
  - Weather Data (hourly, per county)
- **Cleaning Process:**
  - Removal of NA values.
  - Aggregation of total electricity usage per building.
  - Joining weather and house data for complete feature sets.

---

### Step 2: Data Analysis
- **Key Variables Identified:**
  - Dry Bulb Temperature
  - Relative Humidity
  - Wind Speed
  - Solar Radiation Metrics (GHR, DHR, DNR)
- **EDA Insights:**
  - High correlation between temperature/humidity and electricity usage.
  - Peak usage observed in late afternoons.

---

### Step 3: Model Building
- **Initial Model:**
  - Linear regression on total electricity output.
  - Main predictors: Temperature, Humidity, Radiation metrics.
- **Model Improvement:**
  - Added interaction terms and squared temperature terms.
  - Introduced temporal features (hour, day, month).
  - Grouped by county and hour for refined accuracy.

- **Model Performance:**
  - R² = 67.49% (substantial explanatory power)

---

### Step 4: Predictions and Visualization
- **Peak Demand Prediction:**
  - Peak at 4:00 PM predicted for July.
- **Visualization Tools:**
  - Energy usage trends by county and time.
  - Interactive heatmap of temperature vs. humidity vs. energy output.

- **Shiny App:**
  - URL: [Energy Predict App](https://lmqz952567.shinyapps.io/energypredict/)
  - Allows custom prediction based on environmental inputs.

---

## Key Insights and Recommendations
- **Peak Demand Management:**
  - Target conservation efforts at peak hours (4 PM).
- **Energy Efficiency Programs:**
  - Deploy solar panel programs where DNR is high.
- **Customized Client Solutions:**
  - Use the Shiny app for tailored energy usage forecasting.
- **Policy Recommendations:**
  - Update building codes (better insulation).
- **Consumer Awareness:**
  - Run educational campaigns on peak load management.

---

## Tools and Technologies
- **Programming Language:** R
- **Libraries:** dplyr, ggplot2, lubridate, Shiny
- **Techniques:**
  - Regression Modeling
  - Time-Series Aggregation
  - Interactive Visualization

---

## Team Contributions
- Data Prep: Vaishnavi Meka, Hayden Wasserman
- Dataset Finalization: Abhi Chakraborty, Mengqi Li
- EDA and Visuals: Abhi Chakraborty, Mengqi Li
- Model Building: David Gold, Hayden Wasserman, Abhi Chakraborty
- Accuracy Improvement: Abhi Chakraborty
- Interpretation: Abhi Chakraborty, Mengqi Li, Hayden Wasserman
- Future Peak Demand: David Gold, Mengqi Li
- Visualization (Shiny): Mengqi Li
- Actionable Insights: Full Group Collaboration

---

## Author
**Abhi Chakraborty**  
Syracuse University - Applied Data Science  
Email: abchakra@syr.edu

