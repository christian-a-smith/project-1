# Data Professionals' Salaries: Trends and Predictions

Team Members: Audrey Barrett, Reetu Jakhar, Lindsey Jessurun, Christian Smith

Description: The aim of our project is to examine trends within data professionals’ roles over the past three years. We’ll examine relationships between salary and company size, experience level, and title. 

Research Questions:
* What effect does company size have on data professionals’ salaries?
* On average, what salary increases can be expected with growth in experience level?
* What trends can be seen in data professionals’ salaries over the past 3 years? 2020-2023
* What is the average salary for each job title?

Datasets: 
* https://ai-jobs.net/salaries/data-analyst-salary-in-2023/

Additional References:
* https://www.zippia.com/advice/average-annual-raise/

Breakdown of Tasks:
* Data Cleanup - Audrey
* Data Analysis/Visualization
  * Question 1 - Lindsey
  * Question 2 - Audrey
  * Question 3 - Christian
  * Question 4 - Reetu
* Written Analysis - Christian
* Slide Deck - Audrey

# Analysis and Conclusion

It is no secret that the data industry is hot right now.  The job market is expanding, salaries are growing, and many of us have enrolled in this course to better our prospects within the industry. Our group utilized the AI Jobs Dataset on data professional salaries since 2020 to help inform all of our decision making on employment, when that time comes at the end of February. The dataset information included the work year the salary was paid, the experience level the position was labeled as, the employment type, the official job title, the total gross salary paid that year, the currency the salary was paid in, the primary residence of the employee for that position that year, the remote work ratio, the company country location, and the size of the company. With this data, we sought to answer four questions: 

* What effect does company size have on data professionals’ salaries?
* On average, what salary increases can be expected with growth in experience level?
* What trends can be seen in data professionals’ salaries over the past 3 years? 2020-2023
* What is the average salary for each job title?

Before answering these questions, it is important to keep in mind the limitations of our dataset. All of the entries are self reported, which could lead to inaccuracies or misleading numbers. The 2022 and 2023 entries are much more populated than the 2020 and 2021 years. Many job titles may be unique to the company, but have the same qualifications and duties as more generally accepted job titles, so some of these positions might be excluded from any comparisons or conclusions in our project.  When it comes to level of experiences, different companies may define experience levels differently, and so entries may not exactly line up. Finally, data represents the overall compensation/gross salary amount for the working year (before deductions like social security, taxes and other contributions), not including equity/stock options or similar benefits, so actual compensations may end up being higher or lower than what is in our data set.

	What effect does company size have on data professionals’ salaries? When comparing average salaries for entry level positions between small companies (less than 50 employees), medium sized companies (50-250 employees), and large companies (over 250 employees), the data reveals that, on average, company size appears to have minimal impact on salary levels for entry-level data professionals. However, differences are present within a few job titles. Engineer and management positions see increased compensations at large companies compared to small and medium companies. However, the differences remain small. For other titles, such as Analyst, Developer, and Programmer positions, salaries are comparable across different company sizes. This indicates that other factors are better indicators for salary differences, such as job category, experience level, and geographic location.

	On average, what salary increases can be expected with growth in experience level? On first glance, the average salary across experience levels for all three years increases linearly as you go up in experience level. However, to answer this question most accurately, our dataset was filtered to the four job titles with the most entries, which were Data Analyst, Data Scientist, Data Engineer, and Machine Learning Engineer.  For these four titles, salaries increased with growth in experience level, and the growth was fairly linear. This remained true even when outliers were filtered out. All 4 jobs increase at a comparable rate to each other. The main difference comes from the average starting salaries:
