Bike Sales Dataset
![image](https://github.com/Stran251/excel_project/assets/99199099/0dcdd12c-a48a-4687-9504-a09259edcdeb)


My initial task with this dataset is to uncover and delete any hidden duplicates, setting the stage for a cleaner and more insightful analysis.
![image](https://github.com/Stran251/excel_project/assets/99199099/defa7270-d47c-43e0-b9ab-f81ddbaa86ab)
After using the "Remove Duplicate" function within the data tools suite, I successfully identified and eliminated 26 rows of redundant data.


I observed that both the marital status and gender columns used overlapping letters to define customer status. This potential overlap may result in confusion at a later stage.
![image](https://github.com/Stran251/excel_project/assets/99199099/fff91604-39db-4913-8718-982491388329)
To address this issue, I employed the "find and replace" function to substitute individual letters with their corresponding complete words, thereby enhancing ease of use.


I noticed that the distribution of ages within the dataset exhibited considerable variability, posing a possible challenge for analaysis later on. A viable to enhance the data's usability is to categorize the ages into distinct brackets. 
![image](https://github.com/Stran251/excel_project/assets/99199099/36748c8b-7d36-41ca-a6a6-78c594d88117)
To achieve this, I used a nested IF statement, classifying individuals under the age of 31 as belonging to the "adolescent" category, those aged 31 and above as "middle-aged," and individuals surpassing the age of 55 as "seniors."
