
# MLFlow with MLOps automation

This project uses this tutorial:
https://mlflow.org/docs/latest/getting-started/intro-quickstart/index.html

Video explains in first 25 minutes the basics of MLFlow: https://www.youtube.com/watch?v=6ngxBkx05Fs

## Getting started

1. Clone the repository

2. Install dependencies
> uv sync

3. Start mlflow server
> uv run mlflow server --host 127.0.0.1 --port 5000

4. Run the example notebook/code of your choice (lr.ipynb or logistic_regression_script.py)


## Torch

*Note: torch as a dependency currently loads the cuda (over 2Gb)*

Depending on your environment, torch migth need to be configured in pyproject.toml differently, for example for using CPU: https://docs.astral.sh/uv/guides/integration/pytorch/#using-a-pytorch-index
