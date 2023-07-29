# Diabetes Prediction System Using Machine Learning

![Diabetes Prediction System](https://drive.google.com/file/d/1MswFq8HniIRQAo0Xyy2OmGrCc5B_WeWl/view) 
![Diabetes Prediction System](https://drive.google.com/file/d/1lv2RiUq97lLeliyAn9naG-EQRYbW_6G9/view) 

## About

This project implements a Diabetes Prediction System using Machine Learning. It utilizes the Support Vector Machine (SVM) algorithm to predict whether a patient is likely to have diabetes based on certain health parameters. The model is trained on a dataset containing data from 768 patients, and it achieves an accuracy of 78%.


## Project Repository

The project repository can be found on GitHub at the following link: [Diabetes-Prediction-System-Using-ML](https://github.com/AbhishekJoshi236/Diabetes-Prediction-System-Using-ML)


## Technologies and Tools

- Language: Python
- IDE: Jupyter Notebook
- Libraries:
  - NumPy
  - Pandas
  - StandardScaler from sklearn.preprocessing
  - Train_test_split from sklearn.model_selection
  - SVM from sklearn
  - accuracy_score from sklearn.metrics
  - Tkinter (for GUI)
  - Joblib (for model saving and loading)


## Dataset

The project uses a dataset downloaded from Kaggle, which includes data from 768 patients. The dataset consists of 8 features: pregnancies, glucose level, blood pressure, skin thickness, insulin level, BMI (Body Mass Index), Diabetic Pregnancy Function, age, and outcome (target variable).


## Machine Learning Algorithm

The SVM (Support Vector Machine) algorithm is employed to build the prediction model. SVM is a powerful classification algorithm that works well for both linear and non-linear data.


## Methodology

The project follows the below sequence of steps:

1. Importing libraries required for the project.
2. Importing the dataset for analysis.
3. Analyzing and understanding the dataset.
4. Separating data into features (input variables) and labels (output variable).
5. Standardizing the data to bring all features to a common scale.
6. Splitting the dataset into training and testing sets.
7. Training the SVM model using the training data.
8. Evaluating the model's accuracy on the test data.
9. Saving the trained model to a file named "model_diabetes_pre" using Joblib.
10. Implementing an interactive GUI using Tkinter for end-user interaction.
11. Loading the saved model and using it to make predictions based on user inputs through the GUI.


## Contributing

Contributions to this project are welcome. If you have any suggestions, bug reports, or improvements, please feel free to open an issue or submit a pull request on the GitHub repository.


## Contact

If you have any questions or want to get in touch, you can reach out to the project owner:

- GitHub: [AbhishekJoshi236](https://github.com/AbhishekJoshi236)

---

**Note:** The accuracy of the ML model (78%) mentioned in this README is based on the dataset and model used at the time of creation. The actual accuracy might vary based on updates to the dataset or improvements in the model over time.
