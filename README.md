# DiaXpert


# webapp deploy link : 
https://diabetesprediction-s9w303zgoum.streamlit.app/

This app predicts whether a person is diabetic or not based on their age, pregnancies, glucose level, blood pressure, skin thickness, insulin level, BMI, and diabetes pedigree function.

The app uses a variety of machine learning models to make the prediction, including support vector machines (SVM), logistic regression, decision trees, k-nearest neighbors, and random forests. The best model is selected based on its accuracy on a test set of data.

The app also provides a visualization of the patient's data along with the predicted outcome. This can be helpful for understanding the factors that contributed to the prediction.

Usage

To use the app, simply enter your age, pregnancies, glucose level, blood pressure, skin thickness, insulin level, BMI, and diabetes pedigree function into the sidebar. The app will then predict whether you are diabetic or not.

You can also view the visualizations of your data and the predicted outcome by clicking on the "Visualised Patient Report" tab.

Dependencies

The app requires the following dependencies:

streamlit
pandas
sklearn
Installation

To install the app, you can use the following command:

pip install diabetes-prediction-app
Usage Examples

Here are some examples of how to use the app:

To predict whether a 35-year-old woman with 2 pregnancies, a glucose level of 120, a blood pressure of 100, a skin thickness of 20, an insulin level of 100, a BMI of 25, and a diabetes pedigree function of 0.47 is diabetic, you would enter the following values into the sidebar:
Pregnancies: 2
Glucose: 120
BloodPressure: 100
SkinThickness: 20
Insulin: 100
BMI: 25
DiabetesPedigreeFunction: 0.47
The app would then predict that the woman is not diabetic.

To view the visualizations of the woman's data and the predicted outcome, you would click on the "Visualised Patient Report" tab.
Contributing

If you would like to contribute to the app, you can fork the repository on GitHub and submit a pull request.

License

The app is licensed under the MIT License.

I hope this README is helpful!
