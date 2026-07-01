# Macroeconomic Rent Pricing Analysis

**Objective**
This project cleans 2 million data points, removing duplicates, NA values, and unnecessary columns, and analyzes over 100,000 historical housing market records (2010–2018) to quantify the macroeconomic factors driving rent prices. Designed to identify historical impacts on stable markets, this model provides actionable, data-driven insights for affordability policy and interest rate forecasting.

**Methodology & Tech Stack**
* **Language & Tools:** R, `ggplot2`, `corrplot`
* **Statistical Modeling:** Log-transformed Multiple Linear Regression ($R^2 = 0.82$)
* **Diagnostic Testing:** * Evaluated Variance Inflation Factor (VIF) to rule out collinearity.
  * Applied Cook’s Distance and matrix leverage statistics to isolate and analyze highly influential outliers.
  * Validated assumptions of normality, homoscedasticity, and autocorrelation.
  * Executed strict hypothesis testing (all final predictors significant at $\alpha = 0.01$).

**Key Macroeconomic Findings**
* **Price Sensitivity (The "Sticky" Rent):** Identified that a 10% increase in median home listing prices correlates with a 6% increase in the rent index—the strongest predictive relationship in the model. 
* **Supply Dynamics:** Demonstrated that increased housing inventory and sales counts negatively correlate with rent prices, quantifying the flow of consumers moving from apartments to homeownership.
* **Economic Deflation Indicators:** Proved that higher Price Cut Frequencies and Depths lead to higher rent demand. Poor economic conditions for home-buying directly inflate the rental market.
* **The Gentrification Effect:** Isolated highly influential real estate markets using Cook's Distance, proving that high-luxury, high-leverage neighborhoods disproportionately skew median rent pricing upwards.
<img width="1821" height="850" alt="image" src="https://github.com/user-attachments/assets/507ee535-a028-472c-8687-1f86a509ceab" />
<img width="1844" height="696" alt="image" src="https://github.com/user-attachments/assets/9fbc6930-362a-458a-a99b-6f1b0f05a81d" />
<img width="1531" height="788" alt="image" src="https://github.com/user-attachments/assets/b1c92ff1-9481-4692-bb27-b9fe2a27f066" />
<img width="1531" height="788" alt="image" src="https://github.com/user-attachments/assets/d4b65486-d4f4-479f-a84a-6f4a260f1566" />
