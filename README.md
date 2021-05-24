# School_District_Analysis


## Project Overview

### Analyzing school district by using Pandas and Jupyter Notebook

### Goal:

  - Prepare standardized data for analysis, reporting, and presentation to provide insights about performance trends and patterns in order to make important decisions at the school and district level. This analysis will be given to the school analysis board for discussion on the budgets per district per school based on the students' performances and passing grades. 
  

        - Read the row data from both schools and students complete lists CSV files;
        - Clean and Inspect the data;
        - Merge Data Sets;
        - Perform calculations;
        - Create tables
        - Change tata layout structure
        - Organize by data type
        - Format rows and columns
        - Sort or group data as needed 




## Resources 

- Data Source: schools_complete.csv; students_complete.csv

- Software: Python 3.9.4; Pandas Library; Jupyter Notebook




## Summary

- There are 15 schools and 39170 students in total. Total given budget per district summary was **$24,649,428.00**. 

- The average reading score is **81.85** and the average math score is **78.93**.

- Based on the overall passing percentages we noticed that:

    - The medium size school between 1000 to 2000 students has the highest overall passing percentages omn math and reading. 

    - The top five highest-performing schools based on the highest % Overall Passing are charter schools that have a low student population.
    
    ![Top schools](School_District_Analysis/top_five_schools.png)

    - The five lowest-performing schools based on the lowest "% Overall Passing" are district schools that have a high student population. 
    
    ![Lowest schools](lowest_five_schools.png")
        
    - Students from the Charter schools show better results compared to District schools.


- When we received anonimous tip on the 9th graders scores at Thomas High School, we did further analysis on the school's math and reading scores amonghts high school students. My final data showed that the overall passing percentages on math and reading at Thomas High School is actually around _90.63%_ , while the row data that we received showed _97.31%_. This confirms that this school did not report the 9th grader's scores correctly. 
