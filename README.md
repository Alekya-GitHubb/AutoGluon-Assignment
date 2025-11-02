AutoGluon Assignment – Part 1

This repository demonstrates multiple AutoGluon use cases, including Kaggle datasets and official AutoGluon tutorials.
All notebooks were executed and verified in Google Colab, with outputs retained for evaluation as required in the assignment.

Repository Structure

AutoGluon-Assignment/
│
├── AutoGluon.ipynb                          # Main AutoGluon starter notebook
├── AutoGluon_Tabular_In_Depth.ipynb         # In-Depth Tabular Training
├── california_housing_autogluon.ipynb       # California Housing Model (Regression)
├── ieee_fraud_autogluon.ipynb               # IEEE Fraud Detection (Classification)
├── tabular_feature_engineering_autogluon.ipynb  # Auto Feature Engineering + Stacking
├── tabular_multimodal_autogluon.ipynb       # Multimodal Learning (text + numeric)
├── README.md                                # Project documentation
│
└── Part1/
    └── Tabular_QuickStart/
        └── tabular_quick_start_autogluon.ipynb   # Quick Start Tutorial

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

Video Walkthroughs (Google Drive Links)

- IEEE Fraud Detection — [](https://drive.google.com/file/d/1prGK-vlhfBFFZWLVmpqL10GpN7jEpSlx/view?usp=drive_link)
- California Housing — [](https://drive.google.com/file/d/1QGYy52e6AdkFIuvzpVS72deUFm6k7AvK/view?usp=sharing)
- Tabular Quick Start — [](https://drive.google.com/file/d/1z1OncShVrcx3bprDsEu0SClJhBf8s1J1/view?usp=drive_link)
- Tabular In-Depth —  [](https://drive.google.com/file/d/1rqRXundokcjHwn3poU1mjT9YyKauMlfs/view?usp=sharing)
- Tabular Multimodal — [](https://drive.google.com/file/d/1kOiafEa6OBUXJlBGhwczKqvRIfFi-wE_/view?usp=sharing)
- Feature Engineering — [](https://drive.google.com/file/d/1_HiaCdINxJzkmqvH5mRKDd5z0JyPnvUE/view?usp=drive_link)


  
