# Analysis of Data Science Jobs between 2020 and 2023

## Introduction

This project explores the attributes surrounding Data Science jobs between 2020 and 2023. The insights generated from this dataset’s exploration will be valuable to professionals seeking to transition into the data science field, as well as those already in the field, looking to widen their expertise or transform within the field.

## Datasets

The primary analysis will be conducted using a dataset from Kaggle, which contains data on data science jobs between 2020 and 2023. This is a singular, structured dataset that contains 3,755 rows and 11 columns consisting of key variables related to jobs in the data science field.

A complementary analysis will focus on the skills variable from a separate dataset, also retrieved from Kaggle. The dataset contains 12,217 rows that each contain skills required for data science related jobs posted on LinkedIn in January 2024.

Both datasets are publicly available on Kaggle, and we have permission to use them, as Kaggle is an open data source.

## Guiding Questions

**1**. What has been the growth rate in Data Science jobs in the past four years? 

**2**. What is the overall distribution of salaries in the dataset, as well as the salary distribution across categorical variables, such as experience level, company size, remote status?

**3**. What has been the trend over time of remote jobs in the Data Science field? 

**4**. What has the distribution of Data Science job titles been over the years, as well as the distribution per experience level and remote status?

**5**. What are the in demand skills in the Data Science field?

**6**. What are the proportions of employment types in the Data Science field?

## Methodology 
In conducting the analysis, the following approaches were taken:
  * **Data Cleaning and Preprocessing** \- This involved loading and inspecting each dataset independently. Data was cleaned and extracted using regex, among other processes. Irrelevant columns were also removed. Job titles were also grouped into more general job titles.
  * **Exploratory Data Analysis** \- This involved generating statistical summaries on the numerical data. Outlier detection was also carried out.
  * **Data Visualization** \- Visualizations such as line plots, bar charts, clustered bar charts, violin plots, box plots, pie charts and heat maps were plotted to aid the data analysis.
  *  **Hypothesis Testing** \- T-Tests were run between the salaries of categories within the categorical variables, while chi-squared tests would be performed on some categorical variables.
  *  **Reporting and Insights** \- This involved the preparation of a report that displayed key trends in the growth of the data science field as well as the salaries for jobs in this field.

## Insights Gained
The following insights were gained:
 **Growth of Data Science Jobs**
- The number of data science jobs has grown significantly over the past four years, with a notable boom between 2021 and 2022.
- Data Engineering roles have become more prevalent, surpassing Data Scientists as the most common role in 2023.

**Salary Insights**
- Most salaries range between 150,000 and 300,000, with a few roles exceeding 400,000.
- Machine Learning Engineers and Data Architects have the highest median salaries, while Data Analysts earn the least.
- Salaries increase with experience, with Executives earning the most of around 300,000 and above, while entry level professionals earn the least of around 140,000 and below.
- Jobs in the US generally pay higher salaries than jobs in Canada, with wider salary ranges and more high-paying roles.
- Larger companies offer higher salaries compared to medium and small companies.

**Experience Level Trends**
- Senior roles have the highest proportion of jobs in the job market, making up over 70% of the dataset.
- Mid level roles are more common among Data Analysts, while Executive roles are mostly filled by Data Scientists and Data Engineers.
- Entry level positions are relatively scarce, with Machine Learning Engineers and Data Architects rarely having them.

**Remote Work Trends**
- Fully remote roles were dominant between 2020 and 2022, likely due to the COvid-19 pandemic.
- In-person roles surged in 2023, suggesting companies are shifting back to pre-pandemic work arrangements.
- Hybrid roles have consistently remained low throughout the years.

**Relevant Skills**
- Python and SQL are the most in-demand skills, followed by Data Analysis, Machine Learning, and Communication.
- Some other technical skills such as AWS, R and visualization tools, such as Tableau, Power BI are also highly valued.
- Soft skills like Communication, Problem-Solving, and Project Management are also emphasized in job descriptions, and are equally important in the data science field.

**Statistical Relationships**
- There is no statistical relationship between employment type and job title, employment type and company location, or experience level and company location. All other categorical variables are statistically dependent, meaning they influence one another.

**Final Thoughts**
- The Data Science job market is growing, with increasing demand for skilled professionals, rising salaries, a shift back to in-person work, etc. Professionals seeking higher salaries may target US-based jobs and larger companies. In addition, professionals should ensure they continuously develop high-demand skills like Python, SQL, Machine Learning, Communication, etc., to ensure they stay relevant in the field.
- The high demand for senior expertise should serve as motivation rather than discouragement. Internships and networking opportunities can be valuable entry points into the field.
- This analysis provides valuable insights for data science professionals, job seekers, employers, etc., looking to understand trends in the Data Science industry.

## License
This project is licensed under the terms of the MIT license.