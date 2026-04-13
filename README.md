This project implements a Multimodal Machine Learning system to predict housing prices by combining:

1) Structured (tabular) data

2) House images

Unlike traditional models that rely only on numerical features, this approach leverages visual information + structured features to improve prediction performance.

Objective

1) Extracts features from images using CNN

2) Processes structured housing data

4) Combines both modalities (feature fusion)

6) Predicts house prices accurately

 Dataset

This project uses:

1) Housing Sales Dataset (tabular features like area, bedrooms, location, etc.)
   
2) Custom Image Dataset (house/room images)

 Methodology

 1. Data Preprocessing

 2. Handled missing 
 
3.  Scaled numerical features

4.  Encoded categorical variables

5.  Linked image paths with tabular data

 3. Image Feature Extraction (CNN)
3.1 Built a Convolutional Neural Network (CNN)

3.2 Extracted high-level visual features from house images

 5. Tabular Data Processing
Used structured features:
Area
Bedrooms
Bathrooms
Location
Condition
Applied scaling and encoding

6. Feature Fusion (Core Step)
Combined:
CNN image features

Tabular 

Created a multimodal representation

5. Model Training
   
Built a regression model using fused features

Trained using combined inputs

6. Evaluation Metrics

Model performance evaluated using:
 
1) MAE (Mean Absolute Error)
 
2) RMSE (Root Mean Squared Error)

Tech Stack
 
1) Python 

2) TensorFlow / Keras

3) Scikit-learn

4) NumPy / Pandas

5) Matplotlib

