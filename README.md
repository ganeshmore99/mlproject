# End-to-End Student Performance Prediction
This project aims to predict student performance using various machine learning techniques. The project follows an end-to-end machine learning pipeline from data preprocessing, model training, evaluation, and deployment using MLOps tools.

![Student_AIM](https://github.com/ganeshmore99/mlproject/assets/85934803/471d16c0-d6c5-49d8-8f68-666bdfe71e94)

## Table of Contents
#### Introduction
#### Repository Setup
#### Project Template Creation
#### Project Setup and Requirements Installation
#### Logging, Utils, and Exceptions Modules
#### Components Modular Code Implementation
#### Training Pipeline
#### MLOps Tools Implementation
#### Prediction Pipeline and User App Creation
#### Docker
#### GitHub Actions
#### Final CI/CD Deployment on Heroku

## Introduction
This project aims to build a robust machine learning model to predict student performance based on various features. The complete workflow includes data preprocessing, model training, evaluation, deployment, and continuous integration/continuous deployment (CI/CD) using MLOps tools.

## Repository Setup
To get started, clone the repository:
```
git clone https://github.com/your-username/student-performance-prediction.git
cd student-performance-prediction
```

## Project Template Creation
A project template helps in organizing the code and maintaining a standard structure. The structure includes directories for data, notebooks, scripts, and more.

## Project Setup and Requirements Installation
Set up the virtual environment and install the necessary dependencies:

```
conda create -p venv pyhon=3.8 -y
```
```
pip install -r requirements.txt
```

## Logging, Utils, and Exceptions Modules
Logging: Set up logging to track the progress and catch any issues.<br />
Utils: Utility functions for data processing and other repetitive tasks.<br />
Exceptions: Custom exception handling to manage errors gracefully.<br />
Components Modular Code Implementation<br />
Each component of the machine learning pipeline is implemented in a modular fashion to enhance code readability and maintainability. This includes:

Data ingestion<br />
Data preprocessing<br />
Feature engineering<br />
Model training<br />
Model evaluation<br />
Training Pipeline<br />
The training pipeline orchestrates the flow of data from ingestion to preprocessing, feature engineering, model training, and evaluation.

## MLOps Tools Implementation
Implement various MLOps tools to ensure smooth deployment and monitoring of the machine learning models. This includes tools like MLflow for tracking experiments and Docker for containerization.

## Prediction Pipeline and User App Creation
Develop a prediction pipeline that uses the trained model to make predictions on new data. Additionally, create a user-friendly application for users to interact with the model.

## Docker
Containerize the application using Docker to ensure consistency across different environments. To build and run the Docker container:

```
docker build -t student-performance-prediction .
docker run -p 5000:5000 student-performance-prediction
```
## GitHub Actions
Set up GitHub Actions for continuous integration and continuous deployment (CI/CD). This ensures that the project is automatically tested and deployed whenever changes are pushed to the repository.

## Final CI/CD Deployment on Heroku
Deploy the final application on Heroku using CI/CD pipelines. This allows the application to be accessible online and ensures that updates are automatically deployed.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

