AutoGluon Assignment – Part 1

This repository demonstrates multiple AutoGluon use cases, including Kaggle datasets and official AutoGluon tutorials.
All notebooks were executed and verified in Google Colab, with outputs retained for evaluation as required in the assignment.

Repository Structure






Kaggle Projects
Notebook	                Objective
IEEE Fraud Detection	    Detect fraudulent transactions using AutoGluon’s binary classification on the Kaggle IEEE dataset.
California Housing	      Predict median house prices using AutoGluon’s regression model.

AutoGluon Tutorials
Notebook	              Focus
Tabular Quick           Start	Demonstrates AutoGluon’s one-line model training and leaderboard generation.
Tabular In-Depth	      Explores presets, time limits, and feature importance analysis.
Tabular Multimodal	    Handles datasets combining numeric, categorical, and text features.
Feature Engineering	    Shows AutoGluon’s automated feature generation and model stacking.

How to Run:
1.Open any notebook in Google Colab.
2.Ensure AutoGluon is installed:
    !pip install autogluon
3.Run all cells (Runtime → Run all).
4.All outputs and leaderboards are saved automatically.

Key Evaluation Metrics
Metric	                Description
Accuracy / ROC-AUC	    Used for classification tasks (IEEE, Quick Start, In-Depth, Multimodal).
RMSE / R²	              Used for regression (California Housing).
Feature Importance	    Explains most influential features for model prediction.


Video Demonstrations:
  Each notebook has a 1–2 minute walkthrough video explaining:
  Dataset overview
  Model training process
  Output and leaderboard interpretation
All videos are available in the /videos/ directory.



  
