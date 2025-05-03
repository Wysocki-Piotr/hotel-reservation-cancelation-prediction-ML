# Hotel Booking Cancellation Prediction

## Project Goal

The goal of this project is to build a machine learning model that can **predict whether a hotel reservation will be canceled or not**, based on booking details and customer behavior.

Accurate prediction of cancellations can help hotels:
- Improve revenue management,
- Reduce overbooking risks,
- Plan resources and staffing more efficiently.

---
## Dataset
- Źródło: [Hotel Booking Demand dataset on Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)
- Dataset includes two types of hotels (city and resort) and columns such as number of meals, reserved parking spaces, babies, room type, country etc.

## Project Milestones

### 1. **Exploratory Data Analysis (EDA)**
In the first milestone, the dataset was preprocessed and analyzed to understand the distribution of features and their relationships with the target variable 

### 2. **Feature Engineering**
During this phase different encoding and feature selection techniques were used to optimize overall results and explanaibility of features.

### 3. **Modeling**
The final milestone involved training and adjusting different machine learning models. Main target was to boost accuracy, whereas not neglecting other metrics such as F1.  Final model was HistGradientBoosting with hyperparameters (models file).

---

## Results

- **Accuracy on 15 selected features**: 82%  
- **Class distribution**: The target variable is binary with a class imbalance (72% to 28%).
  
**Important Note**:  
When using all available features (without feature selection and any further actions, in total 100+ features) and applying one-hot encoding to categorical variables, the accuracy reached **84%**. 
