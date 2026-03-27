# 🔧 Predictive Maintenance System

Production-ready ML system for Remaining Useful Life (RUL) prediction.

## Features
- LSTM Deep Learning Model
- MLflow Experiment Tracking
- SHAP Explainability
- FastAPI Deployment
- Docker Support
- Unit Testing

## Run Locally

1. Install dependencies:
pip install -r requirements.txt

2. Train model:
python src/train.py

3. Run API:
uvicorn api.main:app --reload

## API Endpoint
POST /predict → returns predicted RUL

## Tech Stack
- PyTorch
- MLflow
- FastAPI
- SHAP
- Docker

## Academic Relevance
- Deep Learning
- Explainable AI
- MLOps
- Production Deployment
