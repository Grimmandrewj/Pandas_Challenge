## Goal
- I was provided with two datasets containing data regarding schools and students.  This data included school information such as name, type, size, and budget, and student information including name, grade, and average test scores in Math and Reading.
- I was tasked with analyzing the data sets and gathering vital information with which the relevant stakeholders could make strategic decisions regarding future school budgets and priorities.  
- The results were first calculated on a district level, then sorted and summarized by school, demonstrating the highest- and lowest-performing schools by size and type (District vs. Charter)

## Method
- The total number of students, average test scores, and percent passing rates were calculated utilizing the provided datasets.  This information was summarized in a dataframe on a district level, listing the totals for the full list of fifteen schools. 
- The information was then narrowed to the school level, calucating overall budget, spending per student, average test scores, and percent passing rates per school.  
- The five highest- and five lowest-performing schools were then visualized in a dataframe organized by school type
- Average Math and Reading scores were then calculated and visualized by grade (9th through 12th) in a dataframe per school
- I then created data bins to categorize the schools by per-student spending and then by size, and additional dataframes were created which centered around the percent overall passing rate and organized by per capita spending and school size. 
- Finally, I created a dataframe which calculated the average tests scores and percentage passing rates categorized by school type (Charter vs. District)

## Summary and Results
- The final analysis can be found in the Pandas_Challenge/PyCitySchools folder in this repository
- The results demonsrate that schools with a lower per student spending budget outperformed schools with a higher per studuent budget in all metrics.  This suggests that per capita spending has less of an impact on educational outcome than other variables which are not included in these datasets:

![image](https://user-images.githubusercontent.com/120341249/214759352-63f82653-f525-417c-bc1e-12a78b9ca86d.png)

- The results also demonstrated that schools with a smaller size outperformed schools of larger sizes.  This seems to indicate that smaller class sizes results in higher student performance and that a smaller teachert-to-student ratio is beneficial:

![image](https://user-images.githubusercontent.com/120341249/214759475-57a9fc0d-f71a-4641-8379-fd248abfed9d.png)

- Finally, the results demonstrated that Charter Schools outperformed District Schools in all metrics as well.  This likely has a myriad of causes which are outside the scope of the provided datasets, but appears to be in line with the conclusions outlined above regarding budget, class size, quality of education, and other variables on student performance: 

![image](https://user-images.githubusercontent.com/120341249/214759658-439662d8-f63e-428b-88df-e8aff25218f4.png)
