# UNHCR-Refugee-Flow

This project is a machine learning classification task using UNHCR refugee flow data. The goal is to predict the Protection Type (PT)—such as Asylum Seeker (ASY), Recognized Refugee (REF), Other International Protection (OIP), or Returned or Other Cases (ROC)—based on features like country of origin, asylum destination, asylum region, year, and refugee count.

## Objective
Build a classification model that predicts the Protection Type (PT) for each refugee flow record to:

Understand patterns in refugee movements and protection outcomes.

Assist in faster triage or profiling of cases based on historical data.

Explore the feasibility of deploying a real-world predictive tool for humanitarian insights.

Model | Accuracy | Macro F1 | Notes
Random Forest (tuned) | 0.9717 | 0.66 | Best overall performance
SVM (RBF) | 0.9717 | 0.47 | Great on ASY, poor on others
KNN | 0.9647 | 0.57 | Balanced but weaker on rare classes
Logistic Regression | 0.9553 | 0.50 | Limited multiclass capacity
