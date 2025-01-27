# Error-Analysis

### Error Metrics in Regression

1. **Mean Squared Error (MSE):**  
   Calculates the average of the squared differences between predicted and actual values, penalizing large errors heavily.  
   **Formula:**  
  MSE = (1/n) * Σ(y_i - y_hat_i)^2


2. **Root Mean Squared Error (RMSE):**  
   The square root of MSE, which puts the error back into the original unit of the data, making it easier to interpret.  
   **Formula:**
   RMSE = √MSE = √((1/n) * Σ(y_i - y_hat_i)^2)

   

3. **Mean Absolute Error (MAE):**  
   Calculates the average absolute difference between predicted and actual values, less sensitive to outliers compared to MSE/RMSE.  
   **Formula:**
   MAE = (1/n) * Σ|y_i - y_hat_i|


4. **Mean Absolute Percentage Error (MAPE):**  
   Expresses errors as a percentage of the actual values, useful when comparing predictions across different scales.  
   **Formula:**
   MAPE = (1/n) * Σ(|y_i - y_hat_i| / y_i) * 100

5. **R-squared (Coefficient of Determination):**  
   Represents the proportion of variance in the dependent variable explained by the regression model, with a value closer to 1 indicating a better fit.  
   **Formula:**
   R^2 = 1 - (Σ(y_i - y_hat_i)^2 / Σ(y_i - y_mean)^2)

   

6. **Root Mean Square Log Error (RMSLE):**  
   Takes the logarithm of the errors before calculating RMSE, particularly useful when dealing with data with large value ranges.  
   **Formula:**  
  RMSLE = √((1/n) * Σ(log(y_i + 1) - log(y_hat_i + 1))^2)


