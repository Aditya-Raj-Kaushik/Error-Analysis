# Error-Analysis
Here are the error metrics formatted neatly for direct use in your README file:

---

### Error Metrics in Regression

1. **Mean Squared Error (MSE):**  
   Calculates the average of the squared differences between predicted and actual values, penalizing large errors heavily.  
   **Formula:**  
   \[
   \text{MSE} = \frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2
   \]

2. **Root Mean Squared Error (RMSE):**  
   The square root of MSE, which puts the error back into the original unit of the data, making it easier to interpret.  
   **Formula:**  
   \[
   \text{RMSE} = \sqrt{\text{MSE}} = \sqrt{\frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2}
   \]

3. **Mean Absolute Error (MAE):**  
   Calculates the average absolute difference between predicted and actual values, less sensitive to outliers compared to MSE/RMSE.  
   **Formula:**  
   \[
   \text{MAE} = \frac{1}{n} \sum_{i=1}^{n} |y_i - \hat{y}_i|
   \]

4. **Mean Absolute Percentage Error (MAPE):**  
   Expresses errors as a percentage of the actual values, useful when comparing predictions across different scales.  
   **Formula:**  
   \[
   \text{MAPE} = \frac{1}{n} \sum_{i=1}^{n} \left| \frac{y_i - \hat{y}_i}{y_i} \right| \times 100
   \]  
   *Note: \( y_i \) should not be zero to avoid division errors.*

5. **R-squared (Coefficient of Determination):**  
   Represents the proportion of variance in the dependent variable explained by the regression model, with a value closer to 1 indicating a better fit.  
   **Formula:**  
   \[
   R^2 = 1 - \frac{\sum_{i=1}^{n} (y_i - \hat{y}_i)^2}{\sum_{i=1}^{n} (y_i - \bar{y})^2}
   \]  
   Where \( \bar{y} \): Mean of the actual values.  

6. **Root Mean Square Log Error (RMSLE):**  
   Takes the logarithm of the errors before calculating RMSE, particularly useful when dealing with data with large value ranges.  
   **Formula:**  
   \[
   \text{RMSLE} = \sqrt{\frac{1}{n} \sum_{i=1}^{n} \left( \log(y_i + 1) - \log(\hat{y}_i + 1) \right)^2}
   \]  
   *Note: Logarithm ensures that errors for smaller values are treated proportionally.*

---

Feel free to copy this directly! Let me know if you need any further formatting adjustments.
