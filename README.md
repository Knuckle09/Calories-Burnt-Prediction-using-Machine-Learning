# Calories-Burnt-Prediction-using-Machine-Learning

**Demo Images**


![image](https://github.com/user-attachments/assets/820673af-db5e-4432-aee0-994701f535f8)


1. **Libraries Used**: 
   The project uses various Python libraries like `pandas` for data handling, `numpy` for numerical operations, `seaborn` and `matplotlib` for plotting graphs, and `scikit-learn` and `xgboost` for building machine learning models.

2. **Loading Data**: 
   It reads two CSV files containing information about calories and exercise, and combines them based on a common identifier (User  ID).

3. **Exploring Data**: 
   The project checks for missing values and duplicate entries in the data. It also shows basic statistics and creates visualizations to understand the data better.

4. **Preparing Data**: 
   The data is split into features (like age, height, etc.) and the target variable (calories). It uses techniques to convert categorical data (like gender) into a format suitable for modeling and scales numerical data for better performance.

5. **Building the Model**: 
   A machine learning model is created using a pipeline that includes data preparation and a regression model (initially a simple linear regression).

6. **Evaluating the Model**: 
   The model's performance is checked using metrics like R² score and Mean Absolute Error to see how well it predicts calories burnt.

7. **Testing Multiple Models**: 
   The project tests different types of models (like Random Forest and XGBoost) to find out which one performs the best.

8. **Saving the Model**: 
   The trained model is saved to a file so it can be used later without needing to train it again.

9. **Making Predictions**: 
   A sample input is created to show how to use the model to predict calories burnt based on user data.

10. **Creating a User Interface**: 
    A simple graphical user interface (GUI) is built using `tkinter`, allowing users to enter their information and get predictions.

11. **User  Interaction**: 
    The GUI has dropdowns and text boxes for users to input their gender, age, height, weight, exercise duration, heart rate, and body temperature.

12. **Displaying Results**: 
    After the user submits their information, the predicted calories burnt are shown in the GUI.
