# Parkinson’s Disease Detection Using Support Vector Machine (SVM)
📖 Project Overview

Parkinson’s disease is a progressive neurological disorder that often presents with subtle speech abnormalities in its early stages. This project applies machine learning (Support Vector Machine) to biomedical voice measurements in order to classify individuals as Parkinson’s disease positive or healthy controls.

The goal is to demonstrate how non-invasive voice features, combined with robust evaluation metrics, can support early screening and clinical decision-making, especially in low-resource or telemedicine settings.

🎯 Objectives

Build a reliable classification model to detect Parkinson’s disease using voice features

Evaluate performance using clinically meaningful metrics beyond accuracy

Assess generalizability using cross-validated ROC–AUC

Demonstrate the potential of ML as a clinical decision support tool

📊 Dataset

Biomedical voice measurements extracted from sustained phonations

Features include jitter, shimmer, noise ratios, pitch measures, and nonlinear speech dynamics

Target variable: Parkinson’s disease status (Yes / No)

⚙️ Methodology

Data preprocessing and feature scaling

Train–test split

Support Vector Machine (SVM) modeling

Model evaluation using:

Classification report

ROC–AUC

Cross-validated ROC–AUC

📈 Key Performance Metrics

Test Accuracy: ~87%

ROC–AUC: ~0.82

Cross-Validated ROC–AUC: ~0.90

Precision & Recall: Well balanced, indicating reliable detection with limited false positives and false negatives

These results suggest strong discriminatory ability and good generalization performance.

📉 Model Evaluation Visuals


Figure 1: ROC–AUC Curve

![ROC_Curve']([Insert ROC curve image here]

Figure 2: Confusion Matrix

[Insert confusion matrix here]

Figure 3: Feature Distribution / Scaling Visualization

[Insert feature plot here]

⚠️ Limitations & Room for Improvement

Dataset size is relatively small, limiting external generalizability

Data originates from a single source; population diversity is limited

SVM model interpretability is limited compared to tree-based models

Class imbalance may still subtly affect prediction thresholds

🚀 Next Steps

Compare performance with ensemble models (Random Forest, XGBoost)

Apply feature importance and SHAP for clinical interpretability

Tune decision thresholds to optimize recall for early screening

Validate the model on external or real-world clinical datasets

Explore deployment for telemedicine and remote monitoring use cases

🏥 Clinical Relevance

This model is not a replacement for clinical diagnosis, but a decision support and screening tool that can:

Support early referral

Aid neurologists in borderline cases

Enable remote and population-level screening

🔗 Project Links

GitHub Repository: [INSERT GITHUB LINK HERE]

LinkedIn Profile: [INSERT LINKEDIN LINK HERE]

✍️ Author

Andy Okebugwu, PhD
Public Health | Data Analytics | Machine Learning in Healthcare
