# Bridge Traffic Condition Classification Using Machine Learning and Time-Series Analysis
This project focuses on analyzing bridge vibration signals under different traffic conditions using machine learning and time-series analysis techniques. The dataset consists of vibration recordings collected from six sensors installed on a bridge under eight different traffic scenarios.

The vibration signals are processed using windowing and feature extraction methods to capture important structural behaviour characteristics such as vibration energy, peaks, and frequency patterns. Random Forest is used as a feature-based machine learning model, ARIMA is applied for classical time-series forecasting, and LSTM is used to learn temporal vibration patterns from sequential data.

The aim of the project is to identify and classify traffic-induced bridge vibration conditions and compare the performance of traditional machine learning and deep learning time-series models through visualization, statistical analysis, and model evaluation metrics.

## Dataset Description
# Bridge Vibration Monitoring Dataset

This project uses a multivariate bridge vibration monitoring dataset collected from a steel truss bridge under different traffic conditions. The dataset contains vibration signals recorded using six accelerometer sensors installed on the bridge structure.

The vibration data was collected at a sampling frequency of 200 Hz, meaning that each sensor records 200 vibration measurements per second. The dataset includes eight separate experimental recordings (test1.txt to test8.txt), where each file represents a different traffic or loading condition on the bridge.

Each row in the dataset corresponds to synchronized vibration measurements captured from multiple sensors at a specific time instant. The dataset is therefore considered multivariate time-series data because:

measurements are recorded continuously over time,
multiple sensors are used simultaneously,
temporal order of the signals is important.

The dataset is used to analyse traffic-induced vibration behaviour of the bridge using machine learning and time-series models such as Random Forest, ARIMA, and LSTM.

Dataset Characteristics
Domain: Structural / Bridge Monitoring
Data Type: Multivariate Time-Series
Sensors: 6 Accelerometers
Sampling Frequency: 200 Hz
Files: 8 Vibration Recordings
Signal Type: Bridge Vibration Acceleration Signals
Dataset Source

Bridge Vibration Monitoring Dataset
DOI: 10.17632/d3by55pjh7.2
