# AI-Health-Triage

AI Triage Assistant

The AI Triage Assistant is a decision-support tool designed to optimize medical resource allocation and enhance patient safety. By utilizing Natural Language Processing (NLP), the system classifies user-described symptoms into three urgency levels: Red (Emergency), Yellow (Urgent), and Green (Routine).

Project Overview
This project was developed for the AI Programming (MBAI 5310G) course at Ontario Tech University. It demonstrates the practical application of AI in healthcare, specifically focusing on building a classification system that interprets clinical narratives to recommend appropriate levels of care.

Key Features:
Feature Engineering: Creates "Smart Profiles" by combining patient age, gender, symptom onset, context, and duration into a clinical narrative.


NLP Vectorization: Utilizes TfidfVectorizer to transform raw text into numerical data for model processing.


Neural Network Classifier: A Sequential model built with Keras/TensorFlow featuring Dense and Dropout layers for robust classification.


Interactive Triage System: An integrated UI using ipywidgets that allows users to input clinical data and receive real-time urgency recommendations with confidence scores.


Dataset
The model is trained on the Medical Triage 500 dataset, which consists of clinical descriptions and their corresponding triage levels.
Source: Hugging Face - Medical Triage 500


Performance
The current model achieves a high level of accuracy in clinical urgency prediction:
Final Accuracy: ~89%


Precision (Red): 0.93


Recall (Red): 0.96


Technology Stack
Languages: Python


Libraries: Pandas, NumPy, Scikit-learn, TensorFlow/Keras


UI/Interface: Ipywidgets, IPython Display


Platform: Jupyter Notebook



License & Integrity
This project is submitted as individual work for MBAI 5310G. It adheres to the Academic Integrity Policy of Ontario Tech University. Open-source libraries and frameworks used are credited within the source code.
