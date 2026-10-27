# MLOps: Theory and Hands-on Implementation

A hands-on learning repository covering essential MLOps concepts, tools, and workflows required to build, deploy, monitor, and maintain reliable machine learning systems.

This repository includes theoretical explanations and practical implementations using Google Colab, with a customer churn prediction model as the running example.

## 📌 Topics Covered

### 1. MLOps Fundamentals
- Introduction to MLOps and its importance
- End-to-end machine learning lifecycle
- Traditional ML workflow vs. MLOps workflow
- Reproducibility and automation

### 2. Experiment Tracking
- Tracking model parameters, metrics, and artifacts
- Comparing multiple training experiments
- Implementing experiment tracking using MLflow

### 3. Model Versioning
- Maintaining multiple trained model versions
- Saving and loading models using Joblib
- Storing model metadata and evaluation metrics

### 4. Data Versioning with DVC
- Understanding data versioning
- Git vs. DVC
- Tracking dataset changes
- Introduction to DVC remotes and reproducible workflows

### 5. Model Registry
- Understanding the model lifecycle
- Registering trained models using MLflow
- Managing model versions and metadata
- Loading registered models for inference

### 6. Model Deployment
- Understanding batch and online inference
- Building a prediction API using FastAPI
- Testing model predictions through HTTP requests

### 7. Model Monitoring
- Monitoring accuracy, precision, recall, and F1-score
- Understanding data quality and system health monitoring
- Implementing basic performance checks and alerts

### 8. Drift Detection
- Data drift
- Concept drift
- Prediction drift
- Detecting distribution changes using the Kolmogorov–Smirnov (KS) test
- Understanding when model retraining may be necessary

### 9. CI/CD for Machine Learning
- Continuous Integration and Continuous Delivery/Deployment
- Automated testing using Pytest
- Creating a GitHub Actions workflow
- Understanding model quality gates

### 10. MLflow
- Experiment tracking
- Logging parameters, metrics, and artifacts
- Model logging and registry integration
- Loading registered model versions

### 11. Docker
- Containers and images
- Writing a Dockerfile for an ML application
- Packaging a FastAPI model-serving application
- Building and running container images

### 12. Kubernetes Basics
- Clusters, nodes, and Pods
- Deployments and Services
- Readiness and liveness probes
- Scaling application replicas
- Deploying a containerized ML API

## 🛠️ Tech Stack

- **Language:** Python
- **ML Libraries:** Scikit-learn, NumPy, Pandas
- **Experiment Tracking & Model Registry:** MLflow
- **Data Versioning:** DVC, Git
- **Model Serialization:** Joblib
- **API Development:** FastAPI
- **Testing:** Pytest
- **CI/CD:** GitHub Actions
- **Containerization:** Docker
- **Container Orchestration:** Kubernetes
- **Environment:** Google Colab

## 🧪 Practical Implementation

The hands-on examples use a customer churn classification workflow.

The implementation covers:

1. Generating a dataset and training machine learning models.
2. Comparing experiments using MLflow.
3. Saving versioned models and metadata.
4. Tracking dataset changes with DVC.
5. Registering and loading models through MLflow.
6. Building a FastAPI prediction endpoint.
7. Evaluating model performance and implementing basic monitoring.
8. Detecting simulated data drift using the KS test.
9. Writing automated tests and a GitHub Actions CI workflow.
10. Creating Docker and Kubernetes configuration files for deployment.

## 🔄 End-to-End MLOps Workflow

```text
Data Collection and Validation
            ↓
Data Versioning (DVC)
            ↓
Model Training and Evaluation
            ↓
Experiment Tracking (MLflow)
            ↓
Model Versioning and Registry
            ↓
Automated Testing (Pytest)
            ↓
CI/CD (GitHub Actions)
            ↓
Containerization (Docker)
            ↓
Deployment (FastAPI + Kubernetes)
            ↓
Monitoring and Drift Detection
            ↓
Retraining and Model Improvement
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd <YOUR_REPOSITORY_NAME>
```

### 2. Install dependencies

```bash
pip install mlflow scikit-learn pandas numpy joblib fastapi uvicorn requests scipy dvc pytest
```

### 3. Run the implementations

Open the provided notebook in Google Colab and execute the cells in order.

The notebook covers model training, experiment tracking, versioning, model registration, deployment, monitoring, and drift detection.

### 4. Run the deployment examples

The FastAPI example can be tested in a suitable Python environment. Docker and Kubernetes examples require a Docker-enabled environment and, for Kubernetes deployment, access to a configured cluster.

## 🎯 Learning Outcomes

Through this implementation, I explored:

- Reproducible machine learning experiments.
- Tracking model metrics, parameters, and artifacts.
- Managing data and model versions.
- Registering and serving trained models.
- Building prediction APIs using FastAPI.
- Monitoring model performance and detecting data drift.
- Automating tests with GitHub Actions.
- Packaging ML applications using Docker.
- Understanding Kubernetes-based deployment and scaling.

## 📚 Learning Resources

- [MLflow Documentation](https://mlflow.org/docs/latest/)
- [DVC Documentation](https://dvc.org/doc)
- [FastAPI Documentation](https://fastapi.tiangolo.com/)
- [Docker Documentation](https://docs.docker.com/)
- [Kubernetes Documentation](https://kubernetes.io/docs/)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)

## 👩‍💻 About This Repository

This repository is part of my continuous learning journey in Machine Learning Engineering and MLOps. It focuses on understanding both the concepts and practical workflows involved in taking machine learning models from experimentation to deployment and monitoring.

**Note:** This is a learning-focused implementation. The monitoring rules and deployment configurations are educational examples and are not intended to represent a complete production-grade MLOps platform.
