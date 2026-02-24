________________________
This project is going to be a complete END-END ML WORKFLOW, following the steps of: 
  Data Versioning → DVC
  Data Validation → Great Expectations
  Model Tracking → MLflow
  Monitoring & Drift Detection → NannyML
  Retraining Pipeline → Automated Trigger
  Deployment → FastAPI + Docker
  CI/CD → GitHub Actions
__________________________________
Dataset used, Using the Standard for MLOps: https://www.kaggle.com/datasets/adarshsng/lending-club-loan-data-csv
__________________________________

# Setup directories for CI/CD pipeline
1. data       - to be ignored by git and tracked by dvc
2. src        - Has the Train.py, Predict.py, validate.py
3. tests      - Unit Testing for different parts of the pipeline
4. deployment - Docker with fastAPI/streamlit 
5. .github/workflows - CI/CD YAML files

__________________________

