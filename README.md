# Rental-Analysis-for-Marketing
## link to the blog post:
https://www.linkedin.com/pulse/marketing-apartment-rental-replacement-using-data-science-zixing-wang/?trackingId=2va6hWqlSmmCJ4PRRolI5A%3D%3D
## Motivation
In order to better market my apartment , I used Python to collect and analyze all communication history with interested people inquiring about the apartment and optimized my apartment advertisement. 
## Questions to Answer
1. What is the most effective platform to post my apartment advertisement?
2. What is the best time to post my advertisement?
3. How can I tell if a person will end up visiting my apartment or not based on the message?

## Instructions: 

I strongly encourage you to read the files in the following order for the best understanding of the project

1. The blogpost(link shown above) or the project report (Market for Lease Replacement using Data Science.docx)
2. Craigslist Email Data Cleanup.ipynb
3. Facebook Message Data Cleanup.ipynb
4. Data Wraggling.ipynb
5. Data Visualization.ipynb

## Strategy: 

CRISP-DM Process 
### Business Understanding: 

I researched the menthods to market rental properties as a non-professional. And later related my findings to the rental market fluctuation. 

### Data Understanding:

I used excel files, JSON files and mbox files and located the information I need.

### Data Preparation: 

I cleaned the data and merged them into one master dataframe

### Modeling and Evaluation

I did not use machine learning. But instead I used descriptive statistics to help me understand the marketing response. 

### Deployment

Proper action has been planned base on the data

## Data: 
*	Craigslist: email and text message
  	
    Format: mbox for email, excel for text messages
    
*	Nextdoor: Nextdoor inbox

  	Format: excel
    
*	Facebook: Facebook messages

  	Format: JSON file for each conversation
    
*	sublet.com: sublet.com inbox

   Format: excel
   
## Files:

Due to the large size of the program. I splitted the entire CRISP process into multiple files
* *Craigslist Email Data Cleanup.ipynb*: processed mbox file and extracted data I need
*. *Facebook Message Data Cleanup.ipynb*: processed a series of JSON files and extracted data I need
* *Data Wraggling.ipynb*: combine all data files together and performed data cleaning
* *Data Visualization.ipynb*: descriptive statistic analysis of the collected data 
* *Market for Lease Replacement using Data Science.docx*: detailed report on the project

## Conclusion and Future Action:
In conclusion, I extracted information from sources like Gmail and Facebook. Cleaned the data and visualized them to find out that 
1. Facebook is the advertising platform that is the worthiest of my time and effort. 
2. The advertisements are better posted on Saturdays and Craigslist advertisements should be renewed in the morning and Facebook advertisements should be renewed at around noon. 
3. People more likely to rent the place will give more positive and affirmative words in the conversation. 
4. And information about the apartment (room and bath numbers, etc) and lease are what people are concerned about the most when looking for the apartment. 
