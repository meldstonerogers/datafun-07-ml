# datafun-07-ml
Module 7 Project
Melissa Stone Rogers, June 9, 2024

## Introduction
Professional project UPDATE ONCE I DETERMINE PROJECT
Commands were used on a Mac machine running zsh.  

## How to Install and Run the Project
Create project repository in Github and clone to your machine.

```
git clone project.url
```
```
git pull
```

```
python3 -m venv .venv
source .venv/bin/activate
```

Create requirements.txt in the root project folder. 
```
touch requirements.txt
```

Install and freeze required packages 
```
pip install jupyterlab pandas pyarrow matplotlib seaborn
python3 -m pip freeze > requirements.txt

```

## Add .gitignore File
Add .gitignore file to the root project folder. 
```
touch .gitignore
```
Add the following to your .gitignore file: 
- .venv/
- .vscode/
- .ipynb_checkpoints/

## Initial Project Save
```
git add .
git commit -m "initial"                         
git push origin main
```
## Project Data Set
For this project, a data set from Seaborn will be used. The data file is flights.csv and contains data of the number of passengers in given months and years. 
[Flights Data Set](https://github.com/mwaskom/seaborn-data/blob/master/flights.csv)


## Exploratory Data Analysis within Jupyter
Create a new juypyter file. 
```
touch filename.ipynb
```

## Import Dependencies 

```
import matplotlib.pyplot as plt
import pandas as pd
import seaborn as sns
import pyarrow as pa
```
## Follow Steps to Complete EDA






## Complete Your Project
Save your project and push back to your repository. 
```
git add .
git commit -m "final"                         
git push origin main
```

## Project Summary
UPDATE 