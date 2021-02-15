# moringaIp
Data analysis with pandas
This project Focuses on analysing data with CRISP-DM Methodology.
Resourcess used to achieve the goal of the project are: 
 
 a).CRISP-DM has the following steps:
 
    1.Business understanding.
    2.Data understanding.
    3.Data Preparation.
    4.Modelling.
    5.Evaluation.
    6.Deployment.
    
 b). Python as the main programming language:
  
   Python Packages that are arequirement for this project are:
   
    i). Pandas - Pandas is for Analysisng and extracting insight from raw data.
         To install Pandas to become available in the project:
         Conda pip install pandas
         To use it in the project.
         import pandas as pd
         
         Pandas is an essential library in analysis data and extracting insight from it,it is easy to use,fast 
         and open source.
    ii). Numpy - is a core library for scientific computing and is made using python. it provides high performance in
         multi-dimensional array objects.
         To use it in a project it have to be installed through this command;
         pip install numpy
         then,
         to use this library in a project it have to be imported into the notebook like this;
         import numpy as np


The goal of this project is to get an insightful strategy to upgrade their infrastructure to serve their mobile user more effectively.
For effective service the dataset have to give insight of how frequent their service are used in cities for the period the data is collected,which cities had the most users during the business and home hours.

To get the insight from dataset, the data have to be loaded to analyse it:
    To load the dataset we create a variable to represent the dataset:
    
      df_cell = pd.read_csv('cell_geo.csv',delimiter =';')
      
      df_cellDescr = pd.read_excel('cells_geo_description.xlsx')
      
   This loads the cell goegraphical dataset and cell geographical description dataset respectively.
   
   Then load the telecom datasets:
    
      df_telc_1 = pd.read_csv('Telcom_dataset.csv')
      
      df_telc_2 = pd.read_csv('Telcom_dataset2.csv')
      
      df_telc_3 = pd.read_csv('Telcom_dataset3.csv')
      
    
      
