# Pewlett-Hackard-Analysis
## **Overview of Project**

The purpose of this analysis is to conduct a Database analysis for Pewlett Hackard with detailed information on the number of future retirees from all departments currently working at the company to be able to prepare a plan to hire new staff and also to prepare a mentorship initiative. 

The criterion was based on the birth dates ranging from 1952 to 1955 and hired dates from 1985 to 1988.


## Results

- Below is the ERD (Entity Relationship Diagram) used to visualize the relationship between the data sources and the structure of the company's employee plan to facilitate the analysis.
![alt text](https://github.com/akhue02/Pewlett-Hackard-Analysis/blob/main/ERD.png )

- After creating the unique_titles table by joining the employees and titles tables, filtering them by date of birth and date hired, removing duplicates, and ordering the data points by date hired there are **90,398 employees retiring** as per the above criterion. 

To download: [unique_titles.csv](https://github.com/akhue02/Pewlett-Hackard-Analysis/files/Data/delivery 1/unique_titles.csv)


- Out of those employees leaving, there are 29,414 Senior Engineers, 28,254 Senior Staff, 14,222 Engineers, 12,243 Staff, 4,502 Technique Leaders, 1,761 Assistant Engineers, and 2 Managers. 


To download: [retiring_titles.csv](https://github.com/akhue02/Pewlett-Hackard-Analysis/files/Data/delivery 1/retiring_titles.csv)

- Created the mentorship_eligibility table by joining the employees, department employees, and titles tables. In this case, the criterion for the join was that the employees were born in 1965 and that they were currently working at PH, in order for them to apply to the retiring/mentorship package. There were 1,549 employees eligible 

To download: [mentorship_eligibility.csv](https://github.com/akhue02/Pewlett-Hackard-Analysis/files/Data/delivery 1/mentorship_table.csv)

- Out of those eligible employees, there are 402 Engineers, 392 Senior Staff, 332 Staff, 290 Senior Engineers, 77 Technique Leaders, and 56 Assistant Engineers. 



## Summary
Ideally, as the silver tsunami approaches the idea would be to prepare and be on the look for 13,505 employees. This number represents the number of people that are currently working at the company, have been there since 1985 to 1988, and their birth date is between 1962 and 1965 to be eligible to leave work. The plan is to offer these people the mentorship program so that they can keep mentoring new employees. However, if they decide to go PH should be ready to hire that amount of people. 
