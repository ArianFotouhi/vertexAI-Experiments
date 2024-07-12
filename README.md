# Vertex AI Experiments Repository

This repository contains scripts and configurations for experimenting with fine-tuning and testing different AI models using Vertex AI. The primary focus is on classification models, and it leverages Google Cloud Platform (GCP) services, particularly Vertex AI for orchestrating machine learning pipelines.

## Why Vertex AI Experimentss
Vertex AI Experiments is an essential tool for evaluating and optimizing various machine learning models. It allows you to test different models and fine-tune hyperparameters efficiently.

## Repository Structure

- `custom_training_job_component`: A custom training component for Vertex AI pipelines.
- `pipeline`: A DSL pipeline for Vertex AI.
- `experiment_runs`: Configuration for running multiple experiments with different hyperparameters and models.

## Requirements

To run the scripts in this repository, you need:

- Python 3.9
- Google Cloud SDK installed and configured
- Vertex AI API enabled in your GCP project
- Permissions to access Google Cloud Storage and Vertex AI

## Dependencies

The custom training job component uses the following Python packages:

- `google-cloud-aiplatform`
- `gcsfs`
- `xgboost`
- `category_encoders`
- `imblearn`
- `pandas`
- `google-cloud-storage`

## Setup

### Install Dependencies

You can install the required dependencies using pip:

```sh
pip install google-cloud-aiplatform gcsfs xgboost category_encoders imblearn pandas google-cloud-storage
```

## Results
![CC Image](https://github.com/ArianFotouhi/vertexAI-Experiments/blob/main/assets/vertexAI-1.png?raw=true)
![CC Image](https://github.com/ArianFotouhi/vertexAI-Experiments/blob/main/assets/vertexAI-2.png?raw=true)
![CC Image](https://github.com/ArianFotouhi/vertexAI-Experiments/blob/main/assets/vertexAI-3.png?raw=true)
![CC Image](https://github.com/ArianFotouhi/vertexAI-Experiments/blob/main/assets/vertexAI-4.png?raw=true)

