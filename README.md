# School_District_Analysis
## Project Overview
  <p>
   The school board has notified that the "students_complete.csv" file shows evidence of academic dishonesty on "reading" and "math" grades for Thomas High School ninth graders  which appears to have been altered.
  
  Also the school board does not know the full extent of the academic dishonesty, so they want to hold on state-testing standards and need help to solve this problem.
    Their requirement is to make Thomas High School with NaNs, so that rest of the data will remain intact.
</p>

## Purpose 
  <p>
  The purpose of this project is to analyze the School District data on basis of school budget, students scores as per their grades.
  Also to learn new insights which will give us clear view of results on each schools performance. 
  </P>

 ## Requirements:
  - A high-level snapshot of the district's key metrics, presented in a table format
  - An overview of the key metrics for each school, presented in a table format
  - Tables presenting each of the following metrics:
  - Top 5 and bottom 5 performing schools, based on the overall passing rate
  - The average math score received by students in each grade level at each school
  - The average reading score received by students in each grade level at each school
  - School performance based on the budget per student
  - School performance based on the school size 
  - School performance based on the type of school
  </p>
  
  ## Resources
  - Jupyter Notebook
  - Python 3.7.6
  - Dependencies
      - Python Pandas library
      - Python Numpy library

## Results:
<p>

- How is the district summary affected?
  
  <p align="left">
	<img src="Resources/school_district_summary.png" width="1000">
</p>

- How is the school summary affected?
    
  <p align="left">
	<img src="Resources/school_summary.png" width="1000">
</p>

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
     - The overall passing percentage for Thomas High School fell to 65%
     - The overall passing percentage for the entire district fell to 64.9%
     - Thomas High School was no longer included on the list of top five schools.

- How does replacing the ninth-grade scores affect the following:
	- The overall passing percentages of Thomas High School decreased by 0.11%
	- The average scores of Thomas High School for math and reading increased by 0.06
	- For the spending range of $630-644 per student, the overall passing percentage decreased by 0.1%
	- School rankings are unchanged. Thomas High School is still the second best performing school in the district with an overall passing rate of 90.63% among their tenth 	  through twelfth graders.
   
- **Math scores by grade**
    	
	<img src="Resources/math_scores_by_grade.png" width="500"> 
	
	
	
 -  **Reading scores by grade**	
	
        <img src="Resources/reading_scores_by_grade.png" width="400">
	
	
	
 - **Scores by school spending** 
    
	<img src="Resources/scores_by_school_spending.png" width="1000">
	
	
	
  - **Scores by school size**
   	 
	<img src="Resources/scores_by_school_size.png" width="1000">
	
	
	
  - **Scores by school type**
  	 
	<img src="Resources/scores_by_school_Type.png" width="1000">
	
  
</p>

## Summary: 

<p>
School district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
  
  In reviewing the last summary on School Types, this data change also affected the passing percentages that compared charter and district schools. Fortunately, it did not affect the average scores for these two school types. Removing the scores resulted in a reduction in charter school's passing percentages. Before the data change, charter schools had very high passing percentages: 94% passing math, 97% passing reading, 90% overall passing. After the data change, charter schools now have a 90% passing math, 93% passing reading, 87% overall passing. On the plus side, these rates are still far superior when compared to district schools.
</p>
