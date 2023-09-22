<h1 align="center">pandas-challenge</h1>


<p align="center">
<img width="800"src=https://github.com/alejandro-davila/pandas-challenge/assets/135288005/3980d61b-c6ea-4f76-a399-99c524eb2b9b)>


<h1 align="center">Background</h1>

You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

<h1 align="center">Analysis</h1>

The objective of this project is to conduct an analysis and gather data on fifteen distinct schools. Employing Pandas, I collect information such as grades, school sizes, districts, and charter status. Furthermore, I calculate the average percentage of students who passed math and reading, as well as the overall average percentage, for each school. Additionally, I create a new DataFrame that categorizes the data based on spending levels, in order to demonstrate the impact of school expenditure on average scores and passing rates. Here is a summary of the key findings from the analysis:


* District Summary
<p align="center">
<img width="1036" alt="District Summary DataFrame" src="https://github.com/alejandro-davila/pandas-challenge/assets/135288005/5813f152-9c69-4d05-b5ef-166ef83609d1">

* Schools Summary
<p align="center">
<img width="1149" alt="Schools Summary DataFrame" src="https://github.com/alejandro-davila/pandas-challenge/assets/135288005/5f953e16-4755-404e-9d81-83608b0399cb">

* Highest-Performing Schools (by % Overall Passing)
<p align="center">
<img width="1146" alt="Highest-Performing Schools by %" src="https://github.com/alejandro-davila/pandas-challenge/assets/135288005/d31d15da-6bc1-4364-84fa-4a0b9cb79281">

* Lowest-Performing Schools (by % Overall Passing)
<p align="center">
<img width="1151" alt="Bottom-Performing Schools by %" src="https://github.com/alejandro-davila/pandas-challenge/assets/135288005/73a0d038-7440-4578-b756-9cb53aef5a56">

* Math Scores by Grade
<p align="center">
<img width="436" alt="Math Scores by Grade" src="https://github.com/alejandro-davila/pandas-challenge/assets/135288005/040fd3ec-faa0-4f34-b84d-f502ac5a0d82">

* Reading Scores by Grade
<p align="center">
<img width="432" alt="Reading Scores by Grade" src="https://github.com/alejandro-davila/pandas-challenge/assets/135288005/cdd5bf54-b1ad-494c-a901-1a717a782a2a">

* Scores by School Spending
<p align="center">
<img width="1156" alt="Scores by School Spending" src="https://github.com/alejandro-davila/pandas-challenge/assets/135288005/31dccb50-2df7-4228-828d-496d3f59d54c">

* Scores by School Size
<img width="1162" alt="Scores by School Size" src="https://github.com/alejandro-davila/pandas-challenge/assets/135288005/f52a9b73-6aa0-4e15-ab52-dad7816655a1">

* Scores by School Type
<p align="center">
<img width="687" alt="Scores by School Type" src="https://github.com/alejandro-davila/pandas-challenge/assets/135288005/0109b257-4530-4dd5-9018-742a864392b2">

***

<h1 align="center">Conclusions & Comparisons</h1>

One conclusion that can be drawn is that charter schools tend to outperform district schools in terms of average scores and passing rates. The "Scores by School Type" analysis showed that, on average, charter schools had higher average math and reading scores, as well as higher percentages of students passing math, reading, and overall. This suggests that the school type can play a role in student performance, with charter schools demonstrating stronger academic outcomes.

Another conclusion that can be drawn is that smaller schools tend to have higher average scores and passing rates compared to larger schools. The "Scores by School Size" analysis indicated that small-sized schools had higher average math and reading scores, as well as higher percentages of students passing math, reading, and overall, compared to medium and large-sized schools. This suggests that smaller schools may provide a more conducive learning environment for students, leading to improved academic performance.

The breakdown of math and reading scores by grade level showed variations in performance among different grades within each school. This suggests that academic progress may not be consistent across all grade levels and emphasizes the importance of targeting interventions and support to specific grade levels where improvement is needed.

The district-wide passing rates for math and reading need improvement: The district summary highlighted the overall passing rates for math and reading across all schools in the district. The analysis indicated that the passing rates were below desirable levels, indicating the need for district-wide efforts to improve student performance and ensure more students meet the proficiency standards in math and reading.

The analysis on "Scores by School Spending" reveals that higher per student spending does not necessarily guarantee better academic performance. Schools in the lowest spending range per student (<$585) had higher average math and reading scores, as well as higher passing rates, compared to schools in higher spending ranges. This suggests that factors other than spending, such as instructional quality and resource allocation, may have a greater impact on student performance.

***

<h1 align="center">References</h1>

SOFTWARE/TOOLS/LIBRARIES

Anaconda, Jupyter Lab, Pandas, PythonData environment using Python 3.6

