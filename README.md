# School_District_Analysis


## Overview of School District Analysis:

Analysis on school district performance using Jupyter Notebook with Python, and Pandas Library. 

The School Board would like to understand various performance metrics of the different school districts and schools. We provided an initial analysis based on data collected from many students and schools across the school district.

We needed to provide another analysis based on anomalies in the data with the 9th grade of Thomas High School. We needed to update the results and change of the scores of math and reading for 9th grade of Thomas High School to 'Nan' (which is the null value). This was due to an update we received from the School Board and higher up and this required updating all prior data.

The School Board will like to understand the impact of changing all the 9th graders math and reading scores at Thomas High School to 'Nan' (null value) - we will now review how this change impacted our intial analysis in parts by district, school spending, school type and school size.

## Analysis of results:


### How is the district summary affected?

-District Analysis - Original-

![Original district](https://user-images.githubusercontent.com/98680133/159214516-0c1e273c-ef01-4499-bba8-161d8b88c59d.png)

-District Anaylsis - Updated-

![Altered district](https://user-images.githubusercontent.com/98680133/159214523-0bb149ef-1218-4f2b-8c9f-b739bf38b3ef.png)

- The change of adding Nan to all 9th grade for Thomas High School Math and Reading scores did not create a huge change with the district analysis. There are only 461 students in 9th grade for Thomas High School, and given the total student count is 39,170, the 9th grade students for Thomas High School only make up 1.18% of the total student count which means thats the results of adding Nan into the data will not create a drastic change to the data.


### How is the school summary affected?

-Top Schools - Original-

![Original School Summary](https://user-images.githubusercontent.com/98680133/159218907-70bba338-b973-4766-85dc-fb5efe0c44d0.png)

-Top Schools - Updated-

![Altered School Summary](https://user-images.githubusercontent.com/98680133/159218914-f8b3c6b5-09ca-467b-bc28-1b91bf39fd7a.png)

- The ranks of the tops schools have not been affected by the update
- The average for math, reading and overall for Thomas High School has changed but not enough to change the rank of top 2.
- The % Passing Math, % Passing Reading and % Overall Passing difference between the original and updated was less then 0.5% which didnt create a huge impact.

## Math and Reading Scores by grade
-Math Scores Original-                               -Math Scores Updated-

![Math original](https://user-images.githubusercontent.com/98680133/159219747-37602c7e-8224-40aa-b3ca-0ced33c0812c.png)
![Math Altered](https://user-images.githubusercontent.com/98680133/159219811-255e2df8-f228-45a5-a50e-82288f58f424.png)

-Reading Scores Original-

![Reading Original](https://user-images.githubusercontent.com/98680133/159219929-bb66c514-ad4e-445a-a077-d72ed8f05ea0.png)

-Reading Scores Updated-

![Reading Altered](https://user-images.githubusercontent.com/98680133/159220014-c719c8a6-9e86-446f-92cd-a97d26566dfc.png)

- The only Difference here is that the 9th grade for Thomas High School was updated to Nan instead for math and reading.
- If we ran a sum or mean of the DataFrame, we will see differences due to the changes for Thomas High School.

## Scores by school spending

-Original school spending-

![Original Spending](https://user-images.githubusercontent.com/98680133/159220427-a64312b3-1dbf-413b-8df8-e221bdd137ca.png)

-Updated school spending-

![Altered Spending](https://user-images.githubusercontent.com/98680133/159220449-6ce00247-aac8-4aa3-96ed-950cf085de41.png)

-There was a slight change in school spending for the range of $630-644 due to Thomas High School being in that range. The changes were less then 0.01% which didnt change the metric range for the school.

## Score by school size

-Original school size-

![Original Size](https://user-images.githubusercontent.com/98680133/159220897-1d3d46ec-8b89-4d74-bdd8-aff4c8bce3bd.png)

-Updated school size-

![Altered Size](https://user-images.githubusercontent.com/98680133/159220954-7cb93a2c-6412-44a5-93cc-4dd92b709722.png)

-The score for the medium school size changed slighty by 0.01%. The changes were once again affected due to the 9th grade score changes.

## Score by school type

-Original school type-

![Original Type](https://user-images.githubusercontent.com/98680133/159221261-ab8a4ac4-e4e1-45bb-a98d-9a638c89ae1a.png)

-Updated school type-

![Altered Type](https://user-images.githubusercontent.com/98680133/159221309-46c1544b-e414-4d50-bdd9-7d3bae7edc46.png)

- Since Thomas High School is a charter school, they affect the Charter school type.
- The changes were affected by 0.01%. 
- The District school type was left unaffected.

## Final Summary

-District Analysis - changes to all scores decreased by less than 0.5% no impact to school or student count.
-Top School Ranking - The rank of Thomas High School did not change and they stayed at top 2 and the % Overall Passing decreased by less then 1%.
-Scores by School Size - The Medium (1000-2000) category were Thomas High School is grouped at decreased their percentage point by less then 0.1%.
-Scores by School Type - Only Charter type category was affected and it decreased by less then 0.1%.
