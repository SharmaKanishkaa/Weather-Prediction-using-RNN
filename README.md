# Weather Prediction using RNN 🌦️🌡️

This project leverages **Recurrent Neural Networks (RNNs)** to predict weather patterns based on historical weather data. Specifically, we use features such as **temperature, wind, precipitation**, and **weather conditions** to predict the maximum temperature (`temp_max`) for future dates. The model is trained on a dataset with columns like **date**, **precipitation**, **temp_max**, **temp_min**, **wind**, and **weather**.

---

## 🚀 **Project Overview**
The goal of this project is to predict the maximum temperature (`temp_max`) based on historical weather data. The model uses **RNNs**, which are great for time-series forecasting, to learn from the sequences of weather data and make accurate predictions for future temperatures.

---

## 📊 **Dataset Description**
The dataset consists of the following columns:
- **date**: Date of the recorded weather data
- **precipitation**: Amount of precipitation (rain/snow)
- **temp_max**: Maximum temperature of the day
- **temp_min**: Minimum temperature of the day
- **wind**: Wind speed
- **weather**: Weather condition (e.g., sunny, rainy, etc.)

---

## ⚙️ **Model Overview**

1. **Data Preprocessing**: 
   - The data is first prepared for model training by cleaning and normalizing the temperature values.
   - The features are selected, and the data is divided into **training**, **validation**, and **test** sets.
   - A **window size** (time step) is used to look at a sequence of past weather data to predict future temperatures.

2. **Model Architecture**: 
   - The **RNN** model is used to capture the sequential nature of the weather data.
   - The model is trained on the historical data and evaluated on the validation and test datasets.

3. **Prediction**: 
   - After training the model, predictions are made on the validation and test datasets.
   - The predicted maximum temperatures are compared to the actual values.

---

## 📈 **Visualization of Results**

To visualize the model's performance, the following plots are generated:

- **Validation Results**: The actual vs. predicted temperature values on the validation set.
- **Test Results**: The actual vs. predicted temperature values on the test set.

---

## 📊 **Results Interpretation**

- **Validation Results**: This plot shows the actual temperatures vs the predicted values for the validation set. The accuracy of the predictions on the validation data provides insight into how well the model is generalizing.
  
- **Test Results**: This plot shows how well the model performs on unseen test data, indicating its potential for making real-world predictions.

---

## ⚡ **Key Features**
- **Time-Series Forecasting**: By using **RNNs**, the model effectively captures patterns and trends in weather data.
- **Data Visualization**: Beautiful plots show the comparison between actual and predicted temperatures, helping evaluate the model’s performance.
- **End-to-End Solution**: This project involves data preprocessing, model building, training, and evaluation, giving a comprehensive view of how weather prediction can be implemented using machine learning.

---

## 🛠️ **Technologies Used**
- **Python**: Main programming language used for data manipulation, model training, and evaluation.
- **Pandas**: Used for data processing and manipulation.
- **NumPy**: Used for numerical operations and working with arrays.
- **Matplotlib & Seaborn**: For data visualization.
- **Keras**: For building and training the Recurrent Neural Network.

---

## 💡 **Conclusion**
This project demonstrates the power of **RNNs** in predicting weather patterns based on historical data. With the ability to learn from sequential data, this model offers a strong foundation for building more sophisticated weather prediction systems.
