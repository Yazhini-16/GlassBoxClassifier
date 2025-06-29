# GlassBoxClassifier: Interpretable AI for Healthcare

This project builds an interpretable machine learning pipeline to predict diabetes using Logistic Regression, enhanced with **SHAP** and **LIME** to explain the model’s decisions — turning it into a transparent "glass box" model.  
It is inspired by real-world applications in healthcare and finance, where **understanding model decisions** is just as important as making accurate predictions.


# Project Highlights

- Binary classification using the Diabetes dataset (Pima Indians)
- SHAP (SHapley values) for global and local feature contributions
- LIME for individual prediction explanations
- Complete model lifecycle: training, evaluation, explanation
- Designed for ethical and explainable AI


# Motivation

Most machine learning models are treated as black boxes. But in sensitive domains like medicine or security, explainability is crucial. This project brings transparency by showing **why** a model makes a prediction — not just **what** it predicts.
> Built as part of my preparation for Master’s studies in Computer Science with a strong focus on **AI transparency and cybersecurity**.


# Technologies Used

- Python
- scikit-learn
- pandas
- SHAP
- LIME
- matplotlib
- Google Colab


# Visual Output

Plots and visualizations are saved in the `/images` folder:
- SHAP Summary Plot
- SHAP Waterfall Plot
- LIME Explanation


# How to Run

1. Open glassbox.ipynb in Google Colab
2. Install required packages from `requirements.txt`
3. Run the notebook cells step by step:
   - Load and preprocess the dataset
   - Train the model
   - Interpret the model using SHAP and LIME


# Built By

Yazhini M — Computer Science undergraduate, passionate about **AI prompting, cybersecurity**, and building ethical tech.

---
“A model that cannot explain itself should never make a life-changing decision.”
