
# Kidney-Disease-Classification-DLproj

## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the dvc.yaml
10. app.py


# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/uthsavi97/Kidney-Disease-Classification-DLproj
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n kidney python=3.11.5  -y
```

```bash
conda activate kidney
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```

# MLflow
Documentation

### MLflow 

cmd
mlflow ui
dagshub
dagshub

MLFLOW_TRACKING_URI=https://dagshub.com/uthsavi97/Kidney-Disease-Classification-DLproj.mlflow \
MLFLOW_TRACKING_USERNAME=uthsavi97 \
MLFLOW_TRACKING_PASSWORD=9443d56bb7aa50de09f2e485d7d13bb17bc200d6 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/uthsavi97/Kidney-Disease-Classification-DLproj.mlflow

export MLFLOW_TRACKING_USERNAME=uthsavi97 

export MLFLOW_TRACKING_PASSWORD=9443d56bb7aa50de09f2e485d7d13bb17bc200d6

```
DVC cmd
dvc init
dvc repro
dvc dag
About MLflow & DVC
MLflow

Its Production Grade
Trace all of your expriements
Logging & taging your model
DVC

Its very lite weight for POC only
lite weight expriements tracker
It can perform Orchestration (Creating Pipelines)