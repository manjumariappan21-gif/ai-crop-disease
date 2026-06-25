DEMO LINK:https://manjumariappan21-gif.github.io/ai-crop-disease/ai%20crop%20disease

PPT LINK:"C:\Users\HP\Downloads\crop-disease-main\AI CROP DISEASE(M.MANJU).pdf"

README CONTENT:
AI Crop Disease Prediction System:

Project Overview:

The AI Crop Disease Prediction System is a Machine Learning project designed to predict whether a crop is Healthy or Diseased based on environmental and crop-related parameters. This system helps farmers identify crop diseases early and take preventive measures to improve agricultural productivity.

The project uses a Decision Tree Classifier trained on crop data containing information such as crop type, disease name, temperature, humidity, soil moisture, and leaf color.

Objectives: Predict crop health status using Machine Learning. Analyze crop and environmental conditions. Provide quick disease detection support for farmers. Improve crop monitoring and decision-making. Technologies Used: Python Google Colab Pandas NumPy Scikit-learn Machine Learning (Decision Tree) Dataset Information:

The dataset contains the following attributes:

Column Name Description Crop Type of crop Disease Disease affecting the crop Temperature (°C) Environmental temperature Humidity (%) Humidity level Soil Moisture (%) Soil moisture percentage Leaf Color Color of the leaf Status Healthy / Diseased Sample Dataset Crop Disease Temperature Humidity Soil Moisture Leaf Color Status Rice Healthy 28 65 60 Green Healthy Rice Leaf Blast 31 85 72 Yellow Diseased Tomato Early Blight 32 82 58 Yellow Diseased Methodology: Step 1: Data Collection

Crop disease dataset was collected and stored in Excel format.

Step 2: Data Preprocessing Loaded dataset using Pandas. Converted categorical values into numerical format using Label Encoding. Selected relevant features and target variables. Step 3: Model Training Split dataset into training and testing sets. Trained a Decision Tree Classifier model. Step 4: Prediction Predicted crop health status. Evaluated model performance using accuracy score. Machine Learning Model:

Algorithm Used: Decision Tree Classifier

Reasons for selecting Decision Tree:

Easy to implement. Fast training process. Suitable for small datasets. Easy to visualize and explain

output: Accuracy: 1.0

Sample Predictions: Actual: Healthy | Predicted: Healthy Actual: Diseased | Predicted: Diseased Actual: Healthy | Predicted: Healthy Actual: Diseased | Predicted: Diseased Actual: Healthy | Predicted: Healthy

Prediction Example:

Input:

Crop = Rice Disease = Leaf Blast Temperature = 30°C Humidity = 80% Soil Moisture = 68% Leaf Color = Yellow

Output:

Prediction: Diseased image
<img width="842" height="306" alt="image" src="https://github.com/user-attachments/assets/66175612-10a0-4afe-8952-3530b11b672b" />





