# Investment Analysis: Evaluating TESLA for Portfolio Inclusion

This project aims to analyze whether TESLA should be included in an investment portfolio, using various financial models and algorithms to evaluate the potential impact of this asset on the portfolio. By utilizing a range of techniques, we can determine whether adding TESLA improves portfolio performance in terms of risk and return.

## Contents

1. **Problem Definition**
   - The objective of this analysis is to assess whether TESLA (TSLA) should be included in the existing investment portfolio. Various models and algorithms will be used to evaluate TESLA's risk, return, and correlation with the current assets in the portfolio. The goal is to determine if TESLA enhances the overall performance, measured by improved returns or reduced risk.

2. **Loading Data and Python Packages**
   - **2.1. Loading Python Packages**: The necessary libraries for data manipulation, financial analysis, and machine learning are imported.
   - **2.2. Data Download**: Historical stock data for TESLA and other portfolio assets is downloaded, cleaned, and prepared for analysis.

3. **Understanding Data**
   - A comprehensive overview of the data, including the key variables, timeframe, and any preprocessing steps. This section provides an understanding of the dataset to ensure correct interpretation of the results.

4. **Model Building**
   - **4.1. Modern Portfolio Theory (MPT)**: MPT is used to determine the optimal asset allocation in the portfolio by maximizing expected return for a given level of risk.
   - **4.2. Semi-Covariance Model**: This model will be used to focus on downside risk, examining how TESLA’s inclusion impacts the potential for negative portfolio returns.
   - **4.3. Capital Asset Pricing Model (CAPM)**: CAPM will be employed to assess the expected return of TESLA based on its risk relative to the market.
   - **4.4. Black-Litterman Model**: This model incorporates market equilibrium returns and investor views to calculate an optimal portfolio allocation with TESLA.

5. **LSTM (Long Short-Term Memory)**
   - A machine learning model will be applied to predict TESLA's future stock price movements. LSTM, a type of recurrent neural network, will be used to capture the temporal dependencies in stock price data, providing a predictive model for TESLA's performance.

6. **Conclusion**
   - A summary of the results from each of the models will be presented, comparing the risk and return profiles with and without TESLA in the portfolio. Recommendations will be made based on the analysis, including whether TESLA should be included in the portfolio and the optimal allocation.


