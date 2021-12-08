Performance analysis of tennis players over the decades

Members of Group 4:
Harikrishnan Sundaram 
Malhar Joshi
Dhruv Jani
Yash Chaudhari 


AIM OF THE PROJECT:
To draw insights from a Tennis dataset w.r.t players age and correlation with the win and loss trend and analyzing the change in participation and performance of the tennis players from major countries like USA, UK, etc. In the earlier days of Tennis, the players would retire by the age of 30, but in recent times, the players have been playing at the age of around 35 and performing well. We will be analyzing the change in the pattern of participation Among the tennis players.

RESEARCH QUESTIONS:
What is the win percentage of players having the age in the range of 20-25, 25-30, 30-35 vs 35 and above for male and female players?
What is the different winning percentage of a player from a specific country on different surfaces?
The percentage of wins between players from the US vs other popular countries and between age groups ranging from 20-25, 25-30, 30-35 vs 35 and above.
What factor is influencing the change in the trend of all male and female players winning the championship? If it's the surface, the age, or some other reason.


ANALYSIS:
For this project we will be using Descriptive Analysis. Descriptive analysis is the process of using statistical techniques to describe or summarize a set of data. It is popular for its ability to generate accessible insights from otherwise uninterpreted data.



Data Preprocessing Steps
We have established steps we’ll need to go through to make sure our data is successfully preprocessed.

1. Data quality assessment

2. Data cleaning

3. Data reduction


**1. Data quality assessment**

First we take a good look at our data and get an idea of its overall quality, relevance to our project, and consistency. There are a number of data anomalies and inherent problems to look out for in almost any data set, for example:

Mismatched data types: When you collect data from many different sources, it may come to you in different formats.

Mixed data values: Perhaps different sources use different descriptors for features – for example, man or male. These value descriptors should all be made uniform.

Data outliers: Outliers can have a huge impact on data analysis results.

Missing data: Take a look for missing data fields, blank spaces in text, or unanswered survey questions. This could be due to human error or incomplete data. To take care of missing data, you’ll have to perform data cleaning.

Since all our data comes from a single source we can conclude that there are no inconsistencies with respect to the quality, data types and data values.


**2. Data cleaning**

Data cleaning is the process of adding missing data and correcting, repairing, or removing incorrect or irrelevant data from a data set. Dating cleaning is the most important step of preprocessing because it will ensure that your data is ready to go for your downstream needs.

Data cleaning will correct all of the inconsistent data you uncovered in your data quality assessment. Depending on the kind of data you’re working with, there are a number of possible cleaners you’ll need to run your data through.

Missing data There are a number of ways to correct for missing data, but the two most common are:

Ignore the tuples: A tuple is an ordered list or sequence of numbers or entities. If multiple values are missing within tuples, you may simply discard the tuples with that missing information. This is only recommended for large data sets, when a few ignored tuples won’t harm further analysis.

Manually fill in missing data: This can be tedious, but is definitely necessary when working with smaller data sets.

Take the mean of the data: We can take the mean of the data to fill the missing values. Generally, replacing the missing values with the average is a crude way of treating missing values. Depending on the context, like if the variation is low or if the variable has low leverage over the response, such a rough approximation is acceptable and could give satisfactory results. In this case, since you are saying it is a categorical variable — this step may not be applicable


**3. Data reduction**


The more data you’re working with, the harder it will be to analyze, even after cleaning and transforming it. Depending on your task at hand, you may actually have more data than you need. Data reduction not only makes the analysis easier and more accurate, but cuts down on data storage.

It will also help identify the most important features to the process at hand.

Attribute selection: Similar to discreditization, attribute selection can fit your data into smaller pools. It, essentially, combines tags or features, so that tags like male/female and professor could be combined into male professor/female professor.

Numerosity reduction: This will help with data storage and transmission. You can use a regression model, for example, to use only the data and variables that are relevant to your analysis.

Dimensionality reduction: This, again, reduces the amount of data used to help facilitate analysis and downstream processes. Algorithms like K-nearest neighbors use pattern recognition to combine similar data and make it more manageable.



Few of the graph analysis below:



