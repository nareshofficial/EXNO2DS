# EXNO2DS
# AIM:
      To perform Exploratory Data Analysis on the given data set.
      
# EXPLANATION:
  The primary aim with exploratory analysis is to examine the data for distribution, outliers and anomalies to direct specific testing of your hypothesis.
  
# ALGORITHM:
STEP 1: Import the required packages to perform Data Cleansing,Removing Outliers and Exploratory Data Analysis.

STEP 2: Replace the null value using any one of the method from mode,median and mean based on the dataset available.

STEP 3: Use boxplot method to analyze the outliers of the given dataset.

STEP 4: Remove the outliers using Inter Quantile Range method.

STEP 5: Use Countplot method to analyze in a graphical method for categorical data.

STEP 6: Use displot method to represent the univariate distribution of data.

STEP 7: Use cross tabulation method to quantitatively analyze the relationship between multiple variables.

STEP 8: Use heatmap method of representation to show relationships between two variables, one plotted on each axis.

## CODING AND OUTPUT
        import pandas as pd
        import numpy as np 
        import import matplotlib.pyplot as plt
        import seaborn as sns
        df=pd.read_csv('/content/titanic_dataset.csv')
        df
        
![311416174-81451b23-08c5-45af-a00f-7e6a0d238a73](https://github.com/user-attachments/assets/75258201-4e05-4e57-bc01-4d5f0e7d1ae6)

        df.info
![311416372-ba3c2652-9331-4ebe-be87-7d90e5248139](https://github.com/user-attachments/assets/5b4368ab-01b8-41cf-9f2d-d8f8e2f79e41)

      df.shape
      
![311416428-197c0a74-6bf8-49a5-8346-b4ec4a4fba20](https://github.com/user-attachments/assets/a54fcbf0-4dba-4cae-b040-7b2a0665f6bb)

       df.head(4)

![311416490-5b03fe5c-b620-4a0e-b02d-ebc0aede1dec](https://github.com/user-attachments/assets/9e52556f-8dd0-49a0-8d14-3e0fdde66645)

        df.describe()

        
![311440906-a070d1bf-2f77-4890-84b4-220fd511850b](https://github.com/user-attachments/assets/9154bab9-0c67-4d2a-8e5c-47e71c64ac9c)

         df.set_index("Passengerid",inplace=True)
         df.describe()

![311441009-1f744a40-6898-494c-ade2-8cb82fd20c3d](https://github.com/user-attachments/assets/216ce04c-a197-4344-9404-d6300e48f1e5)


# RESULT
        Thus, the Exploratory Data Analysis on the given data set was performed successfully.

