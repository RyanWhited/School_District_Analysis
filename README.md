# School District Analysis
## Project Overview
I was tasked to help to prepare all standaradized test data for analysis, reporting, and presentation to provide insights on performance trends and patterns for 15 different high schools within a school disctrict. Once the initial analysis was complete it was reported that there was evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders that were altered. I had to go in and change all grades for those particular students to a null value and refactor the overall analysis.

## Results
- How is the district summary affected?
  - As you can see in the below pictures, the average math score, % passing math, % passing reading, and % overall passing dropped by a small margin after adjusting the Thomas High School 9th graders grades to NaN.
  
  Original District Summary
  
  ![Original District Summary](https://github.com/RyanWhited/School_District_Analysis/blob/main/Resources/Original%20District%20Summary.jpg)
  
  New District Summary
  
  ![New Disctrict Summary](https://github.com/RyanWhited/School_District_Analysis/blob/main/Resources/New%20District%20Summary.jpg)

- How is the school summary affected?
  - I notice a drastic postive change in % passing math, reading, and overall passing as seen below
  
  Original School Summary
  
  ![Original School Summary](https://github.com/RyanWhited/School_District_Analysis/blob/main/Resources/Orginal%20School%20Summary.jpg)
  
  New School Summary
  
  ![New School Summary](https://github.com/RyanWhited/School_District_Analysis/blob/main/Resources/New%20School%20Summary.jpg)

- As a result of this dramatic increase of % overall passing puts Thomas High School into the top 5 performing schools in the district
  ![Top 5 Schools](https://github.com/RyanWhited/School_District_Analysis/blob/main/Resources/Top%205%20Schools.jpg)
  
- How does replacing the ninth-grade scores affect the following:

  - Math and reading scores by grade
    - No significant affect other than we find the NaN value for Thomas High 9th graders
    
  - Scores by school spending
    - I discovered increases in values in both the $585-639 and $630-644 ranges
    
      Original Spending Per Student
      ![Original Spending Per Student](https://github.com/RyanWhited/School_District_Analysis/blob/main/Resources/Original%20Spending%20Per%20Student.jpg)
      
      New Spending Per Student
      ![Original Spending Per Student](https://github.com/RyanWhited/School_District_Analysis/blob/main/Resources/New%20Spending%20Per%20Student.jpg)   
    
  - Scores by school size
    - No affect to this DataFrame
    
  - Scores by school type
    - No affect to this DataFrame
    
 ## Summary
 
 After dropping 9th grade scores from Thomas High School the top 4 notable changes to the school disctric analysis are as follow:
  1. The percentage of passing students at THS increased drastically from 65.1% to 90.6%
  2. THS moved up into the Top 5 performing schools at the number 2 spot
  3. The average math score, % passing math, % passing reading, and % overall passing dropped by a small margin in the District Summary
  4. School spending values increased slightly in both the $585-639 and $630-644 ranges
  
