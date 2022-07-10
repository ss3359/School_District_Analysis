# School_District_Analysis

This is our project searching for percent changes before or after test scores have been removed because of suspicion of acadmemic dishonesty. 

# Overview of The School District Analysis 

The school board has informed the chief data scientist, Maria, and here supervisor about the fife, "students_complete.csv" showing evidence of academic dishonesty for Thomas High School ninth graders. In this project, we observe if the data presents a significant change if the scores of Thomas High School ninth graders are removed. Through the duruation of data cleansing and research, we have used Jupyter Notebook. Jupyter Notebook is a web-based computing platform which combines live coding and manipulation of dataframes. Through this software, we have used Python to compute our findings.  

# Results

In this project, we observe how the reading and math scores are affection given the following scenarios 

#### 1. How is the district summary affected? 

We have found a minor change in the dataframes before and after the Thomas High School ninth graders' test scores were removed. Here is dataframes displaying the district summary before the Thomas High School ninth grader test scores are removed


<img width="814" alt="Screen Shot 2022-07-10 at 11 39 29 AM" src="https://user-images.githubusercontent.com/104328106/178155985-e980b695-0f4e-4e1e-94cc-1c79bdb17b8c.png">

Here is the district summary dataframe after the scores for Thomas High School ninth graders are removed: 

<img width="805" alt="Screen Shot 2022-07-10 at 11 42 16 AM" src="https://user-images.githubusercontent.com/104328106/178156017-620532ea-9825-4728-8b51-5e2120ac7350.png">

From these two dataframes, there is a minor decrease in percentages passing in math, reading, and the overall percentage. 

#### 2. How is the school summary affected?

Based on the data clensing, we have found a small percent decrease in the passing math, reading and overall percentage of passing scores. What is interesting is that the Average Reading Score for Thomas High School has increased after the Thomas High School test scores for ninth graders were removed. 

Here is the data frame displaying the school summaries in the district before the scores from the Thomas High School ninth graders were removed. 


<img width="867" alt="Screen Shot 2022-07-10 at 12 22 05 PM" src="https://user-images.githubusercontent.com/104328106/178157289-fd8a4fad-c082-4aa0-bfbc-92eb45fc30a9.png">

Here is the similar dataframe after the test scores from the Thomas High School ninth graders were removed. 

<img width="864" alt="Screen Shot 2022-07-10 at 12 23 45 PM" src="https://user-images.githubusercontent.com/104328106/178157323-8c828fb9-2795-4389-bc3c-4ad0d2b05e60.png">


Notice that the Average Reading Score from Thomas High School has increased. Otherwise, the overall the passing percentages for math, reading, and overall have decreased only a small amount. 

#### 3. How does replacing ninth graders' math and reading scores affect Thomas High Schools performance relative to the other schools? 

Since there was a minor decrease in percentage of passing math, reading, and overall passing, this decrease did not reflect their school ranking as one of top five performing schools. 

Here is the dataframe representing the high performing schools in the district without the Thomas High School ninth graders test scores removed. This was sorted by the passing overall percent from highest to lowest. 


<img width="886" alt="Screen Shot 2022-07-10 at 12 30 59 PM" src="https://user-images.githubusercontent.com/104328106/178157705-04520bf9-7857-4132-a9a3-a8c92e582db2.png">

Here is the similar dataframe with the scores removed. 

<img width="864" alt="Screen Shot 2022-07-10 at 12 31 26 PM" src="https://user-images.githubusercontent.com/104328106/178157724-16a2668b-ba21-47d9-9066-b44c758af73b.png">

Since there was little percent change from the scores by Thomas High School, it did not reflect their ranking whatsoever. 

#### 4. How does replacing the ninth-grade scores affect the following: 


##### a. Math and Reading Scores By Grade
Obviously, we have removed the scores for ninth graders from Thomas High School. Here are the dataframes representing the average test scores for math and reading for each school based on grade level. These dataframes are displayed before the scores from the Thomas High School ninth graders are removed. 

###### Math Scores By Grade Level: 


<img width="360" alt="Screen Shot 2022-07-10 at 12 45 37 PM" src="https://user-images.githubusercontent.com/104328106/178157986-42f2cd5b-3e1d-4464-8113-7cb41ebb93db.png">



###### Reading Scores By Grade Level: 


<img width="352" alt="Screen Shot 2022-07-10 at 12 46 06 PM" src="https://user-images.githubusercontent.com/104328106/178158006-c4fa5f84-6aeb-4e8c-91e9-30856368ebb1.png">


Here are the similar dataframes with the math and reading score from Thomas High School ninth graders removed. This is indicated as a 'NaN' entry in the respective dataframes. 


##### Math Scores By Grade Level (Refined): 

<img width="406" alt="Screen Shot 2022-07-10 at 12 50 48 PM" src="https://user-images.githubusercontent.com/104328106/178158142-c8df50ee-b1f9-4c23-be10-1cc880d33a6a.png">



##### Reading Scores By Grade Level (Refined): 

<img width="409" alt="Screen Shot 2022-07-10 at 12 51 00 PM" src="https://user-images.githubusercontent.com/104328106/178158148-2320e2b7-9326-4e70-a0ac-865e6f099fc7.png">

After the removial of the grades, there seems to be no change in the data at all. 



#### b. Scores By School Spending: 
In this scenario, we have created four groups to label each school in the district based on spending per student. Thomas High School has a student spending in between $631 and $645 per student. 

Here is the data frame displaying the test scores in regards to spending ranges per student, without removing the test scores made by Thomas High School ninth graders. 


<img width="707" alt="Screen Shot 2022-07-10 at 12 59 37 PM" src="https://user-images.githubusercontent.com/104328106/178158365-2c347cd4-46f0-4f5a-bb4a-8aafcc37ef91.png">

Here is the similar dataframe with the test scores made by Thomas High School ninth graders removed. 

<img width="701" alt="Screen Shot 2022-07-10 at 12 59 16 PM" src="https://user-images.githubusercontent.com/104328106/178158384-52d1aecd-0bd4-46d8-a075-7500a37ffeaa.png">





