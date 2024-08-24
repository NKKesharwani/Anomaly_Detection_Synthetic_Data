1. **Objective**: 
   - Develop a system for real-time anomaly detection and predictive maintenance for application components.
   - Implement it within a web-based application.

2. **Components**:
   - **Data Collection**: Gather performance metrics from application components.
   - **Data Processing**: Clean, transform, and store data for further analysis.
   - **Anomaly Detection**: Build a machine learning model to detect anomalies in the performance metrics.

### Data Collection and Preprocessing
1. **Simulate Data**: 
   - Created synthetic data that mimics system performance metrics, including CPU usage, memory usage, disk I/O, etc.
   - Introduce some anomalies and patterns for predictive maintenance.


### Anomaly Detection Model
1. **Feature Engineering**:
   - Extract relevant features such as moving averages, standard deviations, and time-based features.
   
2. **Model Development**:
   - Use machine learning models like Isolation Forest & DBSCAN for anomaly detection.
   - Train the model on normal behavior data, and validate it with data containing anomalies.
