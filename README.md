#Report:: ML_with_Python_Assigin

1.	Retrieve data from different sources as shown below and saved in .csv Format.

Data1	https://github.com/toUpperCase78/formula1-datasets/blob/master/formula1_2019season_drivers.csv

Data2	https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020/code?datasetId=468218&sortBy=voteCount

Data3	https://www.kaggle.com/datasets/deepcontractor/froza-horizon-5-cars-dataset

Data4	https://data.world/ogletree/tour-down-under-2018

Data5	https://github.com/toUpperCase78/formula1-datasets/blob/master/formula1_2021season_drivers.csv


2.	Data2 is taken for the Visualization and Data Pre-processing:
a.	Read the data and merged.

![image](https://user-images.githubusercontent.com/88844603/232034268-b6977c50-ea1b-4b5a-b774-1d59ba3de108.png)


 

b.	Checked Missing values: There was no missing values present.


![image](https://user-images.githubusercontent.com/88844603/232034288-8d46f1f8-d0fb-4c99-8d57-e63ec873653a.png)









c.	Taken some of the columns data Visualization:
Correlation Matrix: The correlation matrix displays the relationship between numerical variables in the data. The heatmap shows ‘timetaken_in_millisec' has a strong negative correlation with 'wins' and 'points' (i.e. inverse relation ). 
![image](https://user-images.githubusercontent.com/88844603/232034318-2b1d8c4c-d97f-4ce5-bb7e-cb2f1c936935.png)



d.	Top 10 Car Companies by Wins: The bar chart displays the top 10 companies with the highest total wins. It shows that “Ferrari” has the highest number of wins, followed by  ‘McLaren’ and 'Mercedes'.
 ![image](https://user-images.githubusercontent.com/88844603/232034348-89e53e4c-8f02-4bc9-8874-56bd65028e21.png)

e.	Top 10 Nationalities by Wins: The bar chart displays the top 10 nationalities with the highest number of wins. It shows that drivers from 'British (Britain)' have the highest number of wins, followed by 'Great Britain' and 'Brazil'.
![image](https://user-images.githubusercontent.com/88844603/232034383-28c43b2c-e76f-48a8-9214-0947ae5e0ba2.png)


f.	Wins by Company and Driver Nationality: The stacked bar chart displays the number of wins by company and driver nationality for the top 10 companies. It shows that 'British' has the highest number of wins across various driver nationalities, followed by 'Mercedes' and 'McLaren'.
 ![image](https://user-images.githubusercontent.com/88844603/232034417-96adfe65-de87-45ec-8ad7-5d253e18540f.png)

