# Sales Forecasting using RNN_model
This project demonstrates how to use Recurrent Neural Networks (RNN) to forecast future alcohol sales using historical sales data.
## Project Overview

In this project, I implemented an RNN model using Python to predict the future sales of alcohol. The model is trained on historical sales data, and the goal is to forecast sales for the upcoming periods.

## Key Steps:

1. **Seasonal Decomposition**: Decomposed the time-series data to understand the underlying patterns in the data.
2. **Data Scaling**: Scaled the training and testing data using MinMaxScaler to normalize the data before feeding it into the model.Neural networks generally perform better when the input data is scaled between a fixed range (usually 0 and 1)
3. **Data Batching**: Utilized `TimesSeriesGenerator` to batch the data for the RNN model to process it effectively.
4. **Model Training**: Trained an RNN model to predict sales, using Mean Squared Error (MSE) as the loss function to evaluate performance.
5. **Model Evaluation**: Plotted the test data and predictions to visualize the model’s accuracy.
6. **Forecasting**: Used the trained model to forecast future sales of alcohol.
