# UNHCR-Refugee-Flow

This project is a machine learning classification task using UNHCR refugee flow data. The goal is to predict the Protection Type (PT)—such as Asylum Seeker (ASY), Recognized Refugee (REF), Other International Protection (OIP), or Returned or Other Cases (ROC)—based on features like country of origin, asylum destination, asylum region, year, and refugee count.

## Objective
Build a classification model that predicts the Protection Type (PT) for each refugee flow record to:

Understand patterns in refugee movements and protection outcomes.

Assist in faster triage or profiling of cases based on historical data.

Explore the feasibility of deploying a real-world predictive tool for humanitarian insights.

## Results Snapshot
Random Forest (Tuned) achieved the best accuracy at 97.17%, with strong overall performance across classes, particularly the dominant class (ASY). Performance on minority classes (REF, ROC, OIP) was modest but acceptable considering the imbalance.

SVM with RBF kernel also reached 97.17% accuracy, but performed poorly on minority classes like ROC and OIP, despite strong results on ASY.

K-Nearest Neighbors (KNN) recorded an accuracy of 96.47% and offered relatively better balance between classes, but still lagged behind Random Forest in overall macro F1-score.

Logistic Regression came in with an accuracy of 95.53%, showing limited capability in capturing the nuances of the minority classes, especially REF and ROC.
