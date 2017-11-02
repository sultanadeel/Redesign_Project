# Redesign_Project

Tableau Workbook Link
https://public.tableau.com/profile/muhammad.adeel3420#!/vizhome/Project_Redesign/Final_BoxPlot?publish=yes

LinkedIn Top Skills Dataset

Dataset Description:

LinkedIn top skills dataset identifies the skills which are currently, or have been, in demand based on their respective assigned ranks. The skills are ranked differently in every country and some countries prioritize a certain skill more or less as compared to other nations. The dataset also categorizes the skills on yearly basis and the period from 2014 to 2016 inclusively is used as a framework for analyzing the top skills. Moreover, LinkedIn today is the most widely used technology across the globe and is the most preferred platform to get connected, noticed and evaluated by recruiters, companies and even universities. Therefore, this dataset aims to analyze the pattern, relationships and trends in the professional skills on the basis of which skills are highly regarded and in demand versus those skills which are only focused towards a certain niche of the applicants and in demand only in a few countries.
The dataset has four columns Skill, Country, Year and Rank and has over 800 rows of records. The dataset was taken from http://www.makeovermonday.co.uk/data/  and the source of publishing the dataset is LinkedIn’s Annual Top Skills report for the year 2014, 2015 and 2016. The most important objective in analyzing this dataset is to ascertain the most crucial and emerging fact that the Data Analytics and virtualization skills are becoming higher in demand and their respective ranks are therefore increasing in a range of ranks from 1 to 25 used in the dataset.
The dataset is being analyzed in Python version 3 using Jupyter Notebook which is attached as part of this submission. Analyzing the dataset in Python indicates that there are as such no errors in the data itself and there are no missing or null values. Ascertaining the datatypes of the columns indicates that “Year” and “Rank” columns are integer type and “Skills” and “Country” columns are of object types. We also used Python’s matplotlib library to plot some visuals in Jupyter Notebook. The visuals made in Tableau are attached separately as a link to Tableau Public. As part of the requirement of Redesign Project, the critique of one of the existing visuals of the LinkedIn Top Skills Dataset is as follows:

Tableau’s Existing Visual of the Dataset:
https://public.tableau.com/en-us/s/gallery/top-linkedin-skills-2016

<img width="1050" alt="linkedindashboard 1" src="https://user-images.githubusercontent.com/31932632/32347100-d2c07464-bfcc-11e7-9cf2-c915d5883609.png">

The above Figure is the existing Tableau visual on the Dataset. It analyzes which LinkedIn skills are in demand among 14 different countries and the percentage of countries having the specific mentioned skill in their top 10 skills. The visual shows beyond doubt that Statistical Analysis and Data Mining is clearly among the top 10 skills of all the countries , proving the fact that Data Analysis is emerging as a very demanding and attractive field both in terms of recruitment as well as for prospective students pursuing educational degrees. The visual also compares the percentage difference in the mentioned skill from 2014 and it shows that almost all Data Mining, Visualization, Cloud computing and virtualization skills are constantly moving up in the ranks and more and more countries are acquiring them in order to grow and prosper economically. 
However, the visual provides a lot of information for the audience to grasp, as it mentions 38 different skills, many of which somehow overlap in terms of the field and area they refer to. Skills like Retail Operations, Renewable and sustainable energy, Mining and Commodities, Foreign Language Translation and Economics could have been excluded from the visual or could have been include in a separate category. The reason is that the title of the visual is “Which LinkedIn Skills are hot” so only those skills which are possessed by majority of the countries among their top ten skills, should have been incorporated in designing the visual. The primary objective is to show the most important and emerging skills including Data and technology related and not all of the skills. The visualization is made pretty impressively, however, some of the skills could have been excluded in making it a more concise and easy to be read by the concerned audience.
The visualization shows that on average 75% of the countries used in the dataset have technology and Data Analytics skills among their Top 10 skills, and each of those nations have witnessed a double digit growth in the mentioned skills growing in popularity and demand. Skills which have grown most rapidly from 2014 onwards are Mobile Development, Statistical Analysis & Data Mining, and User Interface Design, this shows the widespread usage of smart devices by consumers and therefore the increasing reliance of companies on the designing and development of solutions utilizing such skills. When I redesigned this dataset in Tableau, it was my endeavor to exclude those skills which are not related to our primary objective that Data Skills are increasing in demand, thereby avoiding “data vomit” and clutter in the Tableau visual and providing clarity and simplicity in persuading my audience towards the claim. This is done using Tableau Box Plot visualization which is discussed and analyzed as the final visualization in the end of this document.
Redesign Project Tableau Visuals:
 
 <img width="943" alt="project_redesign 1" src="https://user-images.githubusercontent.com/31932632/32346183-c6932be4-bfc9-11e7-9c3a-ca04f37b7790.png">
 
                                                                 Fig 1.1
