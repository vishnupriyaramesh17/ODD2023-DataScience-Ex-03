# ODD2023-DataScience-Ex-03
# Ex-03 Univariate Analysis
## Aim:
To read the given data and perform the univariate analysis with different types of plots.
## Explanation:
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

## Algorithm:
### Step1:
Read the given data.

### Step2:
Get the information about the data.

### Step3:
Remove the null values from the data.

### Step4:
Mention the datatypes from the data.

### Step5:
Count the values from the data.

### Step6:
Do plots like boxplots,countplot,distribution plot,histogram plot

## Program:
```
DEVELOPED BY : Vishnupriya R
REGISTER NO : 212222110054
import pandas as pd
import numpy as np
import seaborn as sns

df=pd.read_csv('superstore.csv')
df

df.head()
df.info()
df.describe()
df.isnull().sum()

df.dtypes

df['Postal Code'].value_counts()

sns.boxplot(x='Postal Code', data=df)
sns.countplot(x='Postal Code',data=df)
sns.distplot(df["Postal Code"])
sns.histplot(x='Postal Code',data=df)
```
## OUTPUT:
### Dataset:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/15423f63-c88f-41e9-b1b1-52f4393ae674)

### Head:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/2e55b123-e077-4f70-a06f-d4e27203bec4)

### Info:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/31e63d3b-b155-484b-82a2-23dba4df63e1)

### Describe:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/83fd3e4b-3d40-4fd0-9286-3aa2bd47424d)

### IsNull:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/b8919bfc-647b-47d8-81d8-0c1a5b2ba6ce)

### dtypes:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/5db86ac1-d1e3-4255-a524-57ae2bd6a41a)

### Valuecount:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/a3a0978b-7073-450a-ab72-3a2daf972738)

### Boxplot:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/c373f026-3791-4ef3-a752-0812433f8d84)

### Countplot:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/a62bcb1f-57c2-4af3-9a82-d5189633e8c3)

### Distribution plot:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/d897af8e-5709-469a-8ceb-667fb8f61aff)

### Histogram plot:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/f4a1e7e8-1117-4cb9-9de3-5632dddb9f4d)

## Result:
Thus we have read the given data and performed the univariate analysis with different types of plots.











