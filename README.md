# Chicken-Disease-Classification

## Workflows
1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline
7. Update the main.py
8. Update the dvc.yaml

# How to run?

## steps: 

Clone the repository

```
https://github.com/nikhil-j0/Chicken-Disease-Classification.git
```

## STEP 01 - Create a conda environment after opening the repository

```
conda create -n cnncls python=3.8 -y
```

```
conda activate cnncls
```

## STEP 02 - install the requirements

```
pip install -r requirements.txt
```


```
# Finally run the following command
python app.py
```

Now, 

`Open up your local host and port`

## DVC cmd

```
1. dvc init
2. dvc repro
3. dvc dag
```
