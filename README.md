# Introduction
Storytelling with PowerBi by [Paul](https://twitter.com/PauloDaguvnor?s=20&t=vZLxXH6n6up00sT6dPJaLw) was taught on day 15 and 16 of the NG30daysoflearning.
This is to show what I learnt in this class.

# Problem Statement
Theoyinbooke and friends organised a training they tagged [#NG30daysoflearning](https://twitter.com/TheOyinbooke/status/1523694387770789888?s=20&t=vZLxXH6n6up00sT6dPJaLw) their motive was to help the Nigerian students currently affected by the ongoing ASUU strike gain technical skills in Data Analytics. Towards the end of the programme, Theoyinbooke reached out to me and said he wants to know if the training was successful or not, and if it will be advisable to hold more training like that in the future.

After taking a look at the [dataset](https://aka.ms/30DLDATGitHubRepo) made available. One question I want to answer is "How successful was the programme and how can it be improved?"

# Data Sourcing
[Data](https://github.com/theoyinbooke/30Days-of-Learning-Data-Analysis-Using-Power-BI-for-Students/tree/main/Twitter%20Data%20Web%20Scrape) was provided in two forms
- [Jupyter notebook python file](https://github.com/theoyinbooke/30Days-of-Learning-Data-Analysis-Using-Power-BI-for-Students/blob/main/Twitter%20Data%20Web%20Scrape/30DLTweetsScrape.ipynb) 
- [csv file](https://github.com/theoyinbooke/30Days-of-Learning-Data-Analysis-Using-Power-BI-for-Students/blob/main/Twitter%20Data%20Web%20Scrape/30DLTweets.csv)

I made use of the cvs format and extracted the data from the web into Power BI.

# Data Transformation
Data cleaning was performed in Power Qwery,
- There was a column from the raw data that contained both data and time, this was split into 2 separate columns.
- Date column was transformed into Day Number, and the first 3 letters were extracted after which it was sorted by Day Number.
- Time column was transformed into start hours.
- Data types were checked to see if they were accurate.
- Locations column had 71% validity, due to the limitations of the data gotten.

# Data Visualization
[Interact with dashboard here]()

#

# My Thought Process
I am sure you will be wondering why these questions, what insight you want to show, what you want to call our attention to, and many more. This is what I was thinking while asking this question,
### What day of the week were participants most active? 
- I am interested in finding out what was happening on this particular day, what makes it different from every other day, is there something the organisers are doing on this said day that they aren't doing on other days? This dataset can't give this answers but it has opened a new light the organisers can carry out a survey to look at.
### What time of the day were participants most active? 
- I want to find out why engagement is higher at this time, are the partcipants busy with other things before then, can there be a way to adjust the programme to fit this time, or are the organisers doing something at this time we have to take note of 
### Who are the most active participants ?
- My major question here is, Is the active participants the actual learners or the organisers? 
### What were the top most liked and retweeted post?
- To know if there is a pattern among the top posts the organisers should take note of, they can use this to make an informed decision what type of post they will be putting out
### what were the top locations of our participants?
- I asked this just incase the organisers want to have a data hang out or create a physical hub.



