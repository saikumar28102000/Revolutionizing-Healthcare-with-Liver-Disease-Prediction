# Revolutionizing Healthcare with Liver Disease Prediction
This repository consists of files required to deploy a Machine Learning Web App created with Flask and deployed using Heroku platform.


#### If you want to view the deployed model, click on the following link:

• https://liver-disease-pred.herokuapp.com/



## Problem Statement
This data set contains 416 liver patient records and 167 non liver patient records collected from North East of Andhra Pradesh, India. The "Dataset" column is a class label used to divide groups into liver patient (liver disease) or not (no disease). This data set contains 441 male patient records and 142 female patient records.

Use these patient records to determine which patients have liver disease and which ones do not.

## Dataset
[Liver Disease Dataset](https://www.kaggle.com/uciml/indian-liver-patient-records)


## Technology used
- Python
- Machine Learning
- Pandas
- Numpy
- Scikit-learn
- Flask
- HTML
- CSS
- Pycharm
- Heroku

  
## Running Tests

To run app, run the following command

```bash
  python app.run
```

  
## Screenshot

![App Screenshot](https://github.com/saikumar28102000/Python_Project_EAS503/blob/main/Images/ss.png)

  
## Deployment

To deploy this project run following command in the project folder

```bash
  git bash open
```

Create .git file
```bash
  git init
```
Track all the files
```bash
  git add .
```
Cheacking file track or not
```bash
  git status
```
Store as separate version
```bash
  git commit -m 'message'
```
### Deployment on Heroku

Heroku login on git bash

```bash
  heroku login
```
Create new app

```bash
  heroku create
```
Push Code
```bash
  git remote -v
```
Push code to Master Branch
```bash
  git push heroku master
```

  

