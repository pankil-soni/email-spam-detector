# **Email Spam Detection App**

This Streamlit app is a robust email spam detection tool that leverages different machine learning models to predict whether an email is spam or not. Users can choose from various models, input email text directly, or upload a CSV file containing emails for bulk prediction.

# Links: 
- ### Link to the website: https://email-spam-detector-m.streamlit.app/

# Table of contents
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [About the Project](#about-the-project)
- [Screenshots](#screenshots)
- [Contact](#acknowledgements)
# Features
- Model Accuracies: Display the accuracy scores of different machine learning models.
- Predictions: Input email text or upload a CSV file for spam predictions.
- User-Friendly Interface: Streamlit UI ensures an intuitive and easy-to-use experience.

# **Getting Started**
## Clone the repository:

### Prerequisites
1. python3
2. git
3. pip

### Installation
```
git clone https://github.com/pankil-soni/email-spam-detector.git 
```
```
cd email-spam-detector
```

### Install the required dependencies:
```
pip install -r requirements.txt
```

### Run the Streamlit app:
```
streamlit run app.py
```

# Usage
### Text Input
1. Select "Text" as the input type.
2. Enter the email text in the provided text area.
3. Click the "Predict" button to get the spam prediction.

### CSV File Input
1. Select "CSV File" as the input type.
2. Upload a CSV file with a column named 'Email.'
3. The app will predict spam for each email and display the results.

## Model Selection
- ### Choose from the following machine learning models:

1. Logistic Regression
2. Random Forest Classifier
3. Support Vector Classifier (SVC)
3. Complement Naive Bayes

# About This Project
This project is designed for email spam detection, offering flexibility in model selection and input types. It provides an efficient way to analyze single emails or process bulk predictions from CSV files.

# Screenshots
![Streamlit - Google Chrome 11-01-2024 22_53_11](https://github.com/pankil-soni/email-spam-detector/assets/116267467/b2a1acf0-d6ba-4a83-9147-5cd33aa0dd6b)
![Streamlit - Google Chrome 11-01-2024 22_54_36](https://github.com/pankil-soni/email-spam-detector/assets/116267467/370cc9bc-ddb0-4fed-9f2b-1f612110e324)
![Streamlit - Google Chrome 11-01-2024 22_53_47](https://github.com/pankil-soni/email-spam-detector/assets/116267467/4a931bd3-4cdb-42e2-bf89-6a1a6b210676)
![Streamlit - Google Chrome 11-01-2024 22_54_17](https://github.com/pankil-soni/email-spam-detector/assets/116267467/4802e1aa-0a1d-4e2d-8346-e7f6e0d18f85)

# Contributing
Contributions are welcome! Please fork the repository and create a pull request.

# Acknowledgements
This project is created by pankil soni :
- github: https://github.com/pankil-soni
- linkedin : https://www.linkedin.com/in/pankil-soni-5a0541170/
- email : pmsoni2016@gmail.com
