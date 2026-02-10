#  Patient Care Classification System
This project focuses on classifying patients into two categories:
    Out Care -> Requires hospitalization
    In Care -> Suitable for home care
    The classification is based on various health indicators, and machine learning models are used to make accurate predictions.

##  Dataset

The dataset used is PatientCare.csv, which contains patient details such as:
Demographics: Gender, Age
Health Parameters:
    HAEMATOCRIT
    HAEMOGLOBINS
    ERYTHROCYTE
    LEUCOCYTE
    THROMBOCYTE
    MCH
    MCHC
    MCV

## Preprocessing
Gender is encoded as:
    1 → Male
    0 → Female
Performed Exploratory Data Analysis (EDA) with:
    Count plots
    Distribution plots
    Feature relationships

## Model Training
The dataset is split into training and testing sets.
- Three models are trained and evaluated:
    Decision Tree
    Random Forest
    Logistic Regression
- Performance is measured using:
    Accuracy Score
    Confusion Matrix
    Classification Report

## Streamlit Application
A user-friendly Streamlit app is built for real-time predictions.
     Features:
        Users input their health parameters via a web form
        The trained Random Forest Model predicts whether the patient requires:
        In Care (Hospitalization)
        Out Care (Home Care)

    Displays both user input and prediction results

## How to Run the App
1. Install required libraries:
       type in terminal or command `pip install numpy pandas matplotlib seaborn streamlit scikit-learn` or `pip install -r  requirements.txt`
    
2. Run the Streamlit app using the command: `streamlit run streamlit_app.py`.

## Note
- Model performance metrics (confusion matrices & classification reports) are included in the Jupyter Notebook.

- Ensure the dataset is available at the correct path.
- Modify paths or parameters if needed for your local environment.

## Author 
[LinkedIn Profile](https://www.linkedin.com/in/piyushkumar451)
