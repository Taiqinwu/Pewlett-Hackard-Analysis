# Pewlett-Hackard-Analysis

## Overview
* Now that Bobby has proven his SQL chops, his manager has given both of you two more assignments: determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. Then, you’ll write a report that summarizes your analysis and helps prepare Bobby’s manager for the “silver tsunami” as many current employees reach retirement age.

## Results

### Deliverable 1

* Table 1: We need to create a retirement title table. This table will retrieve employee numbers, first name, last name, from the employee table, and title, from data, and to date from title table. We will also filter the data to employees that were born between 1952 and 1955. 
<img width="466" alt="image" src="https://user-images.githubusercontent.com/107168891/183337430-a5fa4abe-e8eb-47b2-9fe2-ac2f5588a2a4.png">

* From our first table that we create, it's incorrect because there are duplicate entries for some employees due to they have switched titles over the years. In this table it will remove these duplicates and keep only the most recent title of each employee. We will also filter out the employees that have left the company, and ascending order by the employee number and descending order by the last date. 
<img width="375" alt="image" src="https://user-images.githubusercontent.com/107168891/183337816-d6e5324d-87a0-4a4a-95af-013aa5f87899.png">

* The last table will retrieve the number of employees by their most recent job title who are about to retire. We will sort the count column in descending order.
<img width="222" alt="image" src="https://user-images.githubusercontent.com/107168891/183337969-d9696f06-662b-4822-a280-b4aac8972952.png">

### Deliverable 2
* In the second part, we will create a mentorship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965.mentorship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965. To do that we will retrieve employee numbers, first name, last name, birth day from the employee table, and from data, and to date from Department Employee table, and title from the title table. Lastly, we will order the table by the employee number.
<img width="516" alt="image" src="https://user-images.githubusercontent.com/107168891/183338538-e6152771-9e05-4721-a07b-5cb2e8f9069d.png">

## Summary
How many roles will need to be filled as the "silver tsunami" begins to make an impact?
* According to the count table above, we notice that there are 72,458 employee ready for retiring, and many of them are in the senior level. The company should start looking for new employees to replace the retirment employees. 

Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
* Based on the mentorship-eligibility table, we see that there are 1550 employees who are eligible for mentorship. Base on the number of people who are eligible for retiring, this will number will be insufficent. The company needs to look for more employees 
