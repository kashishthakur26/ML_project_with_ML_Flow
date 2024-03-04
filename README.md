# ML_project_with_ML_Flow

## Workflows

1. Update config.yaml
2. Update schema.yaml
3. Update params.yaml
4. Update the entity
5. Update teh configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the app.py

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/kashishthakur26/ML_project_with_ML_Flow
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mlproj python=3.8 -y
```

```bash
conda activate mlproj
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

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/kashishthakur26/ML_project_with_ML_Flow.mlflow \
MLFLOW_TRACKING_USERNAME=kashishthakur26 \
MLFLOW_TRACKING_PASSWORD=71c1b8bec134b792297e4e989b1fa3df779dc9bb \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/kashishthakur26/ML_project_with_ML_Flow.mlflow

export MLFLOW_TRACKING_USERNAME=kashishthakur26 

export MLFLOW_TRACKING_PASSWORD=71c1b8bec134b792297e4e989b1fa3df779dc9bb 

```
