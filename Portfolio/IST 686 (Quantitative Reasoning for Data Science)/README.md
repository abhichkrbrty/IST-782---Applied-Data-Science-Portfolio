# IST 686 Quantitative Reasoning for Data Science - Vaccination Analysis Project

## Project Overview
This project involved a comprehensive analysis of **vaccination rates**, **socioeconomic factors**, and **reporting compliance** across California school districts to provide actionable public health insights.

- **Course:** IST 686 Quantitative Reasoning for Data Science
- **Author:** Abhi Chakraborty

---

## Project Goals
- Analyze trends and patterns in U.S. and California vaccination rates.
- Compare public vs. private school reporting compliance.
- Identify predictors for vaccination coverage and belief exceptions.
- Make data-driven recommendations for improving public health outcomes.

---

## Project Steps

### Step 1: Descriptive Reporting
- **U.S. Vaccination Trends:**
  - General improvement over time with minor cyclical variations.
  - Mean vaccination rate (recent years): ~88.5%.

- **California Vaccination Overview:**
  - Mean rates:
    - DTP: 88.7%
    - Polio: 89.4%
    - MMR: 90.2%
    - HepB: 91.1%
  - Strong correlation between vaccinations for different diseases.
  - California often exceeds U.S. averages slightly.

---

### Step 2: Public vs. Private Schools
- **Reporting Rates:**
  - Public schools: 85% reporting compliance.
  - Private schools: 65% reporting compliance.

- **Statistical Difference:**
  - Chi-Squared Test: Significant difference (p-value < 0.001).

- **County Variations:**
  - Example: Colusa County - 98.6% up-to-date; Calaveras County - 76.2% up-to-date.

---

### Step 3: Inferential Reporting
- **Predictors for Vaccination Coverage:**
  - **PctChildPoverty**: Negative impact on vaccination rates.
  - **Enrolled**: Positive impact on vaccination rates.

- **Best Predictors for Belief Exceptions:**
  - **PctFamilyPoverty** and **Enrolled**.

- **Interaction Effects:**
  - Larger districts mitigate negative effects of poverty on vaccination rates.

- **Predictors for Reporting Compliance:**
  - **PctChildPoverty:** Decreases likelihood of complete reporting.
  - **TotalSchools:** Increases likelihood of complete reporting.

---

## Tools and Techniques
- **Programming Language:** R
- **Statistical Methods:**
  - Time Series Decomposition
  - Linear and Logistic Regression
  - Chi-Squared Tests
  - Correlation Analysis
- **Visualization:**
  - Heatmaps and decomposition plots

---

## Key Observations and Lessons Learned
- Socioeconomic factors significantly influence vaccination rates and reporting.
- Larger, resource-rich districts perform better on both vaccination and reporting.
- Targeted interventions are needed for smaller, resource-constrained districts.

---

## Final Recommendations
- **Public Health Policy:**
  - Provide financial and outreach support to high-poverty districts.
  - Improve administrative support for small districts to enhance reporting.
- **Future Analyses:**
  - Conduct longitudinal studies to assess intervention outcomes.
  - Collect qualitative feedback from district administrators.

---

## Author
**Abhi Chakraborty**  
Syracuse University - Applied Data Science  
Email: abchakra@syr.edu

