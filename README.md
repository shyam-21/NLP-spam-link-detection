## Link to Kaggle Notebook files:
- https://www.kaggle.com/code/shyamsudheer/nlp-final-project-urldecomposition-bert
- https://www.kaggle.com/code/shyamsudheer/nlp-project-count-vectorizer
- https://www.kaggle.com/code/shyamsudheer/nlp-project-tf-idf
- https://www.kaggle.com/code/shyamsudheer/nlp-final-project-data-visualizations

## Link to Dataset:
- https://www.kaggle.com/datasets/sid321axn/malicious-urls-dataset

## Link to Deployment site:
- http://3.135.241.192:8000/

## Link to Deployment Github code:
- https://github.com/prasanthsagarkottakota/urldetection

## Link to ML model: 
- https://drive.google.com/drive/folders/1iz02ipt_RzCA12JY0ey7dB3J_uOPCfjs?usp=sharing

Malicious URL Detection using NLP and ML

## Overview

This project aims to enhance cybersecurity by developing a system that can classify URLs as safe or malicious using advanced Natural Language Processing (NLP) and Machine Learning (ML) techniques. The system leverages the BERT embeddings and traditional models like Random Forest for accurate threat analysis and is deployed on a Django-based website for real-time user feedback.

## Features:

URL Input: Users can input any URL they intend to visit into the system.
Data Preprocessing: Techniques like removing slashes, https://, and numerical information.
Feature Engineering: Creation of attributes specific to URLs like length, TLD, etc.
NLP Techniques: Use of BERT tokenizer and embedding, TF-IDF, Count Vectorizer, etc.
Machine Learning Models: Algorithms like Random Forest, Logistic Regression, SVM, etc.
Safety Assessment: Classification of URLs into safe or malicious categories.
Deployment: Deployed as a website using the Django framework for real-time interaction.
Continuous Learning: Periodic model updates based on new data.

## Project Structure:

/input: Contains the dataset used for the project.
/notebooks: Jupyter notebooks for data preprocessing, feature extraction, and model training.
/src: Source code for the Django web application.
/static: Static files for the web application.
/templates: HTML templates for the web application.
requirements.txt: List of dependencies.

## Setup Instructions

- Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/malicious-url-detection.git
cd malicious-url-detection

- Install the required dependencies:
bash
Copy code
pip install -r requirements.txt

- Run the Django server:
bash
Copy code
python manage.py runserver

- Access the application at http://127.0.0.1:8000.
  
Methodologies
Data Preprocessing
Cleaning and transforming URL data.
Tokenizing URLs using BERT and traditional methods.
Feature Engineering
Extracting URL components and creating features like URL length, hostname length, etc.
Machine Learning Models
Implementing and evaluating models like Random Forest, Logistic Regression, SVM, etc.
Deployment
The application is deployed using Django, providing a user-friendly interface for real-time URL classification.
Results
The system demonstrated high accuracy in classifying URLs as safe or malicious.
Evaluation metrics like accuracy, precision, recall, and F1-score indicated robust model performance.
Future Work
Continuously update the model with new data.
Integrate real-time data analysis for improved threat detection.
Expand data sources for more comprehensive threat analysis.

Contributors:
Shyam Sudheer Nadella
Prasanth Sagar Kottakota
Sri Krishna Chaitanya Chivatam
Vaibhav Krishna Joshi
Uday Kumar Putta
