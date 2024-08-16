**Flight Price Prediction**

This project aims to predict flight ticket prices based on various factors using machine learning algorithms. The primary focus is to demonstrate the process of data cleaning, feature engineering, and model selection to achieve high accuracy in flight price prediction.

**Installation**

git clone https://github.com/srivastavankur1/Flight-Price-Prediction.git
cd Flight-Price-Prediction
pip install -r requirements.txt

**Usage**

The project can be used in the following way:

1. *Data Cleaning and Preprocessing*: Run the EDA_and_Preprocessing.ipynb notebook or execute data_cleaning.py and feature_engineering.py scripts to clean and preprocess the data.
2. *Model Training*: Use the Model_Training_and_Evaluation.ipynb notebook or model_training.py script to train various machine learning models.
3. *Model Evaluation*: Evaluate the trained models using the model_evaluation.py script.

**Data Description**

The dataset used in this project includes the following features:

Airline: Name of the airline.
Source: The departure location.
Destination: The arrival location.
Route: The flight route taken.
Duration: Total flight duration.
Total_Stops: Number of stops between source and destination.
Date_of_Journey: The date of the journey.

The training data (Data_Train.xlsx) contains 10,683 records, and the test data (Test_set.xlsx) is used to validate the model's performance.

**Modeling**

Various machine learning models were implemented and tested:

1. Linear Regression
2. Decision Tree
3. Random Forest
4. Gradient Boosting
5. XGBoost
6. Support Vector Machine (SVM)

**Conclusion**

The project successfully demonstrates the process of predicting flight prices using machine learning techniques. The insights gained from this analysis can help travelers make better decisions when booking flights.

**Future Work**

Potential areas for improvement include:

- Incorporating additional features such as airline rating, flight distance, and weather conditions.
Using advanced modeling techniques like neural networks.
- Developing a web application to provide real-time price predictions.

**Contributing**

Contributions are welcome! If you have any suggestions or improvements, please feel free to create a pull request or open an issue.

**License**

This project is licensed under the MIT License.