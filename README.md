# AWS SageMaker Data Training

This repository contains a tutorial on how to build, train, and deploy a Scikit-learn model using AWS SageMaker with a custom training script.

## Overview

This project demonstrates the following steps:
1. **Initialize Boto3 SDK and Create S3 Bucket**: Set up the AWS environment.
2. **Upload Data to SageMaker Local Storage**: Prepare and upload data for training.
3. **Data Exploration and Understanding**: Analyze the dataset.
4. **Split Data into Train/Test Sets**: Prepare data for model training.
5. **Upload Data to S3 Bucket**: Store data in S3 for SageMaker access.
6. **Create a Training Script**: Write a custom script for model training.
7. **Train Model in SageMaker Container**: Execute the training script in SageMaker.
8. **Store Model Artifacts in S3**: Save the trained model.
9. **Deploy SageMaker Endpoint**: Create an endpoint for model inference.

## Prerequisites

- AWS Account
- Python 3.8+
- Boto3
- Scikit-learn
- AWS CLI configured

## Usage

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/longmen2019/AWS-SageMaker-Data-Training.git
    cd AWS-SageMaker-Data-Training
    ```

2. **Run the Jupyter Notebook**:
    Open `Tutorial - 1 Sagemaker SKlearn Custom Script.ipynb` in Jupyter Notebook and follow the steps.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- AWS SageMaker Documentation
- Scikit-learn Documentation

## Contact

For any questions or issues, please open an issue in this repository.
