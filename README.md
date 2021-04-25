# Remote-Job-Market-COVID
This project investigates the remote job market from scraped data from indeed.com in the period before February 15th 2021.

### Research Questions
- Where are the companies that require remote employees located?
- What are the posting rates for remote positions by companies from these locations?
- What are the most requested remote positions in all locations?
- What are the most requested qualifications for remote positions in all locations?
- How are the salaries distributed?
- What are the characteristics of lower- and higher-pay jobs?

### Conclusions
- Staffing companies invest a lot on indeed.com. Duplicates accounted for ~70% of the scraped data and they were mostly from staffing firms.
- The top postings are from these locations in this order: NYC, Chicago, Atlanta, Los Angeles, and Washington, DC.
- Middle of the week is when most of the jobs are posted.
- The majority of the posted remote jobs don’t have a specified location.
- Most of the posted jobs are sales, marketing and business development jobs.
- Most of the required qualifications are 1 year experience and bachelor.
- The median estimated salary for the remote jobs is $60,000 a year.
- More salaries are offered to federal employees, candidates with sales experience, real estate experience and above 2 years experience.
- Less salaries are offered to customer service, representatives, specialist, social media and part-time jobs.

The [Power Point slides](https://github.com/iba13001/Remote-Job-Market/blob/main/RemoteJobMarketCOVID.pptx) have a summary of the research outcome

### Future Work
More work can be done to classify the jobs using unsupervised learning. Also, a machine learning model can be built to predict the salary from job description.

### Data Description
##### The data were scraped using Scrapy within Python.
Company: company name <br>
Date: the time a job posted <br>
JobLoc: job location <br>
JobTitls: the title of the job <br>
Qualifications: the required qualifications <br>
Salary: the salary <br>
Text: the job description <br>
