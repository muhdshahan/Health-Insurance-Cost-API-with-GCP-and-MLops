# health-insurance-price-prediction-gcp

## Description
This project implements a cloud-based API to predict health insurance charges using a Linear Regression model deployed on Google Cloud Platform (GCP). It leverages Cloud Run (or Cloud Functions) for serverless deployment, Google Cloud Storage for model storage, and Python for development.

## Features
- Predicts insurance charges based on BMI, number of children, smoking status, age category, and gender.
- Serverless API accessible via HTTP POST requests.
  
## Technologies
- Python (Pandas, Scikit-learn, NumPy), GCP (Cloud Run/Functions, Cloud Storage), Functions Framework.

## Installation 
- Clone this repository, install dependencies with **pip install -r requirements.txt**, and deploy using GCP CLI or Console.

## Usage
- Test the API with **python test.py** after updating the URL.

## Deployment Instructions
- Deploy manually in GCP Cloud Run (or Functions if available) with the inline editor or CLI: **gcloud run deploy predict-insurance-manual --region us-central1 --allow-unauthenticated --source**

## Image Preview
![Students Admission Report](https://github.com/muhdshahan/PJ5-Students-Admission-Report/blob/main/Students%20Admission%20Report.png)

## License
MIT License

Copyright (c) 2025 Muhammed Shahan P P

Permission is hereby granted, free of charge, to any person obtaining a copy...

## Contact
For questions, contact me at **shahuuraff@gmail.com** or connect on LinkedIn.
