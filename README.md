# Scholarship_prediction_using_AI
An AI-powered model designed to predict scholarship eligibility based on academic achievements, extracurricular involvement, and financial background.
# Project Overview
This project aims to create a predictive model using machine learning techniques to help students identify scholarships for which they are eligible. The model was developed based on simulated data of academic performance, financial background, and extracurricular activities.

## Key Features:
* **Prediction Model**: Uses Random Forest and other machine learning algorithms to predict eligibility for various scholarships.
* **Simple Interface**: A user-friendly interface created using Streamlit for students to input their details and receive a list of eligible scholarships.
* **Scalable**: The model can be further improved by adding more attributes such as test scores, internships, research experience, etc.
* **Prototype**: This is a prototype project designed using minimal and core attributes due to data simulation.

## Repository Structure
* **interface.ipynb**: Jupyter Notebook used to develop and test the project interface.
* **.pkl files**: Pickle files containing pre-trained Random Forest models for predicting scholarship eligibility.
* **scholarships.csv**: Dataset containing scholarship information.
* **students.csv**: Dataset containing student details for testing the model.
    * The .csv files are created for the purpose if simulating the dataset. After creating the dataframe students_df, the .csv files are no more utilised in the project.
* **Scholarship_prediction_model.ipynb**: The notebook used for training and evaluating the Random Forest model.
* **README.md**: Project documentation.
* **Requirements**
<p>To run this project, you will need to install the following Python libraries:<br>
scikit-learn<br>
pandas<br>
numpy<br>
streamlit<br>
You can install these libraries using pip in jupyter notebook</p>

## Usage
* **Model Training**: The model was trained using Random Forest and SMOTE (Synthetic Minority Over-sampling Technique) to handle imbalanced data in the scholarship eligibility dataset.

* **Interface**: Run the Streamlit interface to input student details:
`streamlit run interface.py`<br>
The interface will display eligible scholarships based on the inputs provided by the user.

## Future Scope
* **Attribute Expansion**: Add more features like test scores, research experience, and internship background to improve prediction accuracy.
* **Model Improvement**: Experiment with different algorithms (e.g., XGBoost, SVM) and fine-tune hyperparameters to increase performance.
* **Real-Time Data**: Integrate real-world data to make the model more accurate and relevant for students.
