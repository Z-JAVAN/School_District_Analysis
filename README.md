# School_District_Analysis
## Project Overview:</br>
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
##### Process:<br>
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

Original Analysis:<br>

Experimental data of 461 ninth-grade students at Thomas High School were converted to zero data, which recalculated math acceptance, reading acceptance, and overall acceptance percentages. The total number of students did not change because the number of student IDs was implemented which was not converted to zero data.
We analyzed all the details of the ninth grade Thomas High School students, this analysis was done twice. The first trial of this analysis consisted of a complete set of student data. In the second experiment of this analysis, the ninth grade students of Thomas High School had their scores removed from the calculations and the total grades of the ninth grade of Thomas High School were replaced with NaN.

 ![picture4.png](/Resources/picture4.png)<br/>

When comparing the two graphs, the omission of less than 500 test scores affected the data set of approximately 40,000 students. This change was less than one percent difference, and the numbers continue to be rounded to the nearest whole number.
 </br>
 ![picture1.png](/Resources/picture1.png)<br/>
###### Analysis of various factors affecting students

Increasing the costs of each student is not related to the average grades and the percentage of acceptance. By reviewing and analyzing the data, we conclude that there are more relevant factors than the budget that determine the average grades of students.
