## Period_Poverty
This repository was created in the Semester A of 2020-2021. It stores the group project of the course AIDM 7330 Basics Programming  for Data Science @ Hong Kong Baptist University. This group project was created by LIN Meishan, FU Yu, HU Xinyu and YU Tian.

## Data

When we searched for datasets, we searched for keywords such as menstruation, period poverty and female health conditions, etc. and found different databases about menstruation. Finally, we chose two databases on The United Nations website under the theme of The World's Women 2020.

The two datasets are [ the proportion of women and adolescent girls (15-49) with a private place to wash and change and using menstrual hygiene materials ]( https://worlds-women-2020-data-undesa.hub.arcgis.com/datasets/proportion-of-women-and-adolescent-girls-15-49-with-a-private-place-to-wash-and-change-and-using-menstrual-hygiene-materials?geometry=-154.511%2C-19.309%2C100.020%2C38.550 )and [ the proportion of women and adolescent girls (15-49) who did not participate in school work or social activities during their last menstrual period ]( https://worlds-women-2020-data-undesa.hub.arcgis.com/datasets/proportion-of-women-and-adolescent-girls-15-49-who-did-not-participate-in-school-work-or-social-activities-during-their-last-menstrual-period ). We chose these two datasets because we think data from The UN is relatively authoritative and scientific. These two datasets came from one survey, other than the proportion data of two different questions, all the other information are the same.

In the two datasets, we have variables like age groups, countries including 19 counties from 5 continents, and they are all developing countries, urbanization conditions like rural or urban and wealth conditions of the females taken the survey. When dealing with the two tables, we are not going to present everything, we choose variables that could produce significant characteristic results, so as the table shows, the focused variables of the 2 tables are different.

When processing the data, I used PD.MERGE to combine the two datasets based on their common columns, they are variables like countries, ages, urbanization conditions, wealth conditions, etc.


## Analysis
The rendered version of the notebook, can be viewed [ here ]( https://nbviewer.jupyter.org/github/mic-lin/Period_Poverty/blob/main/7330_GroupProject_MangoX.ipynb ).