Claim: Top Ranked skills are present in all the major economies as well as the emerging ones

Warrant:

The above visual Fig 1.1 is drawn in Tableau after the data wrangling step in Python. The visual analyzes the distribution of ranks and skills among the countries used in the dataset. In some countries in the boxplot, the data is skewed. The visual shows that only a few countries have a higher span of lower whisker and a large no. of data points in the 1st quartile range of the boxplot. U.S. is one country where the median of the rank is comparatively low and the data is skewed to the left indicating that the 1st quartile range consists of four different high ranked skills including Statistical Analysis & Data Mining, Cloud & Distributed Computing, and Mobile Development & User Interface Design. The above box plot also shows that only a few countries including France, U.S, UAE, China and India have a lower median between the range of ranks 5 to 10, as compared to other countries. This shows that these countries have a greater percentage of top ranked skills possessed or in pursuance by people living in those nations.

<img width="949" alt="project_redesign 2" src="https://user-images.githubusercontent.com/31932632/32346184-c6ab6178-bfc9-11e7-930f-f0d82229d113.png">
 
                                                                 Fig 1.2
                                                                 
Claim: Some technologies become popular simultaneously in all the countries, while the other Skills start emerging from the major economies and then spread across the globe

Warrant:

The Tableau visual in Fig 1.2 shows the trend of skills and their respective ranks from the 2014 to 2016. It clearly depicts the changing pattern in the rankings, however, for analysis in Tableau, we have used Average rankings. Cloud & Distribution has gained popularity as it changed from the rank of 2 in 2014 to 1 in 2016.  Despite the fact that Statistical Analysis and Data Mining is overall becoming popular and gaining demand across the globe, in terms of average ranking, the rank has gone down from 1 in 2014 to 2 in 2016. The main reason behind this analogy is that for some developed and major economies from where the top skills actually emerge, such as U.S., U.K. and the other major European countries, the top skills have already passed the most popular stage and are now in later growth stages. However, for the emerging economies like China, India and UAE, those top skills are in the introductory stages and thus among the top skills. Therefore, the average ranking trend for Statistical Analysis and Data Mining is showing that it has slightly reduced in terms of average ranking from 2014 to 2016. Some skills like Virtualization span geographical boundaries and the prevalence and usage of such skills start everywhere at the same time as most firms like Amazon provide their virtualization solutions through their cloud infrastructure. This technology is available over the web and can be bought and licensed by anyone entitled to its usage. Therefore, its average rank reflects the exact scenario in its actual trend of becoming popular and in demand as jobs requiring Virtualization skills are becoming increasing popular.

<img width="949" alt="project_redesign 2" src="https://user-images.githubusercontent.com/31932632/32346184-c6ab6178-bfc9-11e7-930f-f0d82229d113.png">
 
                                                                  Fig 1.3
                                                                  
The above Tableau visual in Fig 1.3 compares the trends of various top data skills from 2014 to 2016, it shows the country wise trend of the top LinkedIn skills. The visual is simple and easy to understand by the viewer, it clearly dominates the fact that Statistical Analysis & Data Mining and Cloud & Distributed Computing are fast gearing up as two top notch skills among all of the different countries in our dataset. China is, however, one country where the top skill such as Statistical Analysis & Data Mining has decreased in its rank from 2 in 2015 to 3 in 2016, whereas a skill like Social Media Marketing has gained popularity in China from 15 in 2015 to the rank of 7 in 2016. In U.S. more emphasis is on outsourcing software development to other countries as shown by the fact in the visual that Java Development is becoming less popular as it became no. 10 in ranking in the year 2016. However, Algorithm Design is becoming more popular in the U.S. as it a component part of the Statistical Data Analysis which is a top skill in the U.S. 
This visualization is created as one of the several visualizations towards creating the final one, however, bar chart is not an ideal representation for analyzing ranks 

