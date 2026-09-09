# iris_mlops
This demonstrates how MLOps work using Iris dataset and ML models created using it.

# Build the Project

Goal: establish a production-style ML repository before introducing automation.

Flow:
raw data -> preprocess -> train -> model artifact

Run:
```bash
pip install -r requirements.txt
python src/preprocess.py
python src/train.py
```
