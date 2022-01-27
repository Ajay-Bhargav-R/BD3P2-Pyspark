# BD3P2-Pyspark ETL Project
Group 10 - Titanic Dataset
Members: 
*Ronald Wallace G – 20BDA10  
*Clevan Cleon Lobo – 20BDA28  
*Jerome Francis – 20BDA43  
*Ajay Bhargav R – 20BDA64  


i.Extract: Load the data
- Read data as pandas dataframe
- then create spark dataframe
- create a table view "titanic" as spark SQL
ii.Transform: Exploratory data analysis using spark df
- Unique passengerId count
- GroupBy sex and count of survived
- GroupBy Pclass and sum of Fare
- Update column age values as 1,2,3 ->child<10,teen>10 to <25,adult>25
- GroupBy age,Embarked,Pclass and count of survived
iii.Load: Save analysis report
- save as tables - partitioned by sex
