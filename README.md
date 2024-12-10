## End To End Machine learning Project on AWS Sagemaker

**Tech Stack and tools used: Python, scikit-learn, Amazon Web Services (AWS) SageMaker,SageMaker Endpoints, S3, pandas, joblib, Git**

## Mobile Price Classification using Random Forest

This project implements a machine learning model to predict mobile phone price ranges using a Random Forest classifier. The model is trained on various features of mobile phones and deployed as an endpoint on Amazon SageMaker for real-time predictions.

### Project Overview

The main components of this project include:

1. **Data Preparation**: The dataset contains various features of mobile phones, such as battery power, RAM, camera quality, etc., along with their corresponding price range categories.

2. **Model Training**: A Random Forest classifier is trained using the scikit-learn library on Amazon SageMaker. The model is configured with 100 estimators and a fixed random state for reproducibility. 

3. **Model Deployment**: The trained model is deployed as an endpoint on Amazon SageMaker, allowing for real-time predictions.

### Key Features

- **Custom Training Script**: A custom training script (`script.py`) is used to define the model training process, including data loading, preprocessing, and model evaluation.

- **SageMaker Integration**: The project leverages Amazon SageMaker for model training, artifact storage, and deployment.

- **Performance Metrics**: The model's performance is evaluated using accuracy and a detailed classification report, providing insights into precision, recall, and F1-score for each price range category.

### Model Performance

The Random Forest classifier achieved the following performance on the test dataset:

- **Accuracy**: 87.5%
- **Precision, Recall, and F1-score**: Varies by price range category, with generally high performance across all categories.


### Future Improvements

- Experiment with hyperparameter tuning to optimize model performance.
- Implement feature importance analysis to identify the most influential factors in price prediction.
- Explore other machine learning algorithms for comparison.

This project demonstrates the end-to-end process of building, training, and deploying a machine learning model for mobile price classification using Amazon SageMaker and S3 services.

**Proof of deployment:**

![Screenshot 2024-12-10 at 12 03 32 AM](https://github.com/user-attachments/assets/87505ba5-81e6-46d6-bec6-e0eb7587075f)


![Screenshot 2024-12-10 at 12 03 11 AM](https://github.com/user-attachments/assets/8305b9c0-0d0e-41b3-8591-3b788e9b33a0)


