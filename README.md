# School_District_Analysis
## Overview
My client, Maria with the City School System, has been informed of possible inaccurate information that was provided to me for a recent school district data analysis project I performed for her. The inaccurate data includes ninth grade math and reading scores from Thomas High School.  Maria has requested an updated analysis to ensure data integrity and to allow the school board to make decisions based on accurate data. 

Therefore, the purpose of this project is to exclude the inaccurate data from the analyzed data set and perform calculations and analysis against the updated data. Once calculations and analysis are performed, I can provide updated reports and a summary of the impact that excluding the inaccurate data had overall.  

I referenced and compared the following two files when creating this report: 
- [Original School Analysis](/PyCitySchools.ipynb) 
- [Updated School Analysis](/PyCitySchools_Challenge_testing.ipynb) 

## Results
### How is the district summary affected:
The district summary was not significantly affected by the updated analysis. In comparing the original and updated reports below, the following observations were made:
- The updated district summary included analysis for 38,709 students versus the original 39,170 students. This is a delta of 461 students. 
- The updated district summary shows a 0.1 decrease in Average Math Score, from 79.0 to 78.9.
- The updated district summary shows no change in the Average Reading Score, keeping at 81.9 for both.
- The updated district summary shows a 0.2% decrease in the percentage of students passing math (% Passing Math), from 75% to 74.8%.
- The updated district summary shows a 0.3% decrease in the percentage of students passing reading (% Passing Reading), from 86% to 85.7%.
- The updated district summary shows a 0.1% decrease in the percentage of students passing both math and reading (% Overall Passing), from 65% to 64.9%.

**ORIGINAL DISTRICT SUMMARY:**
![Original District Summary](/Resources/District_Summary_Original.png)  

**UPDATED DISTRICT SUMMARY:**
![Updated District Summary](/Resources/District_Summary_Updated.png)  

### How is the school summary affected:
The school summary was not significantly affected by the updated analysis. In comparing the original and updated reports below, all of the school summary output is the same with the exception of the **Thomas High School** summary which included the following observations:
- The updated school summary shows a 0.07 decrease in Average Math Score.
- The updated district summary shows a 0.05 increase in Average Reading Score.
- The updated district summary shows a 0.09% decrease in the percentage of students passing math (% Passing Math).
- The updated district summary shows a 0.29% decrease in the percentage of students passing reading (% Passing Reading).
- The updated district summary shows a 0.32% decrease in the percentage of students passing both math and reading (% Overall Passing).

**ORIGINAL SCHOOL SUMMARY:**
![Original School Summary](/Resources/School_Summary_Original.png)  

**UPDATED SCHOOL SUMMARY:**
![Updated School Summary](/Resources/School_Summary_Updated.png) 

### How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to other schools?
Replacing the ninth graders' math and reading scores don't significantly affect Thomas High School's performance relative to the other schools. 

In comparing the top five schools from the original analysis versus the top five schools from the updated analysis, Thomas High School is still considered to be in the top five (even with the ninth graders' math and reading scores excluded).  


**ORIGINAL TOP FIVE SCHOOLS:**
![Original Top_Five](/Resources/School_Summary_Top_Schools_Original.png)  

**UPDATED TOP FIVE SCHOOLS:**
![Updated Top_Five](/Resources/School_Summary_Top_Schools_Updated.png) 

**NOTE:** As an added note, in both analyses, the bottom 5 schools remained the same between the original analysis and the updated one.

### How does replacing ninth-grade scores affect the following:
- Math and reading scores by grade
  - Math and reading scores by school, by grade were unchanged with the exception of the exclusion of Thomas High School's ninth grade scores (signified by **nan**)

  ![1](/Resources/Math_Scores_by_Grade_Updated.png)  
  ![1](/Resources/Reading_Scores_by_Grade_Updated.png) 

- Scores by school spending
  - While there were slight differences in the tenths or hundredths, Scores by School Spending remained unchanged when formatted as requested:
    - The Average Math Score and Average Reading Score for all 4 spending bins in both the Original and Updated reports were equal when rounded to the nearest tenth
    - The % Passing Math, % Passing Reading and % Overall Passing for all 4 spending bins in both the Original and Updated reports were equal when rounded to nearest whole number

**SCORES by SCHOOL SPENDING for both Original & Updated Reports:**
![1](/Resources/Scores_by_School_Spending_Updated.png) 

- Scores by school size
  - While there were slight differences in the tenths or hundredths, Scores by School Size remained unchanged when formatted as requested:
    - The Average Math Score and Average Reading Score for all 3 sizes in both the Original and Updated reports were equal when rounded to the nearest tenth
    - The % Passing Math, % Passing Reading and % Overall Passing for all 3 sizes in both the Original and Updated reports were equal when rounded to nearest whole number
 
 **SCORES by SCHOOL SIZE for both Original & Updated Reports:**
![1](/Resources/Scores_by_School_Size_Updated.png) 


- Scores by school type
  - While there were slight differences in the tenths or hundredths, Scores by School Type remained unchanged when formatted as requested:
    - The Average Math Score and Average Reading Score for the 2 types in both the Original and Updated reports were equal when rounded to the nearest tenth
    - The % Passing Math, % Passing Reading and % Overall Passing for the 2 types in both the Original and Updated reports were equal when rounded to nearest whole number

**SCORES by SCHOOL TYPE for both Original & Updated Reports:**
![1](/Resources/Scores_by_School_Type_Updated.png) 


 
## Summary
As noted in the results details above, there were a few minor changes observed when performing an updated analysis. Due to the exclusion of the Thomas High School ninth graders' math and reading scores:
- There were 461 less students analyzed in the Updated District Summary Report. 
- The Updated District Summary showed a slight decrease in Average Math Score, % Passing Math, % Passing Reading and % Overall Passing.
- The Updated District Summary showed no change in Average Reading Score. 
- The Updated School Summary showed a slight decrease in Average Math Score, % Passing Math, % Passing Reading and % Overall Passing.
- The Updated School Summary showed a slight increase in Average Reading Score. 


However, in total Summary, there was no significant differences between the Original School District Analysis and the Updated School District Analysis.  
