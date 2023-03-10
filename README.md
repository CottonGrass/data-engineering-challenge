# Coding challenge
This page consists a coding challenge.

# Purpose
Aim of this test is three fold,

- evaluate your coding abilities 
- judge your technical experince
- understand how you design a solution

# How you will be judged
You will be scored on,

- coding standard, comments and style
- unit testing strategy
- overall solution design
- appropriate use of source control

# Intructions
- You may use SQLite DB or Docker based using any type of database container of your choosing for data persistance.
- You may also use AWS as long as CDK or Terraform code and instructions are included for deploying to AWS.
- Candidate should put their test results on a public code repository hosted on Github
- Once test is completed please share the Github repository URL to hiring team so they can review your work
- You are building a backend application and no UI is required, input can be provided using a configuration file or command line

# Challenge - Movie Content Collect and Store

Extract the movie titles released between 01/01/2010 - 01/01/2019 in the included data file and scrape any relevant content (i.e. Wikipedia, IMBD, etc.) to create a profile keeping the lineage and time phased infomration for how the movile profile was created/deleted. 

## Details

- Write an application to crawl any relevant content (i.e. Wikipedia, IMBD, etc.) using a crawler framework such as [Scrapy] (http://scrapy.org/) to the list of movies attached. You can use a crawl framework of your choice and build the application in Python.
- The appliction should cleanse the data to obtain only information relevant to the movie, e.g. cast, box office, title, director, plot, etc.  Use a framework such as Readability to cleanse the page of superfluous content such as advertising and html
- Store the data in any storage system of your choice, for subsequent search and retrieval.  Ensure the URL of the article is included to enable comparison to the original.
- Write an API that provides access to the content.  The user should be able to get the top 5 actors/actresses who starred in the top 5 grossing movies.

# Bonus point
If you deploy the solution as a public API using an Amazon EC2 instance.
