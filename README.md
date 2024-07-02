# DFM
DFM project: GDP and Interest Rate
Adding average absolute contributions to the orignial nowcast by @Gene Kindberg-Hanlon. 
Average absolute contributions are insightful because: 
1) Importance of Each Factor: The average absolute contributions help quantify how much each individual factor contributes to the predictive power    of the model for nowcasting GDP or any other outcome variable. Higher contributions imply that the factor is more important for capturing the      variability or movements in the dependent variable.

2) Identification of Key Drivers: By assessing the magnitude of contributions, you can identify which factors are key drivers of the forecasted       variable. This is particularly useful in economic modeling where understanding which indicators (like employment rates, industrial production,     consumer sentiment, etc.) most influence outcomes like GDP is crucial for both policy formulation and economic analysis.

3) Model Calibration and Simplification: If certain factors consistently show very low or negligible contributions, it might indicate that these      factors are not very useful in the model. This information can be used to simplify or recalibrate the model by removing or replacing less          significant factors, thus potentially improving model efficiency and focus.

Why I will apply this method to interest changes in addition to GDP: 
1) Economic Indicators as Predictors: Central banks often consider various economic indicators to make decisions about interest rate adjustments.     Inflation and unemployment are primary factors in such decision-making processes (reflecting the central bank’s dual mandate in many countries,    like the Federal Reserve in the U.S.). A dynamic factor model can efficiently encapsulate the complex relationships between these indicators       and the potential direction of monetary policy.

2) Capturing Latent Factors: One of the strengths of dynamic factor models is their ability to capture latent factors that might influence            interest rates. These could include underlying economic conditions or sentiments that are not directly observable but are reflected across         various data points like consumer spending, business investment, or financial market conditions.

3) Nowcasting and Forecasting: Just as with GDP, interest rates can be nowcasted or forecasted using current and past data to predict short-term      movements. Given that interest rate decisions are typically forward-looking and contingent on expectations about future economic conditions,       integrating leading indicators into a factor model can provide valuable forecasts.
