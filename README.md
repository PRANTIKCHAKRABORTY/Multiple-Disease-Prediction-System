# Multiple-Disease-Prediction-System

This project is a web application built using [Streamlit](https://streamlit.io/) that predicts the likelihood of a person having diabetes, heart disease, or Parkinson's disease. The application uses machine learning models trained on relevant datasets to provide predictions based on user input.

## Features

- **Diabetes Prediction**: Predicts the likelihood of diabetes based on user-provided health metrics.
- **Heart Disease Prediction**: Assesses the risk of heart disease using various health indicators.
- **Parkinson's Disease Prediction**: Evaluates the probability of Parkinson's disease using voice measurements.

## Models

The application uses three separate machine learning models for each disease prediction:

1. **Diabetes Model**: Trained to predict diabetes using features like glucose level, BMI, age, etc.
2. **Heart Disease Model**: Utilizes features such as age, cholesterol levels, and blood pressure to predict heart disease.
3. **Parkinson's Model**: Analyzes voice measurements to predict Parkinson's disease.


## Usage

1. Navigate to the application in your web browser.
2. Use the sidebar to select the disease prediction you want to perform.Enter the required health metrics in the input fields.
3. Click the "Test Result" button to get the prediction.
4. Optionally, click "Get Report" to view the input values you provided.


## File Structure
1. app.py: Main application file containing the Streamlit code.
2. saved_models/: Directory containing the pre-trained machine learning models.
3. requirements.txt: List of Python packages required to run the application.


## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.


## License
This project is licensed under the MIT License.


## Acknowledgements
1. Thanks to the datasets and libraries that made this project possible.
2. Special thanks to the Streamlit community for their support and resources.
