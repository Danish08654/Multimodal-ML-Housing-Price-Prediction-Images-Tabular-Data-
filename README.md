This project implements a Multimodal Machine Learning system to predict housing prices by combining:

1) Structured (tabular) data
2) House images

Unlike traditional models that rely only on numerical features, this approach leverages visual information + structured features to improve prediction performance.

 Objective

To build a robust regression model that:

1) Extracts features from images using CNN
2) Processes structured housing data
3) Combines both modalities (feature fusion)
4) Predicts house prices accurately

 Dataset

This project uses:

1) Housing Sales Dataset (tabular features like area, bedrooms, location, etc.)
   
2) Custom Image Dataset (house/room images)

⚙️ Methodology

 1. Data Preprocessing
Handled missing values
Scaled numerical features
Encoded categorical variables
Linked image paths with tabular data

 2. Image Feature Extraction (CNN)
Built a Convolutional Neural Network (CNN)
Extracted high-level visual features from house images

 3. Tabular Data Processing
Used structured features:
Area
Bedrooms
Bathrooms
Location
Condition
Applied scaling and encoding

 4. Feature Fusion (Core Step)
Combined:
CNN image features
Tabular features
 Created a multimodal representation

 5. Model Training   
Built a regression model using fused features
Trained using combined inputs

 6. Evaluation Metrics

Model performance evaluated using:
 MAE (Mean Absolute Error)
 RMSE (Root Mean Squared Error)

 Tech Stack
 
Python 
TensorFlow / Keras
Scikit-learn
NumPy / Pandas
Matplotlib

Future Improvements

Use pretrained models (ResNet, EfficientNet)
Improve dataset quality (better image-label mapping)
Hyperparameter tuning
Deploy with Streamlit
