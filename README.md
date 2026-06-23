Project Description

Papaya Growth Recommendation System is a machine learning-based agricultural decision support system that helps determine whether environmental conditions are suitable for papaya cultivation. The system collects relevant weather data through a weather API, stores it in a CSV dataset, labels the data based on predefined growth criteria using conditional rules, and trains machine learning models to predict papaya growth suitability. This enables farmers and agricultural planners to make informed decisions based on weather conditions.

Algorithm Information
1. Data Collection:
Weather data was fetched from a weather API.
Parameters such as temperature, humidity, rainfall, and other relevant factors were stored in a CSV file.
2. Data Labeling:
The collected data was labeled using if-else conditions based on predefined papaya growth requirements.
Labels indicated whether the conditions were suitable or unsuitable for papaya growth.
3. Model Training:
The labeled dataset was used to train machine learning classification model (random forest)
4. Prediction:
The trained model analyzes new weather conditions.
It predicts whether the current or forecasted conditions are favorable for papaya cultivation.
5. Output:
Suitable for Papaya Growth or
Not Suitable for Papaya Growth
