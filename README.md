# datafun-07-ml
Final Project
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
pip install jupyterlab pandas pyarrow matplotlib seaborn scipy numpy scikit-learn
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


## Final Project within Jupyter
Create a new juypyter file. 
```
touch yourname_ml.ipynb
```

## Import Dependencies 
```
import matplotlib.pyplot as plt
import pandas as pd
import seaborn as sns
import pyarrow as pa
import numpy as np
import scipy
import sklearn
```
## Follow Steps to Complete Project

## Part 1 - Chart a Straight Line
Follow instructions from text [Intro to Python for Computer Science and Data Science](https://deitel.com/intro-to-python-for-computer-science-and-data-science/) on page 414, Chapter 10.16. Utilize markdown cells to create section headings as you work.  
 
## Part 2 - Prediction
Follow instructions from text [Intro to Python for Computer Science and Data Science](https://deitel.com/intro-to-python-for-computer-science-and-data-science/) on page 416, Chapter 10.16. Utilize markdown cells to create section headings as you work. You will create seven section while working through the data: 
- Section 1 - Data Acquisition
- Section 2 - Data Inspection
- Section 3 - Data Cleaning
- Section 4 - Descriptive Statistics
- Section 5 - Build the Model
- Section 6 - Predict
- Section 7 - Visualizations
It may be helpful to outline these headings in markdown cells, with code cells in between. 

## Part 3 - Prediction
Follow instructions from text [Intro to Python for Computer Science and Data Science](https://deitel.com/intro-to-python-for-computer-science-and-data-science/) on page 620, Chapter 15.4. Utilize markdown cells to create section headings as you work. From Part 2, you have already aquired, inspected, cleaned, and ran descriptive statistics on the data. You will do the following with the data in Part 3: 
- Section 1 - Build the Model
- Section 2 - Test the Model
- Section 3 - Predict 
- Section 3 - Visualizations
It may be helpful to outline these headings in markdown cells, with code cells in between. 

## Part 4 - Insights
Part 4 is a discussion of the two different methods use in this project to visualize data and find the linear regression line. 



## Complete Your Project
Save your project and push back to your repository. 
```
git add .
git commit -m "final"                         
git push origin main
```

## Project Summary
UPDATE 