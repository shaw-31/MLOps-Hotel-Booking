# MLOps Project
Term 5 Final project submitted to Prof. Manaranjan Pradhan

## Title
Hotel Booking Cancellation Analysis and Prediction

## Description
This project focuses on explaining the factors that contribute to the cancellation of hotel bookings.
The dataset is described as follows:
- Data source: Kaggle (https://www.kaggle.com/jessemostipak/hotel-booking-demand)
- Dataset dimensions:
  - No. of features = 32, No. of records = 119390

 
Numeric Features:
- Lead Time | Number of Adults | Number of Children | Number of Babies | Number of Weekday Stay-days | Number of Weekend Stay-days | Number of Previous
- Cancellations | Number of Booking Changes | Number of Days in Waiting List | Average Daily Rate | Special Requests Made

Categorical Features:
- Type of Hotel | Cancellation Flag | Meal Type | Country | Market Segment | Customer Type
- Distribution Channel | Repeat Customer Flag | Reserved & Assigned Room Types | Deposit Type

## Essential usages

To correct version issues specific to packages owing to dependencies
```python
pip install scikit-learn --upgrade
pip install scikit-learn==1.0.1
```

Fitting an encoded model
```python
model.fit(X = x_train, y = y_train)
```

To display graphs in the colab page
```python
%matplotlib inline
```

Converting dataframe to numpy nd-array
```python
x_train_n = x_train.to_numpy()
```

## Support
- Data dictionary guide: Under references 
- Model card and sample reports: Under reports
- Common issues: www.stackoverflow.com

## Roadmap
Future tasks: 
- Model maintenance 
- Application of concepts for different applications and generating a library

## Authors and Acknowledgement
- Source contributor: Jesse Mostipak, Kaggle Expert, Data Science Evangelist
- Project contributors: Yerrapragada Atul | Anusha S | Romil Mathew | Arif Pathan

## Project Status
Model maintenance might be required in the due course if the model performance deteriorates







