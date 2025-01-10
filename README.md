# Time Series Prediction and Forecasting

author:
  * [Mohammad SHREM](https://www.linkedin.com/in/mohammadbshreem/) <mohammad.shrem@edu.univ-fcomte.fr>
    
supervisor:
  * [Prof. Michel SALMON](https://www.femto-st.fr/fr/personnel-femto/msalomon) <michel.salomon@univ-fcomte.fr>

project relaized in [Google Colaboratory](https://colab.google/)

---

## Description
This repository contains code and models for time series prediction and forecasting. The project focuses on creating models to analyze and predict values from various datasets, leveraging neural networks and advanced deep learning techniques.

## Features

### 1. Univariate and Multivariate Time Series Forecasting
- Utilizes the `timeseries_dataset_from_array` method from Keras.
- Includes examples with both univariate (single series) and multivariate (multiple series) predictions.

### 2. Electrical Power Consumption Forecasting
- Models developed using `household_power_consumption.txt`.
- Experiments conducted with different dataset sizes (5,000 and 10,000 samples).
- Variations of LSTM models implemented.

### 3. Prediction Models
- Based on `Timeseries-data.csv`:
  - **Univariate Forecasting:** Predict future values using past values of a single variable.
  - **Multivariate Forecasting:** Predict future values based on multiple features (e.g., P and Rho values).
- Data split: 80% for training, 20% for testing.
- Visualization of actual vs. predicted data.

### 4. Noise Level Prediction and Detection
- Based on data from `DataParkmeter.zip`.
- Normalization using `MinMaxScaler` from Scikit-learn.
- Implements deep learning models to predict short and long-term noise levels.
- Experiments include detection of false data injection attacks and potential extensions to pollution data.

<div align="center">
<img src="https://github.com/user-attachments/assets/161cdaf7-c5a3-43cf-adf1-1ce68d72c46e"></br>
</div>
</br>

## Datasets
- `household_power_consumption.txt`: Data for electrical power consumption.
- `Timeseries-data.csv`: Time series data for temperature and other variables.
- `DataParkmeter.zip`: Urban environmental noise data for smart cities.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Access the Jupyter Notebooks:
   - `lab-Example-TimeseriesGenerator.ipynb`: Example using TimeseriesGenerator.
   - `Empty_Students-Elect-LSTM.ipynb`: LSTM implementation for electrical power consumption.
   - `lab-Elec-timeseries_dataset_from_array-LSTM.ipynb`: Enhanced LSTM implementation.
   - `Prediction-Univariate-Multivariate.ipynb`: Forecasting models for univariate and multivariate data.
   - `NoisePrediction.ipynb`: Noise level prediction and anomaly detection.

4. Run the notebooks on your local machine or in Google Colab.

## Results
- Models were evaluated for training and testing performance.
- Predictions visualized for clear comparison between actual and forecasted values.

## Contribution
Feel free to submit issues or pull requests for improvements or new features.

## References

1. Cours Info, "Data Mining," [Online]. Available: https://cours-info.iut-bm.univ-fcomte.fr/pmwiki/pmwiki.php/MonWiki/DataMining. [Accessed: Jan. 10, 2025].

2. J. Renaud, R. Karam, M. Salomon, and R. Couturier, "Deep Learning and Gradient Boosting for Urban Environmental Noise Monitoring in Smart Cities," FEMTO-ST Institute, CNRS, Univ. Bourgogne Franche-Comté (UBFC), Belfort, France. Available: https://drive.google.com/file/d/10KyNkjmoFL_Jv9q6kWJeErU9PoZTuYoR/view. [Accessed: Jan. 10, 2025].

