# PEWLETT_HACKARD ANALYSIS

## Overview of the Analysis
The purpose of this analysis is to prepare Pewlett-Hackard, a company with several thousand employees, for the upcoming “silver tsunami”. A large number of employees will begin retiring wihtin the next few years and the company wants to be prepared with the retirement packages, open positions and employees’ training. 

The analysis is based on the following findings:

1. Identify the retiring employees by their title.
2. Determine the sum of retiring employees grouped by title.
3. Identify the employees eligible for participation in the mentorship program.

Moreover, I have also looked at some additional details such as roles to be filled in different departments and which employees are qualified and close to retirmenet to be involved in the training program. 

## Results

### The list of retiring employees
  1. The table includes employee number, first name, last name, title, from-date and to-date.
  2. The table displays a list of employees who is going to retire in the next few years.
  3. The list is long and extensive, yet at-a-glance analysis gives us some insights about the query. Some employees appear more than once due to change of title during their career at Pewlett-Hackard.

<img width="698" alt="retirement_titles" src="https://user-images.githubusercontent.com/100812308/165014335-327bac97-69bc-4b6b-a9a1-cf7e496e37f4.png">

### The list of retiring employees without duplicates

  1. The table includes employee number, first name, last name, title, from-date and to-date.
  2. The table displays a list of employees who are going to retire in the next few years.
  3. In the table each employee is listed only once, by her or his most recent title.

<img width="555" alt="unique_titles" src="https://user-images.githubusercontent.com/100812308/165014457-a743e456-c66d-4ebf-ba95-1f269763497c.png">

### The number of retiring employees grouped by title

  1. The table includes employees’ titles and their sum.
  2. The query returns a cohesive table with 7 rows.
  3. From this table we can quickly see how many employees with certain title will retire in the next few years.

<img width="246" alt="retiring_titles" src="https://user-images.githubusercontent.com/100812308/165014532-31799064-1f55-4ff3-b2f1-9fbd53dd7e71.png">

### The employees eligible for the mentorship program

  1. The table contains employee number, first name, last name, birth date, from date, to date and title.
  2. The table displays a list of employees who is eligible for the mentorship program.

<img width="798" alt="mentorship_eligibility" src="https://user-images.githubusercontent.com/100812308/165014593-951a1195-6240-43bd-b4ae-033216b6fabf.png">

## Summary
Reports above give a good insight about the number of the employees that are about to retire and hold specific title. However, I believe that additional break down per department will be beneficial for the company. In this case headquarters can see what to expect in each department separately. Below is the table showing ready-to-retire employees with their department names. 

<img width="697" alt="unique_titles_department" src="https://user-images.githubusercontent.com/100812308/165014872-89d62aa6-f404-4cac-873e-68e91734981b.png">

The table 'retirement titles' contains all the information about the employees that are about to retire in the next four years. Since every department will be affected in some way, a query was run to get more precise numbers what each department can expect and how many roles will need to be filled. Below is the table displaying this information:

<img width="375" alt="roles_to_fill" src="https://user-images.githubusercontent.com/100812308/165015045-64757654-60cc-4038-9e5d-68f5d92154f4.png">


To ensure that are enough qualified staff for training at Pewlett-Hackard I ran a query with additional filter, that returns only employees on higher positions, assuming that those are qualified as mentors. From the table we can see how many qualified employees are in each department to train next generation.

<img width="413" alt="qualified_staff" src="https://user-images.githubusercontent.com/100812308/165015107-a7bac79d-7ba6-44e9-a945-01bd72084485.png">







