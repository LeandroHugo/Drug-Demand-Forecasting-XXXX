# 🚀 Project Overview 🚀

In this project, we embarked on a journey to solve a real-world problem faced by healthcare companies like McKesson: predicting the demand for various drugs to better manage inventory and reduce waste. 🏥💊

## 📚 Data Collection and Preprocessing 📚

Since real-world drug sales data is often not publicly available due to privacy and legal restrictions, we generated synthetic data for our project. We created a dataset with sales data for three drugs for each day of the year 2022. 📈📅

## 🔍 Exploratory Data Analysis 🔍

We visualized the sales data for the three drugs over time. This helped us understand the trends and patterns in our data, which is crucial for effective forecasting. 📊🔎

## 🏗️ Feature Engineering 🏗️

We created new features from the date, including the day of the week, the month, the day of the month, and the day of the year. These features can help our model capture weekly, monthly, and yearly patterns in the sales data. 📆🔧

## 🤖 Model Selection and Training 🤖

We chose the Random Forest model for our forecasting task. Random Forest is a powerful and versatile machine learning model that is often effective for regression tasks. We trained a separate model for each drug. 🌲🤖

## 🎯 Model Evaluation 🎯

We evaluated our models using the Mean Absolute Percentage Error (MAPE), which gives us an idea of the average error of our models as a percentage of the actual values. This metric is intuitive and easy to interpret. 🎯📏

## 🚀 Model Deployment 🚀

We created a function that takes in the features of a new data point (day of the week, month, day of the month, and day of the year) and returns the predicted sales for each drug. This function can be used to make predictions on new data. 🚀🔮

### **🎉 Conclusion 🎉**

We successfully built a forecasting system that can predict drug demand, which can help companies like McKesson better manage their inventory and reduce waste. However, our approach has some limitations. For example, our model might not perform as well on real-world data, which is often noisier and more complex than synthetic data. Future work could involve training our model on real-world data, if it becomes available, or exploring more sophisticated forecasting models. 🎉🏁

Remember, the journey is just as important as the destination. We learned a lot from this project, and we hope you did too! 🌟🎓