![image](https://user-images.githubusercontent.com/69467542/142350967-0f581904-3d69-4718-8ec1-13449f27ed33.png)

The above graph gives a view of country vs surface which can help us understand which country plays better on which surface. This can help us understand where players of a certain country need to improve. Eg: USA plays very good on Hard surfaces as compared to Grass. This shows us that players in United States need to focus on Grass courts more.


![image](https://user-images.githubusercontent.com/69467542/142350358-4aa9d45e-66a9-40b0-ab00-d006e42d1467.png)

The above graph gives a view of age vs year of male players, which shows us which age group performed well given an year. The colors represent the following

1. Blue : Ages 20 to 25

2. Red: Ages 25 to 30

3. Green: Ages 30 to 35

4. Orange: Ages 35 and above

As we can see, players between the ages of 25 and 30 had consistent wins in games as compared to other age groups.

Age group 20 to 25 had some years with higher win percentage but weren't consistent for long.

Age groups 30 to 35 and 35 and above had the worst win percentages.




![image](https://user-images.githubusercontent.com/69467542/142350441-24443c6d-f79f-4d12-a656-7dc22712d648.png)

The above graph gives a view of age vs year of female players, which shows us which age group performed well given an year. The colors represent the following

1. Blue : Ages 20 to 25

2. Red: Ages 25 to 30

3. Green: Ages 30 to 35

4. Orange: Ages 35 and above

We can conclude that female players are more likely to win when they are in the age group of 20 to 25, not consistent, but this age group has the maximum wins overall.

Female players are leaste likely to play and win with age above 35.

CONTINGENCY TABLE
In a contingency table, each cell represents the combination of the two variables. You need to read across the table to witness how the two variables i.e., independent, and dependent variables relate to each other.

![image](https://user-images.githubusercontent.com/69467542/145259556-dc675bd3-f92f-4bd6-87a6-647bbfa58a6c.png)

![image](https://user-images.githubusercontent.com/69467542/145259587-4fffe5d9-85e4-478d-b542-bc1aa080b4c0.png)

![image](https://user-images.githubusercontent.com/69467542/145259619-4cc423cb-1473-4170-bf72-785a79f1ccf5.png)
![image](https://user-images.githubusercontent.com/69467542/145259638-4c912f80-7d8a-4c69-bcf6-7695861f30d7.png)
![image](https://user-images.githubusercontent.com/69467542/145259665-d620f263-5c2f-4729-b3cf-0fb82ac94cfe.png)


**CONCLUSION**

**Research Questions:**

Q1. What is the win percentage of players having the age in the range of 20-25, 25-30, 30-35 vs 35 and above for male and female players?

--> Refer Figure 2 and 3.

Q2. What is the different winning percentage of a player from a specific country on different surfaces?

--> Refer Figure 1.

Q3. The percentage of wins between players from the US vs other popular countries and between age groups ranging from 20-25, 25-30, 30-35 vs 35 and above.

--> Refer Figure 11, 12, 13, 14.

Q4. What factor is influencing the change in the trend of all male and female players winning the championship? If it's the surface, the age, or some other reason.

--> Major deciding factors were Age and height.
<br></br>
**Interesting things About Our Project:**

Q1: What was unique about the data?  Did you have to deal with imbalance? What data cleaning did you do? Outlier treatment?  

--> This dataset is extremely good for descriptive analysis as it contains data from year 1970 to 2020 which contains ATP and WTA tennis tours. The data was raw initially and some of the features were not in the expected format such as Age which caused imbalance. We used various methods to clean the dataset for our analysis. There were missing/null values present so we calculated the total percentage of missing data and dropped the columns if error percentages were high. We replaced some values with mean value of the column or with a string. We used data reduction technique to streamline the analysis.

Q2. Did you create any new additional features / variables?

--> Yes. We created the field “Age” from “Date of Birth” for giving better analysis while comparing age wise performance in tournaments. Also we divided the age into 5 different age groups to better understand our dataset.

Q3. What was the process you used for evaluation?  What was the best result?

--> We used descriptive analysis to evaluate the dataset. Descriptive analysis is the process of using statistical techniques to describe or summarize a set of data. It is popular for its ability to generate accessible insights from otherwise uninterpreted data.

Q4. What were the problems you faced? How did you solve them?

--> Since the dataset was meant for descriptive analysis, meaningful visualization of the dataset was quite a challenge.

Q5. What future work would you like to do? 

--> We would like add data about players physical and cardiological strength so that we can give predictive analysis.

Q6. Instructions for individuals that may want to use your work

--> Implement an ML model which can be further integrated into a webpage for better user accessibility.











Data Resources: 
https://github.com/JeffSackmann/tennis_atp

https://github.com/JeffSackmann/tennis_wta

Project Github:- 
https://github.com/malharjoshi/KDD_Project


 


