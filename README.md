# anomaly-detection
This example implemented the anomaly detection algorithm on time series data. 
The simulated data of a mobile app's daily active users (DAU) was used to describe the data issues that may arise in real-world scenarios. We then employ an anomaly detection system to perform backtesting, validating the feasibility of this algorithm and demonstrating how it can be applied in practical situations.

Please check [the blog]() for all details.


The two implemented anomaly detection algorithms:

### 1. Level shift anomaly detection

Goal: To detect sudden drops or increases in data values, enabling us to provide timely alerts.

Reference: [adtk](https://adtk.readthedocs.io/en/stable/)

### 2. Isolation forest anomaly detection
Goal: Help us monitor collections of abnormal data points. In our use case, they are used to issue warnings when the value have not returned to normal.

Reference: [sklearn.ensemble.IsolationForest](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.IsolationForest.html)


## requirements
`adtk==0.6.2`

`Pillow==9.5.0`

`plotly==5.14.1`

`scikit_learn==1.1.2`



