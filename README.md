# Data_Science
Power BI used exclusively for this analysis.

This is a detailed dashboard created with information on the salary trends across a number of countries in different fields of data science.

Here is how the final dashboard looks like.
![countplot](https://github.com/Farouk-Muda/Data_Science/blob/main/Data_science.png)

## Objectives
The primary objectives of this project are:
 - Identify and visualize trends in salary data over time to observe changes and growth.
 - Provide insights into salary variations across different levels of experience, including entry, middle, senior, and executive roles.
 - Explore average salaries across various countries to highlight regional disparities and opportunities.

## Tools and Technologies
- DAX Functions: writing DAX expressions for calculated columns, measures, and advanced data modeling.
- Power Query: data transformation, cleansing, and shaping using Power Query for ETL processes.
  
## Dataset
- Source: This dataset is obtained from kaggle [Data Science Salary](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries) It contains informatio
- Size: It consists of 606 rows and 11 columns. the columns are:
  1.work_year:	The year in which the work or data record pertains.
  2.experience_level:	The level of experience of the employee. 
  3.employment_type:	The type of employment contract.
  4.job_title	:The title or designation of the job role.
  5.salary	:The total salary amount (likely in the local currency) received for the job role.
  6.salary_currency	:The currency in which the salary is paid.
  7.salary_in_usd: The salary converted into USD for standardized comparison.
  8.employee_residence: The country or location where the employee resides while working.
  9.remote_ratio: The proportion of the job that is performed remotely.
  10.company_location: The country or location where the company is headquartered or operates.
  11.company_size: The size of the company. 

## Data Cleaning and Preparation
- Handling Abbreviated Rows: Converted abbreviated terms to full forms for better understanding in columns such as employment_type, experience_level, employee_residence, and company_size. Example:"FT" → "Full-time", "S" → "Small", "M" → "Medium".
- Missing Values: In the power query editor, I examined the valid, error and empty under the column quality.
- Data Normalization: Checked and ensured all salary values are positive integers. 


## Insights
- The average salary is **$112K**, highlighting competitive compensation trends.
- Executive roles command the highest average salaries at **$199K**, while entry-level positions average at **$62K**.
- The highest-paid roles include **Data Analytics Lead ($405K)** and **Principal Data Engineer ($328K)**.
- Emerging roles like **Machine Learning Specialist ($158K**) also highlight significant earning potential.
- Countries such as **Russia ($158K), United States ($144K)**, and **New Zealand ($125K)** have the highest average salaries.
- Lower salaries are observed in countries like **Nigeria ($22K)** and **India ($29K)**, indicating economic and regional disparities.
- **A significant majority (96.87%)** of employees are full-time, with minimal representation in part-time and freelance roles. This suggests a strong preference for stable employment in data science-related roles.
- **Fully remote roles (381 positions)** are significantly more prevalent compared to **no remote (127)** and **partially remote (99)** options. This highlights a growing trend and preference for remote work within the industry.
- A retention rate of **0.86** indicates a relatively stable workforce but also leaves room for improvement in employee satisfaction or workplace policies.


## Recommendations
- Given the consistent growth in salaries, especially in executive roles, it's crucial for companies to develop clear career progression pathways. Offering opportunities for skill advancement and leadership roles could improve employee retention and attract top talent.
- Aspiring professionals should aim to upskill, particularly in emerging areas like machine learning and data engineering, to position themselves for high-paying roles like Data Analytics Lead or Principal Data Engineer.
- Employers should consider offering competitive salaries for mid-level professionals to retain talent and prevent burnout from low compensation at these levels. Structuring a clear differentiation in salary based on experience could foster a sense of value and loyalty among staff.
- Middle-level employees might consider seeking new opportunities that provide better compensation.
- Countries like Russia and New Zealand show high salaries, while regions like Nigeria and India have lower averages. A global salary framework should be flexible enough to reflect these differences while maintaining fairness.
- Those based in lower-paying countries should look for remote or multinational opportunities that offer competitive international salaries, as roles in the United States and Russia show higher earning potentials.
- Since full-time roles dominate the market, companies should prioritize stable, long-term employment contracts for data science positions to align with industry trends. However, offering flexible work arrangements like part-time or freelance roles could appeal to a broader talent pool.
- Data professionals should consider the benefits of full-time roles, which remain the most common and offer better long-term stability. For those seeking flexibility, freelance or contract work may still present viable options despite their smaller representation.
- The significant preference for fully remote work suggests that companies should incorporate remote work options into their employee value propositions. Offering flexible or hybrid work models can help attract and retain talent, particularly in competitive fields like data science.
- Those in the data science field should seek out fully remote opportunities, which offer a larger number of roles and potential flexibility in work-life balance.
- Companies, especially smaller ones, should review their compensation structures to ensure they are competitive within their industry. Large companies often offer higher salaries, and small or medium-sized companies might need to provide additional benefits or perks to retain top talent.
- Data professionals should assess the pros and cons of working at different company sizes. While large companies offer higher salaries, smaller organizations might provide more diverse experiences and career development opportunities.
- With a retention rate of 0.86, there is room to improve employee satisfaction and workplace policies. Employers should focus on creating a more positive work environment, offering career growth, and improving employee engagement strategies.
- Job stability in data science roles is relatively high, but professionals should still be mindful of their long-term career goals. Employees should consider roles with growth opportunities to ensure ongoing professional development.
