Cover Type Classification

This project is a machine learning analysis to classify forest cover type based on cartographic data. The analysis is performed in a Jupyter notebook and uses common data science libraries like Pandas, NumPy, and Matplotlib.

Dataset

The model is trained on the covertype.csv dataset, which contains a variety of features including:

    Geographical Features: Elevation, Aspect, and Slope.

Distance Metrics: Horizontal distance to hydrology and roadways.

Soil Type: Forty different soil types (Encoded Them).

Target Variable: The Cover_Type, which is the variable the model aims to predict.

Analysis & Methodology

The Jupyter notebook demonstrates the following steps:

    Data Preprocessing: Initial checks for missing values to ensure data quality.

    Classification Models: Two tree-based models, XGBClassifier and Random Forest, were trained and compared.

    Model Comparison: The Random Forest model emerged as the superior performer, achieving an average of 95% across F1, recall, and precision metrics.
