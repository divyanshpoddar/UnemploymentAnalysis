# Unemployment Analysis in India During COVID-19👩🏽‍🔧

![Python](https://img.shields.io/badge/Python-3.8%2B-blue) 
![Pandas](https://img.shields.io/badge/pandas-1.2.4-orange)
![NumPy](https://img.shields.io/badge/numpy-1.19.2-orange)
![Matplotlib](https://img.shields.io/badge/matplotlib-3.3.4-orange)
![Seaborn](https://img.shields.io/badge/seaborn-0.11.1-orange)

## Project Overview

This project explores unemployment trends in India, with a special focus on the impact of the COVID-19 pandemic. By analyzing a dataset that spans both pre-lockdown and lockdown periods, the project reveals crucial insights into how different states were affected by the pandemic in terms of unemployment rates, labor participation, and workforce challenges.

## Dataset Information

- **Source:** The dataset used in this analysis was loaded from this GitHub repository also available on Kaggle.
- **Columns:**
  - `Region`: The state or region.
  - `Date`: The date of observation.
  - `Frequency`: Whether the data is monthly or otherwise.
  - `Estimated Unemployment Rate (%)`: The percentage of the unemployment rate.
  - `Estimated Employed`: The number of employed individuals in the region.
  - `Estimated Labour Participation Rate (%)`: The percentage of labor force participation.
  - `Area`: Whether the region is Rural or Urban.

## Data Analysis and Visualization

The analysis includes state-wise breakdowns of unemployment rates, labor participation, and employment trends. We also compare pre-lockdown and during lockdown unemployment trends to understand the impact of COVID-19 on the Indian economy.

### Key Insights

1. **COVID-19 Lockdown Impact:**
   - A sharp increase in the Estimated Unemployment Rate was observed during the lockdown, highlighting severe disruptions to the labor market.
   
2. **State-Wise Analysis:**
   - **Before the Lockdown:** Tripura, Haryana, and Himachal Pradesh had the highest unemployment rates.
   - **During the Lockdown:** Puducherry, Jharkhand, and Bihar showed the most significant rise in unemployment.
   
3. **Workforce Challenges:**
   - States like Uttar Pradesh, Maharashtra, and West Bengal consistently struggled to maintain a high Estimated Employed Workforce before and during the pandemic.
   
4. **Labor Participation:**
   - High labor participation was noted in Telangana, Tripura, Meghalaya, and Assam before the lockdown, while Meghalaya, Telangana, Tripura, and Andhra Pradesh maintained resilience during the lockdown.
   
5. **Correlation Analysis:**
   - A strong negative correlation between the Estimated Unemployment Rate and Estimated Employment was found in both pre-lockdown and lockdown periods, indicating the complex relationship between these two indicators.

### Data Wrangling Steps

1. Renamed the columns for clarity.
2. Converted `Date` to datetime format and extracted the month.
3. Handled missing values by removing rows with null values.
4. Created separate datasets for pre-lockdown and lockdown periods.
5. Performed data visualizations to better understand the relationships between variables.

### Visualizations

- **Region-wise Estimated Unemployment Rate:** Bar plots comparing pre-lockdown and during lockdown unemployment rates across states.
- **State-wise Estimated Unemployment Rate:** Swarm and bar plots to compare the state-wise unemployment rates before and during the lockdown.
- **Correlation Heatmaps:** Correlation analysis between unemployment, labor participation, and employment rates pre-lockdown and during lockdown.

## Libraries Used

- **Python:** ![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
- **Pandas:** For data manipulation and analysis. ![Pandas](https://img.shields.io/badge/pandas-1.2.4-orange)
- **NumPy:** For numerical operations. ![NumPy](https://img.shields.io/badge/numpy-1.19.2-orange)
- **Matplotlib:** For creating static, interactive visualizations. ![Matplotlib](https://img.shields.io/badge/matplotlib-3.3.4-orange)
- **Seaborn:** For statistical data visualization. ![Seaborn](https://img.shields.io/badge/seaborn-0.11.1-orange)

## Conclusion

This analysis highlighted the severe impact of the COVID-19 pandemic on India's labor market. States that had relatively lower unemployment before the pandemic, such as Haryana and Himachal Pradesh, saw a dramatic shift during the lockdown, while others like Puducherry and Jharkhand topped the list during the pandemic. The study underscores the importance of data-driven strategies to mitigate future economic challenges.

## How to Use This Project

1. Clone the repository:  
   ```bash
   git clone https://github.com/devgupta2619/Unemployment_Analysis.git
   ```

2. Install the necessary libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn
   ```

3. Run the Jupyter Notebook or Python script to see the analysis in action.

---
