# Real Estate Market Analysis in New York

## Introduction

This comprehensive project leverages advanced predictive analytics to forecast real estate price trends across New York's diverse zip codes. It aims to provide strategic insights for informed investment decisions in the dynamic New York real estate market.

## Business Problem

We are engaged by a leading real estate investment firm, known for its strategic and data-driven approach to the New York property market. The firm seeks to continue its legacy of high-return investments by identifying promising real estate opportunities. The key question is: Can we predict the future trends of property prices in New York's diverse zip codes using historical data?

## Data Overview

We utilize an extensive dataset from Zillow, covering April 1996 to April 2018. This dataset includes critical variables such as RegionID, RegionName (zip codes), and median property values, providing a comprehensive view of the New York real estate landscape.

## Project Approach

1. **Data Preparation & Cleaning**: Standardizing data formats and handling missing data for accurate analysis.
2. **Exploratory Data Analysis (EDA)**: Investigating underlying trends and characteristics of the New York real estate market.
3. **Stationarity Testing & Data Transformation**: Applying statistical tests and transformations to prepare data for time series modeling.
4. **Model Development & Forecasting**: Building ARIMA models for each zip code to forecast future real estate prices and evaluating model performance.
5. **Risk Analysis and Cross-Validation**: Implementing strategies to enhance model reliability and integrate risk metrics.

## Technical Aspects

- Languages & Libraries: Python, Pandas, NumPy, Matplotlib, Seaborn, Statsmodels.
- Techniques: Time Series Analysis, ARIMA Modeling, Data Visualization.

## Key Insights

1. **Market Variability**: Distinct growth rates and risk profiles across various zip codes.
2. **Model Precision**: Varied levels of forecasting accuracy; some zip codes offer more reliable predictions.
3. **Investment Opportunities**: Identification of potential investment areas based on growth prospects and risk analysis.

## Results & Interpretation
- **Model Outputs**: In-depth results from ARIMA models for each zip code.
- **Financial Crisis Impact**: Visual depiction of the real estate market's response to economic downturns, highlighting pivotal trends and recovery phases.
  
## Recommendations
Based on ARIMA model forecasts, the project suggests top zip codes for investment, balancing potential growth against associated risks.
   - Top 5 Zip Codes for Investment
**11231**
   - **Profitability**: Strong growth (8.01% growth percentage).
   - **Risk**: Low (3.61% future risk).
       - Ideal for those seeking growth with low risk.

**11211**
   - **Profitability**: Significant growth (9.0% growth percentage).
   - **Risk**: Moderate (8.52% future risk).
       - Balanced choice for growth-focused investors.

**11930**
   - **Profitability**: Good growth (5.55% growth percentage).
   - **Risk**: Moderate (5.25% future risk).
       - Suitable for medium-term investment strategies.

**11215**
   - **Profitability**: Stable, albeit low growth (0.02% growth percentage).
   - **Risk**: Low (4.84% future risk).
       - A conservative option for risk-averse investors.

**14201**
   - **Profitability**: Moderate growth (6.61% growth percentage).
   - **Risk**: Moderate (13.82% future risk).
       - A balanced option for investors seeking reasonable growth with manageable risk.

#### Risk-Growth Scatterplot: 
- A visual correlation between predicted growth and associated risk for each zip code.


## Next Steps
Suggests deeper analysis into local market trends, historical real estate performance, and broader economic factors to refine investment strategies.

## Conclusion
The project, with its comprehensive approach and detailed analysis, offers valuable insights into the New York real estate market, guiding investors towards informed decisions that align with their investment goals and risk tolerance.

