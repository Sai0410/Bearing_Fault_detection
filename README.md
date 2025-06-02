# Bearing_Fault_detection
Machine Learning project for bearing fault classification using Random Forest and SVM

# OVERVIEW
This project uses vibration signal data from bearing to classify fault types (e.g. Inner Race, Outer Race, Ball Fault) using machine learning models like Random Forest and SVM. The code includes preprocessing, feature extraction, model training, visualization, and exporting ability for trained models for future use.

# REPOSITORY STRUCTURE
```
├── data/             # Raw and processed data files (CSV)
├── code/             # Google Colab notebooks and .py scripts
├── models/           # Exported models (.joblib)
├── visuals/          # PCA, t-SNE plots, accuracy graphs
├── README.md         # Project description and instructions
```

# FEATURES
- Signal preprocessing with noise.
- Statistical feature extraction from the time series segments.
- Train-test split and straitified K FOLD  cross-validation.
- Random Forest and SVM training and testing.
- Model performance visualization.
- PCA and t-SNE for data separation visualization.
- Model export using 'joblib'.

  # RESULTS
  -Random Forest Accuracy: 1.0
  -SVM Accuracy: 0.9
  -PCA and t-SNE plots show class separability
  -Classification reports and confusion matrices included

  # Future Additions/Work
  - Add more learning models, preferrably deep learning models
  - Automate hyperparamter tuning
  - Extend to real-time data
 
  # References/Acknowledgements
  -NASA Bearing Dataset (Case Western Reserve University)
