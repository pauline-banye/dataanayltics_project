# Data-Analytics-Course-Project
For the project, you are provided with a dataset to analyze using the skills learned in the course.

When working on the project, you are encouraged to consider the different stages of the data life cycle and the importance of using the right tools to efficiently answer as many of the project questions as you can.

Feel free to be creative in how you present your findings to answer each project question. At the very minimum, you are expected to create a dashboard in Tableau Public (https://public.tableau.com/en-us/s/) with at least 3 different visualizations to help answer some of the project questions.

# Dataset description:
The dataset contains the daily number of webpage visits for several Wikipedia webpages. (if you are not familiar with Wikipedia, you can check it out here https://en.wikipedia.org/wiki/Main_Page). The dataset includes daily page visit counts for 1,500 Wikipedia pages starting on 2016-01-01 until 2016-12-31.

Dataset source: Kaggle.com

# Project Questions:
what were some of the most trending search topics on Wikipedia on the following days? Using the provided dataset, can you show some evidence to support your answer? a- New year's day b- November 8, 2016

Which page experienced the biggest decline in page visits during 2016?

Which page experienced the biggest increase in page visits during 2016?

Wikipedia pages could be written in several languages. How many languages are represented in this dataset? What proportion of the pages does each language represent?

Hint: One may infer which language a page is written in based on the page name e.g. Special:Search_fr.wikipedia.org_all-access_all-agents is written in French and Special:Book_en.wikipedia.org_all-access_spider is written in English.
Based on the provided dataset, which day(s) of the week is/are the most popular for visiting wikipedia?

Based on the provided dataset, which day(s) of the week is/are the least popular for visiting wikipedia?

Based on the dataset provided, which device type is used more frequently for visiting wikipedia i.e. desktop or mobile devices?

# steps to flatten the data
flatten data: py flatten.py
read with jupyter notebook vscode
cleaning - fillunknowns &  drop duplicates
create sqlite database
