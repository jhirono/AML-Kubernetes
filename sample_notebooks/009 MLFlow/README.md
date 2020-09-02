# Azure ML Examples

[![run-notebooks-badge](https://github.com/Azure/azureml-examples/workflows/run-notebooks/badge.svg)](https://github.com/Azure/azureml-examples/actions?query=workflow%3Arun-notebooks)

Welcome to the Azure ML examples! This repository showcases the Azure Machine Learning (ML) service.

## Getting started

Clone this repository and install a few required packages:

```sh
git clone https://github.com/Azure/azureml-examples
cd azureml-examples
pip install -r requirements.txt
```

### install cmaks sdk

```sh
pip install --disable-pip-version-check --extra-index-url https://azuremlsdktestpypi.azureedge.net/CmAks-Compute-Test/D58E86006C65 azureml-pipeline-steps azureml-contrib-pipeline-steps azureml-contrib-k8s --upgrade
```

## Notebooks

Example notebooks are located in the [notebooks folder](notebooks).

path|scenario|compute|framework(s)|dataset|environment type|distribution|other
-|-|-|-|-|-|-|-
[notebooks\fastai\train-mnist-resnet18.ipynb](notebooks\fastai\train-mnist-resnet18.ipynb)|training|AML - CPU|fastai, mlflow|mnist|conda file|None|None
[notebooks\fastai\train-pets-resnet34.ipynb](notebooks\fastai\train-pets-resnet34.ipynb)|training|AML - GPU|fastai, mlflow|pets|docker file|None|broken :(
[notebooks\lightgbm\train-iris.ipynb](notebooks\lightgbm\train-iris.ipynb)|training|AML - CPU|lightgbm, mlflow|iris|pip file|None|None
[notebooks\pytorch\train-mnist-cnn.ipynb](notebooks\pytorch\train-mnist-cnn.ipynb)|training|AML - GPU|pytorch|mnist|curated|None|None
[notebooks\sklearn\train-diabetes-ridge.ipynb](notebooks\sklearn\train-diabetes-ridge.ipynb)|training|AML - CPU|sklearn, mlflow|diabetes|conda file|None|None
[notebooks\tensorflow-v2\train-iris-nn.ipynb](notebooks\tensorflow-v2\train-iris-nn.ipynb)|training|AML - CPU|tensorflow2, mlflow|iris|conda file|None|None
[notebooks\tensorflow-v2\train-mnist-nn.ipynb](notebooks\tensorflow-v2\train-mnist-nn.ipynb)|training|AML - GPU|tensorflow2, mlflow|mnist|curated|None|None
[notebooks\xgboost\train-iris.ipynb](notebooks\xgboost\train-iris.ipynb)|training|AML - CPU|xgboost, mlflow|iris|pip file|None|None

## Contributing

We welcome contributions and suggestions! Please see the [Contributing Guidelines](CONTRIBUTING.md) for details.