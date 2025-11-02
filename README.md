AutoGluon Assignment

This repository showcases end-to-end AutoML workflows using AutoGluon, including Kaggle problems and official AutoGluon tutorials.
All notebooks were executed in Google Colab, and results (output cells, metrics & leaderboards) are preserved as required.

Repository Structure

AutoGluon-Assignment/
│
├── AutoGluon.ipynb                               # Intro notebook
├── AutoGluon_Tabular_In_Depth.ipynb              # Advanced tabular modeling
├── california_housing_autogluon.ipynb            # Regression demo (Kaggle California Housing)
├── ieee_fraud_autogluon.ipynb                    # Fraud detection (Kaggle IEEE)
├── tabular_feature_engineering_autogluon.ipynb   # Automated feature engineering + stacking
├── tabular_multimodal_autogluon.ipynb            # Multimodal learning (text + numeric)
│
└── Part1/
    └── Tabular_QuickStart/
        └── tabular_quick_start_autogluon.ipynb   # Quick start tutorial

        | Notebook                                      | Problem Type            | Goal                                                         |
| --------------------------------------------- | ----------------------- | ------------------------------------------------------------ |
| `ieee_fraud_autogluon.ipynb`                  | Classification (Kaggle) | Detect fraudulent transactions                               |
| `california_housing_autogluon.ipynb`          | Regression (Kaggle)     | Predict median house values                                  |
| `tabular_quick_start_autogluon.ipynb`         | Tabular QuickStart      | 1-line AutoML training & leaderboard                         |
| `AutoGluon_Tabular_In_Depth.ipynb`            | Advanced Tabular        | Best-quality training, time-limit tuning, feature importance |
| `tabular_multimodal_autogluon.ipynb`          | Multimodal              | Train on numeric + category + text features                  |
| `tabular_feature_engineering_autogluon.ipynb` | Feature Engineering     | Auto-generated features + model stacking                     |


How to Run:
1.Open any notebook in Google Colab.
2.Ensure AutoGluon is installed:
    !pip install autogluon
3.Run all cells (Runtime → Run all).
4.All outputs and leaderboards are saved automatically.


| Key Evaluation Metrics |
|------------|-----------|
| Metric | Description |
| Accuracy / ROC-AUC | Used for classification tasks (IEEE, Quick Start, In-Depth, Multimodal).|
| RMSE / R²	| Used for regression (California Housing).|
| Feature Importance | Explains most influential features for model prediction.|


Video Walkthroughs (Google Drive Links)

| Notebook | Video Link |
|---------|-----------|
| IEEE Fraud Detection | [Watch Video](https://drive.google.com/file/d/1prGK-vlhfBFFZWLVmpqL10GpN7jEpSlx/view?usp=drive_link) |
| California Housing | [Watch Video](https://drive.google.com/file/d/1QGYy52e6AdkFIuvzpVS72deUFm6k7AvK/view?usp=sharing) |
| Tabular Quick Start | [Watch Video](https://drive.google.com/file/d/1z1OncShVrcx3bprDsEu0SClJhBf8s1J1/view?usp=drive_link) |
| Tabular In-Depth | [Watch Video](https://drive.google.com/file/d/1rqRXundokcjHwn3poU1mjT9YyKauMlfs/view?usp=sharing) |
| Tabular Multimodal | [Watch Video](https://drive.google.com/file/d/1kOiafEa6OBUXJlBGhwczKqvRIfFi-wE_/view?usp=sharing) |
| Feature Engineering | [Watch Video](https://drive.google.com/file/d/1_HiaCdINxJzkmqvH5mRKDd5z0JyPnvUE/view?usp=drive_link) |


  
