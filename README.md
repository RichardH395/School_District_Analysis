### School_District_Analysis

### Overview of the school district analysis:
The overview of this project is using Anaconda packages such as Jupyter Notebook with Pandas and other imported modules to provide data science, technical analysis and insights to PyCitySchools District. Using the data provided in the resources file we developed, cleaned, and provided informaton about District Grades, Funding, and Overall Passing for multiple schools within this District. This can be applied to the real world as Data Science is used for Education sectors all around the world use similar information to be analyzed and direct school funding and influence policies regarding education on all levels. On top of this we take a look at Standardized Test Scores for all schools and see that ninth grade scores have been compromised and are assigned to invesigate the influence of this anamoly regarding academic dishonesty.  

### Results: 

## How is the district summary affected?
The Original District Summary is Listed Below:
![Screen Shot 2022-02-24 at 7 55 30 PM](https://user-images.githubusercontent.com/90523595/155633640-62600f8b-8974-4e4c-975d-399e85937dbf.png

After removing the scores of ninth graders from Thomas Highschool we see the new District Summary:

![Screen Shot 2022-02-24 at 7 59 46 PM](https://user-images.githubusercontent.com/90523595/155633776-9f2f3081-425a-40cf-8468-91a4448b3c96.png)
 
- Average Math Score has changed from 79.0 to 78.9.
- Average Reading Score was not affected
- Passing Math Percentage changed from 75% to 74.8% 
- Passing Reading Percentage changed from 86% to 85.7% 
- Overall Passing Rate has changed from 65% to 64.9%

As we can see, removing the ninth grade data from Thomas highschool had negligle overall changes to the overall District Summary at whole, this is expected as this is a small facet a major district consisting of multiple schools. Further Analysis on individual school summaries are needed in order to go down the funnel of the issue at hand. 

## How is the school summary affected?
Looking at the individual school summary will give us better insight on each individual level including the issue with the ninth grade scores from Thomas High School. As we are able to create additional layers and columns regading each school. We begin by separating these schools into their respective types, both Charter and District Schools. This can help on a larger scale to see which type of schools perform better allowing us to develop follow up questions. As we move down we can take look at the size of the student body and in conjuction to this we look as Total School Budget as well as Per Student Budget. We can see there's a correlation between these parameters and the outcomes such as the Average Reading and Math Scores. Once we take these averages we can also see the percentage of passing scores for each sections as well as overall passing rate for each respectivre school. This applies to the District analysis further as we see we can see the top performing schools and the bottom performing schools. 

## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
After looking at the school summary we can take a look at Thomas High School performance specifically considering the potential of cheating or anamoly in these scores. 

- Average Math Score at Thomas High School changed from 83.42 to 83.35.
- Average Reading Score at Thomas High School changed from 83.84 to 83.89.
- Passing Math Percentage at Thomas High School greatly changed from 93.3% to 66.9%.
- Passing Reading Percentage at Thomas High School changed from 97.3% to 69.7%.
- Overall Passing Percentage at Thomas High School changed from 90.9% to 65.1%.

The Remainder of the schools remain unaffected as we're focusing on Thomas High School's scores and percentages with the removal of the compromised data. By replacing the ninth grade scores with NaN we see that Thomas High School is actually a high performing school outside of the incident. 

![Screen Shot 2022-02-24 at 9 19 29 PM](https://user-images.githubusercontent.com/90523595/155641763-3e58a0d0-651a-493c-9e30-546519ce9aa8.png)

![Screen Shot 2022-02-24 at 9 19 48 PM](https://user-images.githubusercontent.com/90523595/155641799-44bfad12-8867-4322-a56c-f9cf1deb5767.png)

![Screen Shot 2022-02-24 at 9 22 01 PM](https://user-images.githubusercontent.com/90523595/155641813-7e9d41be-05e6-4b7e-87f0-ef9a83e0be8c.png)

### How does replacing the ninth-grade scores affect the following:

## Math and reading scores by grade:
The Remainder of the schools remain unaffected as we're focusing on Thomas High School's scores and percentages with the removal of the compromised data. By replacing the ninth grade scores with NaN we see that Math and Reading scores by schools excluding Thomas High School below.

Math Before 
![PyChallenge Math](https://user-images.githubusercontent.com/90523595/155644050-c5a623ff-f634-467e-b0a4-750eca046d91.png)

Math After 
![PyChal Math](https://user-images.githubusercontent.com/90523595/155644079-77b0504d-6448-401e-8623-9e12f3f09737.png)

Reading Before
![PyCity Read](https://user-images.githubusercontent.com/90523595/155644114-416d650a-5fac-490e-aeed-4e62f89eff47.png)

Reading After
![PyChal Read](https://user-images.githubusercontent.com/90523595/155644143-5aab1184-cf5a-44bb-ad09-03deebcb4acc.png)


## Scores by school spending
All but one of the bins for spending changed and it was the $630-644 range. This changed from 56% to 63% 

Spending Before 
![PyCity Spend](https://user-images.githubusercontent.com/90523595/155644169-6957966e-b8bf-48b1-b03c-ba23d3a0af09.png)

Spending After

![PyChal Spend](https://user-images.githubusercontent.com/90523595/155645686-a3d0aeea-ab67-4570-9da2-0bf7762e5e4a.png)


## Scores by school size
The only change we see here is in the Medium Sized Range as Thomas High School is one of the respective ones. We see an increase in all percenatges of passing students due to this.

School Size Before
![PyCity Size](https://user-images.githubusercontent.com/90523595/155644352-117384b4-e22e-4489-9800-5648d3f65970.png)

School Size After
![PyChal Size](https://user-images.githubusercontent.com/90523595/155646137-c2d771fc-6f9e-4ec7-9b89-2e8f30882451.png)


## Scores by school type
As we've established the only difference we'll see is in anything related to Thomas High School, because this school is a charter and not a district we dont see any changes in district but charter schools have an overall decrease in all percentage categories.

Type Before 
![PyCity Type](https://user-images.githubusercontent.com/90523595/155644379-890fcd76-a390-4670-ab35-906f7cc8c31f.png)

Type After 
![PyChal Type](https://user-images.githubusercontent.com/90523595/155646565-b11da677-ce28-4b8e-8522-7cd19004b8f1.png)


### Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

![Summary ](https://user-images.githubusercontent.com/90523595/155646897-7fd1a6d2-f3ed-402a-b780-71c0957812ad.png)

In the end, we see that the removing the ninth grade students which was affecting the data had multiple changes across scores for both Math and Reading, Percentages related to these and the averages as well. We see that by removing Thomas' ninth grade score it better reflects the high level of performance as it's not being negatively influenced by compromised test scores. 
