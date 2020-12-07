# Pewlett Hackard Analysis
## Overview of the Analysis
To determine the number of retiring employees per title and identify employees who are eligible to participate in a mentorship program in order to help the company deal with the "silver tsunami" as many current employees are reaching retirement age.

## Results
The first snapshot objective is to uderstand how many employes will be able to retire in the next couple of years. In order to give a high level picture, a table was created to show how many titles per position will be retiring soon. See below:

<img width="275" alt="RetiringTitles" src="https://user-images.githubusercontent.com/72593264/101303885-b5706a00-3804-11eb-8d1e-0f263a11d07d.png">

Also, another table was created in order to demonstrate how many and what are the current employees that would be eligible for a part time mentorship program, that would facilitate the transition between employees. Below is the first 10 rows of that table.

<img width="870" alt="Mentorship_Eligibility" src="https://user-images.githubusercontent.com/72593264/101308157-d1790900-380e-11eb-86da-adfdd6dd747d.png">

Results can be expressed like this:
- 90938 employees will be eligble to retire in the next couple of years in various roles.
- Vast majority of these employees - 63.8% - are from senior positions (senior staff/senior engineer)
- 1549 employees are eligble to be in the mentorship program
- 70.9% of these employees are in Senior positions.

## Summary
Two questions are being addressed here:
- How many roles will need to be filled as the "Silver Tsunami" begins to make an impact?

The answer is simple - too many. A total of 90938 employees will be eligble to retire in the next couple of years. This number can be achieved with a sum of all the titles in the retirin title table:

<img width="122" alt="Retiring_sum" src="https://user-images.githubusercontent.com/72593264/101310182-cffe0f80-3813-11eb-885c-f85bb3aecbbe.png">

- Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

The answer is no.

A total of 1549 employes will be  eligible for the mentorship program. Sorting and counting the mentorship eligibility table we get the results below:

<img width="278" alt="Mentorship_title_summary" src="https://user-images.githubusercontent.com/72593264/101310292-1fdcd680-3814-11eb-8cf4-ae4a01aba805.png">

The most deficiency after the silver tsunami will be on Senior Staff and Senior Engineers.
It is important to notice that there is a significant number of Senior Staff/Engineers that will be eligible for mentoship (around 1000), although this number is far from perfect given the size of the company.

In order to train enginieers and staff to keep the same number of senior employees after the silver tsunami, each senior mentor would have to train least 30 people, which is not feasible in a mentorship program.
