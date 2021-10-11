# Pewlett Hackard Analysis
## Project Overview
Pewlett Hackard is a very large company employing just over 300,000 employees.  I have been tasked with identifying the total number of employees that are eligible for retirement, as well as the number of employees eligible to participate in a company mentorship program.  Employees born between January 1, 1952 and December 31, 1955 are deemed eligible for retirement. Employees born in the year 1965, have been idenified as those eligible to participate in the mentorship program.  The below information breaks down how many total employees are expected to retire and their current titles.  Examples of queries created are also provided for reference.

## Results
### Total Employees Retiring by Title
![Retiring_Titles_Query](https://user-images.githubusercontent.com/89044350/136845315-b650dc7b-1e2b-4ee0-805c-08f8ac132837.PNG)
- The above query creates a new table called "retiring_titles", and provides a total count of employees eligible to retire organized by title. As shown below:

![Retiring_Titles](https://user-images.githubusercontent.com/89044350/136845413-f20fd9da-0587-4be5-bb62-28a8eba3898f.PNG)

### Total Employees Eligible For Mentorship Program
![Mentorship_Eligibility_Query](https://user-images.githubusercontent.com/89044350/136846312-e92d721d-b4fb-4211-971c-66ec199994b7.PNG)
- The above query creates a new table called "mentorship_eligibility", which provides a total count of employees eligible to participate in the mentorship program.  There are over 1500 employees eligible to participate, below is a screenshot of the first 10 employees to provide a visual of the table created:

![Mentorship_Eligibility](https://user-images.githubusercontent.com/89044350/136846527-3366643c-e520-4321-bbdd-1f0b1eae314d.PNG)

## Summary of Analysis
Pewlett Hackard is preparing for over 90,000 employees (90,398 to be exact) to retire.  Only 1,549 employees qualify for the mentorship program, this is not nearly enough to fill in the void that will be created with the number of individuals eligible to retire. As shown above, 64% of the individuals eligible to retire fall under Senior Level staff or Engineering. The Engineering Department as a whole is going to be hit the hardest with 45,397 employees being eligible to retire, making up 50% of the total. This is a lot of knowledge and experience leaving the company.

It would be my recommendation to expand the eligibily for the mentorship program to include a wider birth year range, one year is not providing enough employees to fill the void. Pewlett Hackard could also entertain the idea of temporary monetary incentives to high level individuals eligible for retirement to remain with the company in order to train employees. This would buy the company time to hire new talent, train existing talent to fill their superiors positions once they are vacated and lower the amount of employees retiring at the same time. A positive for Pewlett Hackard is that new hires could have the potential to learn quickly as technology has grown so much providing the younger generations entering the work force more exposure and experience, making them that much more tech savy.
