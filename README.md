# Time_Series_Analysis

## Problem Statement
- Compare different models for time series analysis against the ARIMA baseline to determine the most effective forecasting model.
  


- **Evaluation Criteria:** 
  - Performance based on test-error metrics.
  - Compare accuracy of each model against ARIMA's baseline to assess relative effectiveness.
  
- **Outcome:** 
  - Identify the optimal model for time series analysis, enhancing predictive capabilities and informing data-driven decision-making processes.

## Methodology
- Implement train-test-validation split:
    - Training: Tune model parameters to optimize performance.
    - Validation: Select the best-performing model based on validation set results.
    - Testing: Evaluate model accuracy and compare against ARIMA baseline.
  
- Utilize window sliding method for input generation:
    - Sequentially slide fixed-width window along time series data.
    - Facilitates input preparation for models like neural networks, decision trees, and linear models.


## Experimental Results and Validation
 

## Conclusion and Future Work

## Defining the problem
- We are comparing different models for analysis of time series data.
- We are checking the results with the baseline of ARIMA model, which is considered as the best model for time series data.
- How should you define the train-test split ? We are defining the train-test-validation split by using the window sliding method where we first split the whole time series into 3 sets & afterwards we perform our window sliding method to proivide for the input of our model like NN, decision tree & linear models
- Performance based on test-error

## Credits
- Rhythm Bansal (2021A7PS2430G)
- Ameya Kasture (2021A7PS2058G)
- Shivam Agarwal (2021A7PS2909G)
- Patel Dharmik Rohitkumar (2020A7PS0085G)