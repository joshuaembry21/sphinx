# Onboarding

## Connect on Slack 

## Get access to github repo

- add nxnw folder to directory 

- through the terminal cd into the nxnw folder 

-`git clone https://github.com/North-by-Northwest/Initial_Production_Prediction_Model.git`


## Set up PyCharm Professional

- open PyCharm Professional

- File -> Open -> Initial_Production_Prediction_Model 

### Add Interpreter & change markdown 

- in the interpreter settings add new conda interpreter Python version 3.8 

- in new environment location change 'Initial_Production_Prediction_Model' to 'ippf' 

- change markdown to 4 spaces per tab

## Install dependencies 
```
conda install pandas numpy tqdm matplotlib pyarrow scikit-learn jupyterlab jupyter nodejs openpyxl xlrd dask 
pip install --upgrade xgboost geopy
```

## Download Data

- download [Insync](https://www.insynchq.com/) 

- create data folder in directory 

- in Insync go to "Shared with me" folder and 2 way sync NxNW into your local data folder 
