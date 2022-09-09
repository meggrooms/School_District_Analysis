# School District Analysis
Standardized Test Analysis, the Correlation Between Test Scores and Budget, and Calculating for Academic Integrity


----------------
## Purpose
Initially my job was to rank 15 Colorado high schools based on student performance based on a variety of factors, including test scores, school size, type of school, & per capita budget. This portion of the project focused primarily on cleaning data and performing calculations but there were some errors in the data. A subset of students were assigned incorrect prefix and suffix designations, important data was missing, and column organization wasn't intuitive. I was tasked with cleaning and presenting the data.
<BR>
<br>


### Topics Covered
• Jupyter Notebook <br>
• Read an external CSV file<br>
• Format a DataFrame column<br>
• Determine data types of row values<br>
• Retrieve data from specific columns<br>
• Merge, filter, slice, and sort<br>
• Apply the groupby() function<br>
• Use multiple methods to perform a function<br>
• Perform mathematical calculations on columns<br>
<br>
<br>

# Results
 


<BR>
Original & adjusted district score summary
 <BR>

<img src="https://github.com/meggrooms/School_District_Analysis/blob/main/Resources/Images/Orig_District_Summary.png">

 <img src="https://github.com/meggrooms/School_District_Analysis/blob/main/Resources/Images/Adj_District_Summary.png">
 <BR>
  <BR>
   <BR>

Thomas High School's original & adjusted performance
  <BR>

<img src="https://github.com/meggrooms/School_District_Analysis/blob/main/Resources/Images/01_top_schools.png">
<img src="https://github.com/meggrooms/School_District_Analysis/blob/main/Resources/Images/01_bottom_schools.png">
 <BR>
  <BR>
   <BR>
  

  
School size summary
  <BR>
  <img src="https://github.com/meggrooms/School_District_Analysis/blob/main/Resources/Images/School_Size_Summary.png">
 <BR>
  <BR>
   <BR>
  
Test scores by per capita budget   
   <BR>
   <img src="https://github.com/meggrooms/School_District_Analysis/blob/main/Resources/Images/Scores_per_capita.png">
    
 <BR>
  <BR>
   <BR>
  
Thomas High School is a charter school, which has significantly higher passing rates, with a 36 point difference in overall passing. 
 <BR>
 <img src="https://github.com/meggrooms/School_District_Analysis/blob/main/Resources/Images/school_type.png">
  <BR>
  <BR>
   <BR>
An example of creating a database for scores by grade

  <img src="https://github.com/meggrooms/School_District_Analysis/blob/main/Resources/Images/by_grade_DF.png">
 <BR>
  <BR>
   <BR>
   

 
 ## How the school district metrics were affected by the changes in the data.
<BR>
• There was a dramatic shift in Thomas High School's passing rate, from 91% to 65%.
<BR>
• Thomas High School dropped from the top 5 schools to the middle of the pack.
<BR> 
• Ninth grade scores from Thomas High School are now represented by NaN, a null value.
<BR>
• 

•Schools of small and medium size perform at the same rate, while large schools overall passing rates drop by 35%
 <BR><BR><BR>
 
 
### How is the district summary affected?
The original metrics showed a significant drop in reading scores.
<BR>
<img src="https://github.com/meggrooms/School_District_Analysis/blob/main/Resources/Images/Orig_District_Summary.png">
<img src="https://github.com/meggrooms/School_District_Analysis/blob/main/Resources/Images/Adj_District_Summary.png">
<BR>
 <BR>
### How is the school summary affected?
After re-running the school summary data, it's clear that Thomas High School's overall passing percentage was much lower.
 <Br>
<img src="https://github.com/meggrooms/School_District_Analysis/blob/main/Resources/Images/before_school_summary.png">
  <BR>
<img src="https://github.com/meggrooms/School_District_Analysis/blob/main/Resources/Images/after_thomas_school_summ.png">
   <BR>
   <BR>

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Thomas High School's original school ranking was #2 of 15. Replacing the scores result in a ranking solidly in the middle of the pack
  <br>
  <img src="https://github.com/meggrooms/School_District_Analysis/blob/main/Resources/Images/Top_Schools.png">
 <BR>
  <BR>
   <BR>

### How does replacing the ninth-grade scores affect the following:

**Math & reading scores by grade**
     <BR>
      Originally Thomas High School has an 83.6% average math score and 83.7% reading for the 9th grade tests. These scores have been replaced with NaN, a null value.
    <BR>
     <BR>
**Scores by school spending**
     <BR>
Thomas High Schools spends $638 per student, which typically produces an overall passing rate of 91%. THS, however, scores 63%
<BR>  
    <img src="https://github.com/meggrooms/School_District_Analysis/blob/main/Resources/Images/Scores_per_capita.png">
 
  <img src="https://github.com/meggrooms/School_District_Analysis/blob/main/Resources/Images/spending_per_student.png">
      
