# School_District_Analysis
## Overview of the school district analysis::</br>
School district performance analysis was performed using the Jupyter notebook with Python, the Panda Library, and the Numpy Library. We first provide a preliminary analysis based on data collected from many students and schools across the school district.
  There appear to be some anomalies in the data, especially in the math and reading grades of ninth-grade high school students.
We want to look at the effect of changing all grades 9 in math and reading in Thomas High School - we will now look at how this change has affected various parts of the analysis over time, including Thomas 9 high school grades.
  The consequences of deleting potentially inaccurate data are also discussed.
  
### Resources:<br>
<br>Data Source: schools_complete.csv<br>
Data Source: students_complete.csv<br>
Sofware: Jupyter Notebook 6.3.0<br>
Library: Pandas<br>
Library: Numpy<br>
Language: Python 3.6.7<br>
#### Process:<br>
Open Jupyter Notebook files from local directories using a development environment.
Read an external CSV file into a DataFrame.
Format a DataFrame column.
Determine data types of row values in a DataFrame.
Retrieve data from specific columns of a DataFrame.
Merge, filter, slice, and sort a DataFrame.
Apply the groupby() function to a DataFrame.
Use multiple methods to perform a function on a DataFrame.
Perform mathematical calculations on columns of a DataFrame or Series.<br>

#### Results :<br>
Experimental data of 461 ninth-grade students at Thomas High School were converted to zero data, which recalculated math acceptance, reading acceptance, and overall acceptance percentages. The total number of students did not change because the number of student IDs was implemented which was not converted to zero data.
We analyzed all the details of the ninth grade Thomas High School students, this analysis was done twice. The first trial of this analysis consisted of a complete set of student data. In the second experiment of this analysis, the ninth grade students of Thomas High School had their scores removed from the calculations and the total grades of the ninth grade of Thomas High School were replaced with Nan.


## orginal<br>
 ![picture01.png](/Resources/picture01.png)<br/>

Adding Nan to all math grades and reading Thomas  high schoolGrade 9 did not have much effect on the result of the analysis.  It should be noted that the number of students was 461 and the total number of students was 39,170, so removing the math grade and reading did not have much effect on the result.
 ## Updated  </br> 
 ![picture02.png](/Resources/picture02.png)<br/>


The following changes occurred when the Thomas ninth grade students (grade was deducted from the calculations)
Total Budget
Average Math Score
Average Reading Score
% Passing Math (The percentage of students that passed math.)
% Passing Reading (The percentage of students that passed reading.)
% Overall Passing (The percentage of students that passed math and reading.)
and using the datas , we can see that all of that has been reduced. 

  ## Reading Scores - Original information
  ![picture3.png](/Resources/picture3.png)<br/>
 ##  Updated information
.![picture4.png](/Resources/picture4.png)<br/>
## Math Scores - Original information
![picture5.png](/Resources/picture4.png)<br/>
## Updated information
![picture6.png](/Resources/picture4.png)<br/>

