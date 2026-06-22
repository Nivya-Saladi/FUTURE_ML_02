# Support Ticket Classification System
## Project Overview
The objective of this project is to automatically classify support tickets into different categories using Natural Language Processing (NLP) and Machine Learning techniques. Automating ticket classification helps organizations improve response time, prioritize requests, and route issues to the appropriate teams.

## Dataset
IT Support Ticket Dataset
* Total Records: 47,837
* Number of Categories: 8

### Categories
* Hardware
* HR Support
* Access
* Miscellaneous
* Storage
* Purchase
* Internal Project
* Administrative Rights

## Project Workflow
### 1. Data Cleaning and Preprocessing
* Checked and handled missing values.
* Removed invalid records.
* Prepared text data for machine learning.

### 2. Feature Extraction
Text features were extracted using **TF-IDF Vectorization** with:
* Unigrams and Bigrams
* Maximum 15,000 features
* Minimum document frequency of 2
* Sublinear term frequency scaling

### 3. Model Building
Two classification models were tested:
* Logistic Regression
* Linear Support Vector Machine (Linear SVM)

### 4. Model Evaluation
The models were evaluated using:
* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

### 5. Best Model
Logistic Regression achieved the best performance with an accuracy of:
85.9%

## Visualizations
The project includes:
* Ticket Category Distribution
* Confusion Matrix
* Classification Performance Metrics
* Sample Ticket Predictions
These visualizations help understand the dataset and evaluate model performance.


## Business Applications
Support ticket classification systems can help organizations:
* Automatically route tickets to the appropriate department.
* Reduce manual effort and response time.
* Improve customer support efficiency.
* Prioritize issue resolution.
* Enhance user experience and operational productivity.


## Technologies Used
* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

## Future Improvements
* Experiment with advanced NLP models such as BERT and DistilBERT.
* Deploy the model as a web application.
* Integrate real-time ticket prediction.
* Incorporate sentiment analysis for priority estimation.

Machine Learning Intern – Future Interns
