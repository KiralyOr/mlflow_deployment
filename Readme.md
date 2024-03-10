# MLflow on Kubernetes Deployment

This repository contains the necessary Kubernetes deployment YAML files to deploy MLflow, an open-source platform for managing the end-to-end machine learning lifecycle. This deployment aims to simplify the process of setting up MLflow in a Kubernetes environment, making it easy to track experiments, share projects, and deploy models.

## Prerequisites

Before you start, make sure you have the following prerequisites met:
- Kubernetes cluster up and running
- kubectl installed and configured to communicate with your cluster
- Helm installed (if using Helm charts for deployment)

## Quickstart

To quickly deploy MLflow on your Kubernetes cluster, follow these steps:

1. Clone this repository to your local machine:

```bash
git https://github.com/KiralyOr/mlflow_deployment.git
cd mlflow-kubernetes
