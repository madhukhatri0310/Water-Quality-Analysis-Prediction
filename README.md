# Water-Quality-Analysis-Prediction
This project is centered around the analysis and prediction of water potability using a dataset containing various chemical properties of water. The goal is to use machine learning to check if water samples are potable based on features such as pH, hardness, solids, chloramines, sulfate, conductivity, organic carbon, trihalomethanes, and turbidity.
Data Description:

The dataset consists of 3276 entries with 10 columns, each representing different chemical properties of water:

pH: pH of the water (0-14).
Hardness: Hardness of the water measured in mg/L.
Solids: Total dissolved solids in water measured in ppm.
Chloramines: Amount of chloramines in water measured in ppm.
Sulfate: Amount of sulfate in water measured in mg/L.
Conductivity: Conductivity of the water measured in μS/cm.
Organic_carbon: Amount of organic carbon in water measured in ppm.
Trihalomethanes: Amount of trihalomethanes in water measured in μg/L.
Turbidity: Turbidity of the water measured in NTU.
Potability: Indicates if the water is potable (1) or not (0).
Tools and Libraries Used:

Python: Primary programming language.
Pandas & NumPy: For data manipulation and numerical analysis.
Seaborn & Matplotlib: For data visualization.
Plotly: For interactive plots.
Scikit-Learn: For machine learning model building, training, and evaluation.
Exploratory Data Analysis (EDA):

Statistical summary and data type inspection.
Visualization of distributions and relationships between features.
Analysis of missing values and imputation where necessary.
Predictive Modeling:

Splitting data into training and testing sets.
Feature scaling to normalize data.
Training multiple models including Logistic Regression, Random Forest, SVM, Gradient Boosting, and Neural Networks.
Evaluation of models based on accuracy, precision, recall, F1-score, and ROC AUC
