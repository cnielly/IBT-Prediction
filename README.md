# IBT-Prediction
This project is a use case that was presented to us by the Consulting Firm Eleven.

### Data

We were provided with three data files:
- Airport Data: 
  - To train the model: Information about landing in the airport during the last 6 months
  - To predict: Anticipated information as runaway, estimated landing hour etc
- Aircraft Data: main characteristics of the aircraft
- Weather Data: diverse observations aggregated on a daily basis

### Goal

Taxi time is the time window between the moment the airplane’s wheels touch the ground i.e. the Actual Landing Time
(ALDT) and the moment it arrives at its assigned dock i.e. Actual In-Block Time (AIBT).

Currently almost every airport around the world is using a moving average approach to predict the taxi time: the airport assumes that the taxi-in time for a given day will be equal to the average of taxi-ins during the past two months.
The goal of this project is to improve the taxi time prediction thanks to Machine Learning algorithms. 

### Presentation of the files

- `data` folder: raw data and generated data sets
- `data_preparation` folder: cleaning, merging data sets, creating new features, etc
- `models` folder: build, train and test ML models such as Mixed Effects or Random Forest. 

We would like to thank Eleven for this great opportunity to work on a real life case. 
As future data scientists, we enjoyed the "learning-by-doing" philosophy of this course.

*Gautier DULAC, Sophie BROSSE, Antoine SALAMITOU, Léonard FLEUTOT and Cyprien NIELLY*

*Students of the MSc "Data Science for Business", between HEC Paris and Ecole polytechnique.*

