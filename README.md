# ETL
ETL Project – Job Posting 
During this project I will be looking to answer the following questions 
1-	Companies posting on github. 
2-	If the companies posting in git hub are part of the 100 greatest places to work at 
3-	What is the competition on for companies with Data Analyst need
4-	What is the revenue of the companies as of 2020
5-	What is the salary level of the companies posting on github 
6-	What is the industry type of the companies in listed in the greatest places to work- top 100
For this project I will be using .csv and the two required methods of data pull (API call and web scraping)
1-	populating current application list in github
   	url = "https://jobs.github.com/positions.json?description=api"
2-	Job application list from .csv file in Kaggle, only for Data Analytics
    	data_df = pd.read_csv('../resources/DataAnalyst1.csv')
3-	Webscraping from greatplacetowork to get the list of companies in the top 100
  	url = 'https://www.greatplacetowork.com/best-workplaces/100-best/2021'
Steps followed
1-	Creating a dataframe for Data Analytics file 
2-	Cleaning data for view in panda. 
3-	Creating tables of data for consumption into postgres. 
4-	Creating a dataframe for the API call from github to populate the current posting of jobs (https://jobs.github.com/positions.json?description=api)
5-	Cleaning data for reporting 
6-	Creating tables of data for consumption into postgres.
7-	Creating a dataframe for the webscreping from greatplacetowork, the data from the webscrapping can be used to see if github job posting platform is being used by companies from the web.
8-	Cleaning of data for reporting 
9-	Creating tables of data for consumption into postgres.
10-	Updating a the columns of the table and creating a data frame so the column names are acceptable by postgres. see ER Diagram.png for structure of tables 
11-	Creating a table the tables in postgress and querying to see the data is accessible. ![image](https://user-images.githubusercontent.com/78058338/116282954-5b435780-a759-11eb-9bd3-71cd97b34010.png)
