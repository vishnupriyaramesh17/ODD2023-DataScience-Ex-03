# ODD2023-DataScience-Ex-03
# Ex-03 Univariate Analysis
# Aim:
To read the given data and perform the univariate analysis with different types of plots.
# Explanation:
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

# Algorithm:
## Step1:
Read the given data.

## Step2:
Get the information about the data.

## Step3:
Remove the null values from the data.

## Step4:
Mention the datatypes from the data.

## Step5:
Count the values from the data.

## Step6:
Do plots like boxplots,countplot,distribution plot,histogram plot

# Program:

DEVELOPED BY : Vishnupriya R
REGISTER NO : 212222110054

## diabetes.csv
```
import pandas as pd
df=pd.read_csv("/content/diabetes.csv")
df
df.info()
df.dtypes
df['DiabetesPedigreeFunction'].value_counts()
df.describe()
import seaborn as sns
sns.boxplot(x='SkinThickness',data=df)
sns.countplot(x="SkinThickness",data=df)
sns.distplot(df['SkinThickness'])
sns.histplot(x="SkinThickness",data=df)
df.skew()
sns.histplot(x='Insulin',data=df)
sns.distplot(df['BloodPressure'])
df.kurtosis()
sns.boxplot(x='Insulin',data=df)
sns.boxplot(x='SkinThickness',data=df)
```
## employeesal.csv
```
import pandas as pd
df=pd.read_csv("/content/employeesal.csv")
df
df.info()
df.dtypes
df['Salary'].value_counts()
df.describe()
import seaborn as sns
sns.boxplot(x='Experience_Years',data=df)
sns.countplot(x="Experience_Years",data=df)
sns.distplot(df['Experience_Years'])
sns.histplot(x="Experience_Years",data=df)
df.skew()
sns.histplot(x='Salary',data=df)
sns.distplot(df['ID'])
df.kurtosis()
sns.boxplot(x='Salary',data=df)
sns.boxplot(x='Experience_Years',data=df)
```
## SuperStore.csv
```
import pandas as pd
df=pd.read_csv("/content/SuperStore.csv")
df
df.info()
df.dtypes
df['Sales'].value_counts()
df.describe()
import seaborn as sns
sns.boxplot(x='Postal Code',data=df)
sns.countplot(x="Postal Code",data=df)
sns.distplot(df['Postal Code'])
sns.histplot(x="Postal Codes",data=df)
df.skew()
sns.histplot(x='Sales',data=df)
sns.distplot(df['Postal Code'])
df.kurtosis()
sns.boxplot(x='Sales',data=df)
sns.boxplot(x='Row ID',data=df)
```

# Output:

## For diabetes.csv file

## Dataframe:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/268273e4-7df3-4885-843c-5d2df65d7311)

## Data information:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/14798c5e-cb1f-4ffd-b4af-e35127c2832a)

## Datatype:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/c5bd0216-f540-4ca1-9860-9272cc6b6a03)

## Valuecount:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/449bb012-2eb5-4b4b-a95f-f91f0d095478)

## Describing a data:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/4eaa9988-5b63-4fa3-8966-fec7e96154ac)

## Boxplot:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/d5fddeac-0993-4a9b-951b-fa67aa93dfbc)

## Countplot:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/58f5a8de-51ad-4b7e-8870-1ee404472d0f)

## Distribution plot:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/c2bbb2cd-dbb7-41ed-8cdb-6f44160df2b1)

## Histogram plot:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/59672395-2fa3-4e68-8c7e-e8b9f16052e1)

## Skewness:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/12613c07-461e-4ceb-9824-98ac0ec8f5fb)
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/5d54ceb5-1b5e-4064-9641-caa266524a0c)
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/33e03671-fd54-4260-b606-4e73bd147d11)

## Kurtosis:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/df11cd71-52b1-4559-b915-4f93e3b2fcbb)
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/dc538cc4-7d94-47c1-87ef-2ec5aadfe9c1)


## For employeesal.csv file:

## Dataframe:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/4a6aa0a8-7d68-47e0-8c71-ab9385c93c63)

## Data information:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/8ef5de03-883c-4272-bf9c-d9d63792927a)

## Datatypes:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/ea64676e-4b63-4840-987f-8c65e2f88e7c)

## Valuecount:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/890345d2-4094-410f-bf4e-50e582fc9c63)

## Describing a data:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/d1c1573d-b0bb-4d5a-ae0a-4affde653fbd)

## Boxplot:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/cd8c0a28-0b14-42f4-9549-f865266cae70)

## Countplot:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/f178de62-a7f8-4f7b-b521-ba9e49648c0f)

## Distribution plot:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/44bcda7c-ab09-4ece-a1b7-e5947790bc7d)

## Histogram plot:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/d7b0dc60-12e7-40f0-8cdc-64348748bf89)

## Skewness:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/2ca2381a-8437-46bb-a7b2-8f92fcad3057)
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/2254077b-901f-48d0-b0c5-352ca521eaa0)
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/8130e480-21d3-474e-b088-d846d0f91b2b)

## Kurtosis:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/32e83426-dc6b-4e20-9edd-dcccc6aa14e7)
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/efe1d007-b068-41ca-957a-84dc9eb5ddea)
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/40a3e1e7-96ab-4456-85a3-abc14f67019f)

## For SuperStore.csv file:

## Dataframe:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/e79f918e-23f1-4cea-bae3-8d603f3fb315)

## Data information:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/908357f8-757c-40fd-a33d-acd7407dfe09)

## Datatypes:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/880181ae-4d2e-4afc-8fa9-e1d2af83d1d7)

## Valuecounts:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/cd8d0c09-8a26-408b-888a-0e9fc64c1f2b)

## Describing a data:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/ca200004-b3f9-4431-b593-a7582ad21ee1)

## Boxplot:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/9800885e-804b-45b4-ae76-c5bbf14fccd5)

## Countplot:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/ec04fc5c-a579-4121-9d3c-690e9df4c210)

## Distribution plot:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/15a67de8-2880-4ded-b6a6-9659270858fc)

## Histogram plot:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/79e3881a-577e-4e88-b934-f770abbd3974)

## Skewness:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/307f9fe2-8960-48de-913e-c8b8a37e5cd3)
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/f13bddb5-9a23-457d-b019-63862d4de7a2)
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/f74193bd-afe4-4b0a-bae3-1502a5f1e515)

## Kurtosis:
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/92582484-b03f-4a7e-a598-c4c58a7a13b8)
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/fb342ab0-6ac8-42c8-9438-2b31519dfb0a)
![image](https://github.com/vishnupriyaramesh17/ODD2023-DataScience-Ex-03/assets/119393589/8fc88546-ab7c-4bca-8c3a-b1e4e738ceed)

# RESULT:
Thus we have read the given data and performed the univariate analysis with different types of plots.

