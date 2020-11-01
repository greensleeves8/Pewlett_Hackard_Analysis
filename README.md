# Pewlett Hackard Analysis

## Overview

A Human Resources analyst with Pewlett Hackard, a large, long-standing company, approached us
to lead the creation of the company's new Human Resources database, and to assist with the analysis
of the company's upcoming "silver tsunami"; as Baby Boomer's reach retirement age, the company needs
to identify the number of employees retiring in the near future, and determine the number of 
positions that need to be filled within the company. For the creation of the HR database, we were 
tasked with moving data from CSVs created in Excel into a SQL database, in this case using PostgreSQL 
through pgAdmin, and then creating SQL queries to perform our retirement analysis. 


## Results

- Pewlett Hackard has quite the retirement crunch ahead of them, with over 90,000 employees identified
as nearing retirement age. These positions will most likely need to be filled, while management may 
also need to decide whether certain positions can be consolidated, or replaced by automation. 
![Number of Retiring Employees: 90,398](https://github.com/greensleeves8/Pewlett_Hackard_Analysis/blob/main/Resources/Retiring_Employees_Number.png)

- The Engineering ranks at Pewlett Hackard stand to be the most hard hit by the upcoming retirements.
Between Senior Engineers, Engineers, and Assistant Engineers, over 45,000 employees will be retiring 
imminently. 
![Number of Engineering Positions Retiring: 45,000+](https://github.com/greensleeves8/Pewlett_Hackard_Analysis/blob/main/Resources/Retiring_Titles_Dept.png)

- Pewlett Hackard's Management ranks are mostly unaffected, with only two managers up for retirement. 

- The planned mentorship program may be inadequate for the number of positions retiring. Only 1,549 
employees fit the initial criteria for the mentorship program. If the full number of retiring 
employees are replaced, that would leave the average mentor responsible for over 58 incoming employees. 
![Employees Eligible for Mentorship Program: 1549](https://github.com/greensleeves8/Pewlett_Hackard_Analysis/blob/main/Resources/Mentorship_Eligibilty.png)

## Summary

The exact number of jobs that will need to be replaced due to the criteria for retirement we were given
is just over 90,000, 90,398 to be exact. Whether this is the exact amount of hires that will need to
be made is unclear; Pewlett Hackard management will need to determine whether they think that certain 
positions can be consolidated or replaced by new efficiency standards or automation. Even if that is the
case, and the full number of positions needing to be replaced is below the number of positions lost to
retirement, Pewlett Hackard Human Resources and Management have a substantial task ahead of them.

Given the number of positions opening up due to retirement, it seems that with the the current criteria
for meeting the qualifications of the mentorship program, Pewlett lacks enough qualifying mentors. Under
the current criteria for the mentor program, there are just 1,549 potential mentors for the over 90,000
positions to be filled, or 1 mentor for every 58.4 positions to be filled. My suggestion would be to 
expand the age range for the potential mentors. By running a new query for the mentorship program with 
the exact same criteria as before, but with the date of birth criteria expanded to between January 1, 1964
and December 31, 1965, the number of potential candidates for the mentorship program expands to 19,905
employees, which would place the ratio of mentors to potential new employees at around 1 to 5. 

Lastly, given the number of positions that stand to be filled, and the amount of engineering jobs that 
need to be filled, it's important to make sure that the number of potential mentorship positions reflect the 
number of engineering positions that need to be filled, and thus the number of engineering mentors needed. 
The revised group of mentors reflects a proportional amount of potential engineering mentors:

![Revised Mentor Group](https://github.com/greensleeves8/Pewlett_Hackard_Analysis/blob/main/Resources/Revised_Mentor_group.png) 

The revised criteria for the mentorship that I suggested would provide an adequate amount of potential
engineering mentors, with nearly 10,000 Senior Engineers, Engineers, and Assistant Engineers among the 
mentorship group. 


