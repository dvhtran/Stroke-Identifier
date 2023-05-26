**Stroke Prediction Machine Learning Model

**Project Description

Stroke is a serious medical condition that requires early detection for timely medical intervention and optimal patient outcomes. This project aims to create a machine learning model for early stroke detection, focusing on various causative factors. The model assists clinical teams in predicting or assessing the risk of stroke occurrence, enabling timely medical intervention, minimizing brain damage, preventing long-term disabilities, identifying underlying causes, and facilitating quick medical decision-making.

**Data Overview

The stroke dataset comprises patients' medical records, including demographics, medical history, lifestyle factors, and the presence or absence of a stroke. It provides a comprehensive set of information for analysis and prediction.

**Built With

Python and Packages (e.g., scikit-learn, matplotlib, seaborn, pickle)
Flask
HTML
CSS
Getting Started
Prerequisites
Make sure you have the following prerequisites installed on your development machine:

**Git**

Python and set up your virtual environment
Install Flask globally using the command: pip install flask
Your favorite code editor (e.g., VScode)
Your favorite browser (e.g., Google Chrome)
Installation
Clone this repository and save it in your local directory. Run the following command in the terminal:
bash
Copy code
git clone https://github.com/dvhtran/Stroke-Identifier.git
Start the Flask app by running the following command in the terminal:
Copy code
python app.py
Visit localhost:5000 in your browser and enjoy!
Machine Learning Pipeline
Data Collection
The dataset used for this project was collected from Kaggle.

**Model Selection

The Random Forest Classifier was chosen for this problem due to its high accuracy in classification tasks. It is a popular choice in the healthcare and medical industry, where precise and reliable predictions are crucial.

**Exploratory Data Analysis (EDA)

Several interesting observations were made during the EDA phase, including data distribution analysis, examination of the target variable, handling missing values, and addressing data imbalances.

**Data Preprocessing

The data was cleaned and prepared for analysis. This involved handling missing values, encoding categorical variables, applying feature scaling, and dividing the data into training and testing sets.

**Model Training

Three models were trained using different resampling methods to handle imbalanced data.

**Evaluation

The performance of the models was assessed using accuracy scores, confusion matrices, and classification reports. The selected model, Model 1, demonstrated superior performance overall.

**Model Deployment with Flask

The model was implemented in the Flask application to handle incoming requests. A web-based UI was created using HTML and CSS to provide an interactive experience for users.

Credits
Kevin Lee
Kaggle
UC Berkeley Extension Data Analytics Bootcamp


