# Imperial-College-Capstone
Creating Capstone Project for Imperial College

NON-TECHNICAL EXPLANATION OF THE PROJECT
Our project aims to develop a machine learning-based breast cancer diagnostic model to assist medical professionals in early and accurate breast cancer detection. By analyzing various tumor features from medical images, the model can classify tumors as benign or malignant, aiding doctors in making informed decisions about patient care. The model is designed to be highly accurate, achieving a remarkable 96.49% classification accuracy. With this tool, healthcare providers can improve diagnostic precision, leading to timely treatment and better patient outcomes.

DATA
The data used for our model is sourced from the Breast Cancer Wisconsin (Diagnostic) Data Set from the UCI Machine Learning Repository. The dataset contains features extracted from digitized images of fine needle aspirate (FNA) of breast masses. It includes 30 different features, such as tumor size, shape, and texture. Each tumor is labeled as benign or malignant based on biopsy results.

MODEL
We employed a logistic regression model for breast cancer diagnosis. Logistic regression is a powerful and interpretable classification algorithm suitable for binary classification tasks like ours. It estimates the probability of a tumor being malignant based on the input features and makes predictions accordingly. Its simplicity and effectiveness made it a suitable choice for our project.

HYPERPARAMETER OPTIMIZATION
In the hyperparameter optimization phase, we focused on tuning the regularization strength (C) in the logistic regression model. We employed grid search, where we iterated over a range of values for C to find the optimal value that maximized the model's accuracy. This process helped us find the best combination of hyperparameters to achieve the highest performance for breast cancer diagnosis.

RESULTS
Our model achieved an impressive accuracy rate of 96.49% in classifying breast tumors as benign or malignant. This high accuracy ensures that the model can correctly identify cancer cases with a high level of confidence. It provides medical professionals with a reliable and efficient tool to support their diagnostic process, enabling early detection and timely treatment of breast cancer, ultimately leading to improved patient outcomes.

Screenshot

CONTACT DETAILS
For any inquiries or further discussions about the project, feel free to contact us on rishipal.gulati@gmail.com
