Time Series Forecasting Project

📌 Overview

This project applies various time series models to predict future values based on given historical data. The models implemented include AR, MA, ARMA, ARIMA, and Auto ARIMA (both seasonal and non-seasonal).

📊 Dataset

The dataset consists of a simple time series:

10, 23, 36, 40, 51, 63, 72, 84, 93, 102, 113, 125

A test set is also provided to evaluate model accuracy:

85, 92

🚀 Models Used

AR (AutoRegressive Model): Uses past values to predict future values.

MA (Moving Average Model): Uses past forecast errors to improve predictions.

ARMA (AutoRegressive Moving Average): Combines AR and MA models.

ARIMA (AutoRegressive Integrated Moving Average): Uses differencing to handle non-stationary data.

Auto ARIMA (with & without seasonality): Automatically selects the best ARIMA parameters.

🔧 Installation

Ensure you have the required R packages installed:

install.packages("zoo")
install.packages("forecast")
install.packages("Metrics")

Then, load them in your R environment:

library(zoo)
library(ggplot2)
library(forecast)
library(Metrics)

📈 Forecasting & Evaluation

The script forecasts the next two values and evaluates performance using:

MAE (Mean Absolute Error)

MAPE (Mean Absolute Percentage Error)

RMSE (Root Mean Squared Error)

📜 Usage

Run the R script to:

Train different time series models.

Generate forecasts for future values.

Compare model performance using error metrics.

📌 Example Output

Predicted values for the next two time points using different models:

   AR    MA   ARMA  ARIMA  AutoARIMANoSeason  AutoARIMASeason
  X1    X2    X3    X4      X5                   X6

(E.g., replace X1, X2... with actual results)

📬 Contact

For questions or improvements, feel free to open an issue or submit a pull request! 🚀
