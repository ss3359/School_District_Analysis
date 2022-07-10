# School_District_Analysis
The purpose of this project is to give an overall of students performace of standarized tests in math and reading from various public schools in the state of Colorado. We have conducted this project by using Jupyter Notebook, a software that inherits a python library that creates dataframes called Pandas.

# Overview of The School District Analysis
The School Board in the State of Colorado has notified one of the principals of the School that the file students_complete.csv shows altered reading and math grades for Thomas High School ninth graders. We observe that if the data shows a significant amount of change if we ignore the scores generated by the Thomas High School ninth graders. We have conducted our findings using Jupyter Notebook, a web-based interactive computational enviornment for creating notebook documents. 


# Results
In this project, we are observing how the data is changed overall when we eliminate the ninth grade reading and math scores from Thomas High School. From the change in the data, this is what we have observed. 

   ### 1. How is the district summary affected? 
   These were the following results displayed for the school district summary. The first results is the district summary before the scores for Thomas High School were removed. The results is shown below. 
<img width="1363" alt="Screen Shot 2022-07-10 at 6 18 08 AM" src="https://user-images.githubusercontent.com/104328106/178144605-afe9f7ff-e5ff-4d15-988a-4460b93ef0ba.png">

This is the results for the district summary shown below, but the reading and mathematics scores for Thomas High School were removed. There is a change of percentage of passing scores for the district. 

<img width="1326" alt="Screen Shot 2022-07-10 at 6 21 17 AM" src="https://user-images.githubusercontent.com/104328106/178144734-3d708eca-2431-402d-9944-46d7646ab5ce.png">

### 2. How is the school summary affected? 
From the previous results, we see that there was a percent decrease in passing scores when the ninth grade test scores were removed. However, there was only a minor percent decrease. We expect to see a different reusult for the school summary. Shown below is the school summary before the scores from Thomas High School were removed. 

<img width="730" alt="Screen Shot 2022-07-10 at 6 34 07 AM" src="https://user-images.githubusercontent.com/104328106/178145124-1f9e8c18-58dd-42ea-994d-e6a77dcaf371.png">

Here is the similar school summary data frame with the scores from Thomas High School removed. 

<img width="872" alt="Screen Shot 2022-07-10 at 8 20 05 AM" src="https://user-images.githubusercontent.com/104328106/178148840-561b002e-e447-445a-9617-0c8e6fb3e545.png">

Comparing both data frames, we see there is a minor percent decrease of passing scores for reading, math, and overall passing. There is not a change in the data. To prove this, we have printed out the top five performing schools in the district. Here are the data frames displaying the top five schools in the distict without the scores removed. 

### 3. How does replacing the ninth graders' math and reading scores affect Thomas High Schools performance relative to other schools? 
With a percent change occuring after the test scores removed, Thomas High School still remained the second best performing high school in terms of their test scores. Here is the data frame representing the top five performing high schools in the district without the test scores removed. 

<img width="1196" alt="Screen Shot 2022-07-10 at 7 24 22 AM" src="https://user-images.githubusercontent.com/104328106/178146813-3f3ae3e3-07b0-4de1-998b-58b69020234e.png">

Here is the same data frame with the test scores removed. 

<img width="867" alt="Screen Shot 2022-07-10 at 8 21 49 AM" src="https://user-images.githubusercontent.com/104328106/178148907-e566c80c-1733-4b54-961a-049cc63a7b97.png">


Clearly, we can observe that the removal of the scores did not alter the schools ranking. Also, it did not alter the bottom five schools whatsoever. 

### 4. How does replacing the ninth-grade scores affect the following: 

#### a. The Scores By School Spending 
What we see is that there is not a change of percent of passing scores for math and reading. Here are the data frames for math and reading without the test scores for Thomas High School ninth graders removed respectively: 

##### Math Scores By Grade Level: 
<img width="356" alt="Screen Shot 2022-07-10 at 8 54 05 AM" src="https://user-images.githubusercontent.com/104328106/178150119-b24076f7-7473-4fb2-8d39-f68767a38e08.png">

##### Reading Scores By Grade Level: 
<img width="325" alt="Screen Shot 2022-07-10 at 8 56 08 AM" src="https://user-images.githubusercontent.com/104328106/178150186-5dce3186-61c7-4abe-8b4b-b1cc8500af6d.png">


Here are the test scores for math and reading with the test scores for Thomas High School ninth graders removed. 

##### Math Scores By Grade Level (Refined): 
<img width="304" alt="Screen Shot 2022-07-10 at 9 01 42 AM" src="https://user-images.githubusercontent.com/104328106/178150401-dcb9f729-48f5-4415-87b9-415da1e6db35.png">


##### Reading Scores By Grade Level (Refined): 
<img width="311" alt="Screen Shot 2022-07-10 at 9 01 10 AM" src="https://user-images.githubusercontent.com/104328106/178150380-d0f98fc7-92ab-44a4-9518-f4635e216266.png">

#### b. The Scores By School Spending
In both cases, we have found that the spending for Thomas High School is in between $631 fo $645 per student. However, there is a change of percentages of passing test scores when the scores from the Thomas High School ninth-graders are removed. Here is the data frame of test scores by school spending before the alteration of the data: 
<img width="729" alt="Screen Shot 2022-07-10 at 9 15 05 AM" src="https://user-images.githubusercontent.com/104328106/178150955-f7f22fbf-4bb4-481b-8219-bc7b70c82e80.png">


Here is the same data frame with the Thomas High School ninth-grader test scores removed: 
<img width="724" alt="Screen Shot 2022-07-10 at 9 18 28 AM" src="https://user-images.githubusercontent.com/104328106/178150996-af6348d6-8db0-440e-ba91-a09f41d1ee06.png">

Notice that schools whose spending per student is less than $586 remained the same for both data frames. The scores for schools whose spending per student in between $646 to $675 has not changed either. The test scores have increased for each row entry of data for schools whose student spending is in between $586 to $630 and $631 and $645 respectively. 

#### c. The Scores By School Size

By observing the test scores by school size, there is not much of a change in test scores occuring without and with the test scores removed. Here is the data frame of the test scores by school size without the scores from the Thomas High School ninth graders removed: 

<img width="674" alt="Screen Shot 2022-07-10 at 9 31 38 AM" src="https://user-images.githubusercontent.com/104328106/178151496-f05f0d1b-dd37-438a-a389-822c0895d0b0.png">

Here are the test scores by school size with the test scores removed: 
<img width="668" alt="Screen Shot 2022-07-10 at 9 32 35 AM" src="https://user-images.githubusercontent.com/104328106/178151537-95a02c12-814e-4ec7-943c-e59151111115.png">



# Summary