<img width="1005" alt="project_redesign 3" src="https://user-images.githubusercontent.com/31932632/32346185-c6c7d434-bfc9-11e7-806c-dab4a58329fe.png">
 
                                                                  Fig 1.4

Claim: Increasing popularity in top skills is encouraging the previously less popular skills to become more demanding and rewarding

Warrant:

One of the most effective ways to visualize changes in ranks over time is to create a bump chart in Tableau as in Fig 1.3 above. This visual shows the changing trends of skill ranks from 2014 to 2016. By hovering the cursor on the circles in the Tableau worksheet, we can see the details such as the skill name and its respective average rank at that particular point in time. The visual shows that from 2014 to 2016, there was a slight variation in the top ranked skills such as Data Mining and Cloud Computing. However, the less popular skills fluctuated a lot, as we see that Pearl/Python/Ruby are becoming popular as the average rank of this skill moved from 10 in 2014 to 6 in 2016. The main reason behind this is that skills like Statistical Analysis and Data Mining and Cloud Computing do require proficiency in data science analysis tools such as Python in order to be well versed in Data Mining. Therefore, Python/Pear/Ruby are climbing up the ranks and becoming more popular over the years.

 <img width="943" alt="project_redesign 5" src="https://user-images.githubusercontent.com/31932632/32346188-c6faa436-bfc9-11e7-8b75-e7dd74aaa09e.png">
 
                                                                 Fig 1.5
                                                                 
Claim: Cloud & Statistical Data Mining skills are consistently ranked higher among all the countries as shown by the positive skewness of their respective boxplots

Warrant:

Tableau visual in Fig 1.4 shows the distribution of skills with reference to the ranks. The box plot shows that there is a greater degree of variation in the distribution of data for most of the skills. The skills which are most popular in demand in all the countries including Cloud and Distributed Computing and Statistical Analysis and Data Mining have most of the observations concentrated on the low end of the ranking scale indicating the fact that these skills occupy the top ranks . Cloud and Data Mining skills ranking distribution is skewed right and have positive skewness, their range of observations is smaller than the ranges of other skills. Pear/Python/Ruby skill set is also skewed to the right and has positive skewness, however, the range of this skillset is higher as compared to the top 2 skills Cloud and Data Mining, and this is because due to the rising popularity and growing demand of Data skills, tools like Python also increasing in demand. The positive skewness of Data Mining and Cloud skills also indicate most of the data points are spread out in the lower 1st and 2nd quartile ranges which is clearly shown in the dataset as these skills are on average ranked among the top ranked skills consistently in all the different countries in the dataset.

                                                          Final Visualization:

<img width="943" alt="project_redesign 6" src="https://user-images.githubusercontent.com/31932632/32346189-c7263466-bfc9-11e7-9e49-b683a9264cda.png">
 
Claim: Data and Technology skills are increasing in demand

Warrant:

After creating several Tableau visualizations, our final visual is as above which is created as part of this Project Redesign and creating it is an endeavor towards compare it with the existing visualization of LinkedIn Top Skills dataset available at https://public.tableau.com/en-us/s/gallery/top-linkedin-skills-2016. Our final visual is better than the one on Tableau Public because we have excluded those skills which are not crucial in analyzing and supporting our claim that Data skills are becoming popular. Our final visual is clear and easy to understand by the audience as it shows in a straightforward way, the respective trend of skills over the years using ranks as a measurement criteria for developing the boxplots which are intuitive and quite persuasive towards convincing the audience.
Skills like Data Warehousing, Data Mining, Cloud Computing, Java and Python are all showing a common trend of gaining top ranks and moving up the rank ladder from 2014 to 2016. This clearly and conspicuously satisfies our ultimate claim of this Redesign Project that “Data and Technology skills are increasing in demand.”

LinkedIn Top skills dataset has a lot of dimensions and a limited number of measures to analyze trends, relationships and patterns in skill ranking. However, boxplot is one ideal visual that we developed in Tableau for analyzing which skills are increasing in demand and which are becoming less popular.


