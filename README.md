# P08 - Dockerized Delivery Time Prediction API

## Project Overview
This project demonstrates how to package a machine-learning delivery-time prediction API using Docker.

## Technologies
- Python
- FastAPI
- Scikit-learn
- Docker
- Jupyter Notebook

## Files
- P08.ipynb: Practical notebook and task execution.
- work/app.py: Prediction API.
- work/model.joblib: Trained prediction model.
- work/requirements.txt: Python dependencies.
- work/Dockerfile.v2: Corrected Dockerfile.
- work/.dockerignore.mine: Docker ignore patterns.

## How to Run
Build the Docker image using the corrected Dockerfile:

```bash
docker build -f work/Dockerfile.v2 -t delivery-api:2.0 work/
