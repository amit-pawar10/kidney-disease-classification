# Kidney-Disease-Classification


## 📊 Overview
A Kidney Tumor classification system that leverages deep learning models to classify the CT scan image into Healthy or Tumor

##  🏗️  Workflows

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
https://github.com/krishnaik06/Kidney-Disease-Classification-Deep-Learning-Project
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n kidney python=3.8 -y
```

```bash
conda activate cnncls
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




### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag


## About  DVC


DVC 

 - Its very lite weight for POC only
 - lite weight expriements tracker
 - It can perform Orchestration (Creating Pipelines)