* Data Analysts have an average starting salary of $75,685
* Data Scientists have an average starting salary of $106,415
* Data Engineers have an average starting salary of $109,101
* Machine Learning Engineers have an average starting salary of $139,916
When breaking it down further, we can see some surprising results–data analysts and machine learning engineers both show a decrease in salary when increasing from senior level to executive level, but this seems to be either due to lack of data in the executive level, or there are simply fewer executive level positions compared to senior level positions. When looking at the average jump in salary as you rise in experience levels, the data shows that:
* Data Analysts show an average salary increase of $10,438 per jump.
* Data Scientists show an average salary increase of $24,688 per jump.
* Data Engineers show an average salary increase of $23,973 per jump.
* Machine Learning Engineers show an average salary increase of $17,011 per jump.
These numbers change significantly when removing the executive level positions. When those are removed, we see the following:
* Data Analysts show an average salary increase of $22,156 per jump.
* Data Scientists show an average salary increase of $30,568 per jump.
* Data Engineers show an average salary increase of $23,789 per jump.
* Machine Learning Engineers show an average salary increase of $27,200 per jump.
Overall, Data Scientists’ and Data Engineers’ salaries seem to grow at a faster rate than that of Data Analysts & Machine Learning Engineers, though at least part of that seems to be from incomplete data in our data set. 

	What trends can be seen in data professionals’ salaries over the past 3 years? Upon studying the dataset and calculating the average salary for each year, we can immediately see that the 2021 and 2020 average salaries for the data field must have significant outliers on the high end, as an average salary of $383,113 in 2020 and $579,841 in 2021 does not accurately represent the field, and overall the downward trend shown year to year does not tell a complete picture. As our project is focused on informing our class cohort of salary ranges post completion of the course, we also ran the averages for those positions reported as entry level. Again, without applying a filter to the data, we get a misleading picture. 2020’s average entry level salary displayed at $347,423, 2021 at $302,394, 2022 at $222,893, and 2023 at $132,983. Again showing a downward trend, and again showing numbers that are not realistic to expect for entry level positions. Moving forward, data was once again filtered out to the four job titles with the most entries, which were Data Analyst, Data Engineer, Data Scientist, and Machine Learning Engineer, and the outliers within each of these categories were filtered out, giving us the most accurate picture to draw conclusions from. All four of these job titles have shown significant average salary growth over the last 3 years, with all of them beating the 2022 national average of salary raises of 7.2%, with Machine Learning Engineer showing the fastest growth. However, the 2023 reported data shows that growth may be slowing across these four titles. More data will be needed from 2024 to confirm that trend. 

What is the average salary for each job title? Our final question in our project seeks to inform the class on the top paying titles in the field, as well as the bottom paying titles. To show this, we compiled the average salaries of all titles, across all three years within our data set, and then sorted to show the top ten and bottom ten average salaries.  Of these, the top 10 job titles by average salary are:
* Business Intelligence Data Analyst ($726,470.59)
* Data Analytics Lead ($405,000)
* Data Science Tech Lead ($375,000)
* Managing Director Data Science ($300,000)
* Head of Machine Learning ($259,000)
* AWS Data Architect ($258,000)
* Director of Data Science ($253,918)
* AI Architect ($253,600)
* Cloud Data Architect ($250,000)
* Head of Data ($248,568)
The job titles with the lowest average salary are:
* Data Operations Specialist ($55,355)
* Data Integration Specialist ($56,512)
* Machine Learning Operations Engineer ($60,000)
* Compliance Data Analyst ($60,000)
* BI Data Engineer ($60,000)
* Big Data Engineer ($70,000)
* Computer Vision Software Engineer ($75,500)
* Data Operations Analyst ($84,132)
* Data Quality Analyst ($84,370)
* Data Analytics Specialist ($95,000)
Outliers have some effect on the output but did not significantly change the final results.
After removing the outliers the average salary of the top job title changed from $1,297,222 to $726,470, and the top ten and bottom ten positions stayed the same, with the only position change being Data Quality Analyst and Data Operations Analyst switching places. These numbers on highest and lowest salaries in the field will prove useful when this cohort begins their job search.

In conclusion, our study on data professionals' salaries, utilizing the AI Jobs Dataset from 2020 to 2023, has revealed several key insights that can greatly inform decision-making for job seekers within the thriving data industry. Firstly, we found that company size has a minimal impact on data professionals' salaries, indicating a level playing field for career growth across various organizations. Second, data scientists and data engineers exhibit the most significant salary increases as they gain experience, emphasizing the importance of skill development and high demand in these roles. Third, our data indicates that data professionals' salaries are outpacing the national average, reflecting the industry's robust growth and demand. Finally, we found that the highest-paying job titles, with average salaries ranging from $375,000 - $726,471, include BI Data Analyst, Data Analytics Lead, and Data Scientist Tech Lead. This information provides valuable insights for individuals seeking opportunities in the data field, emphasizing the industry's stability and lucrative potential for those willing to invest in their skill sets and expertise.


