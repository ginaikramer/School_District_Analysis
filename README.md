# School_District_Analysis
## Overview
My client, Maria with the City School System, has been informed of possible inaccurate information that was provided to me for a recent school district data analysis project I performed for her. The innaccurate data includes ninth grade math and reading scores from Thomas High School.  Maria has requested an updated analysis to ensure data integrity and to allow the school board to make decisions based on accurate data. 

Therefore, the purpose of this project is to exclude the inaccurate data from the analyzed data set and perform calculations and analysis against the updated data. Once calculations and analysis are performed, I can provide updated reports and a summary of the impact that excluding the inaccurate data had overall.   

## Results
### How is the district summary affected:
The district summary was not significantly affected by the updated analysis. In compariing [Original School Analysis](/Resources/PyCitySchools.htm). with Y, the following observations were made:
- The updated district summary included analysis for 38,709 students versus the original 39,170 students. This is a delta of 461 students. 
- The updated district summary shows a 0.1 decrease in Average Math Score, from 79.0 to 78.9.
- The updated district summary shows no change in the Average Reading Score, keeping at 81.9 for both.
- The updated district summary shows a 0.2% decrease in the percentage of students passing math (% Passing Math), from 75% to 74.8%.
- The updated district summary shows a 0.3% decrease in the percentage of students passing reading (% Passing Reading), from 86% to 85.7%.
- The updated district summary shows a 0.1% decrease in the percentage of students passing both math and reading (% Overall Passing), from 65% to 64.9%.
- 


### How is the school summary affected:
### How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to other schools?
### Howd does replacing ninth-grade scores affect the following:

  - ![2017 Stock Analysis](/VBA_Challenge_2017_table.png)  

  - ![2018 Stock Analysis](/VBA_Challenge_2018_table.png)  

 
## Summary
- What are the advantages or disadvantages of refactoring code?
  - Advantages include:
    - The code is easier for the author and others to read and understand
    - The code is easier to perform troubleshooting to catch issues
    - The code is easier to maintain over time
  - Disadvantages include:
    - The action of refactoring can become very time-consuming 
    - Time spent might not be worth the positive gain from refactoring
    - There's a risk of the person refactoring causing bugs in the existing code
  
- How do these pros and cons apply to refactoring the original VBA script?
   - Refactoring the code meant I had to spend additional time making the updates and it added risk that I could introduce bugs into code that was already working. 
     - I actually did make some mistakes but was able to overcome them using the Debugger and Messageboxes to step through actual data.
   - Refactoring the code allowed me to add additional comments that will make it easier for me or others on my team to make future updates
   - Based on the comparison of execution times between the original and refactored code, refactoring the code does provide efficiency gains which can benefit clients like Steve
     - The refactored code saved around 0.17 seconds for calculating 2017 data
     - The refactored coded saved half a second or 0.5 seconds for calculating 2018 data
     - These time savings will be beneficial when applying this code to large volumes of stock data
