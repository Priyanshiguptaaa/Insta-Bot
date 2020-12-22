# Insta-Bot
An automated web scraper built using Selenium WebDriver to parse "food" based data from Instagram and perform a case study on it

----

This is an advanced bot for scraping data that uses Selenium to parse Instagram data. 
- The use case for this project is that a friend has strted his "food blogging Instagram account". He wants to follow a lot of individuals so that he can easily get recognized, but it is a tedious task. This bot is programmed to assist him, using Selenium by performing automation.
- All specific activity functions are developed in the first section, such as following users, getting likes, getting tags, etc.
- The analysis and the case study are performed in the second part. 

It is divided into 3 use cases.
- First, he has to evaluate the behaviours of these bloggers now that his friend has followed a lot of various food bloggers. The first 10 handles are obtained from the list of Instagram handles you obtained by searching for 'food' and the top 5 with the highest number of followers are discovered. It also finds the number of posts these handles have made in the previous 3 days and uses a graph to show this data. 
- The second use case is, the friend needs a list of hashtags to use in his posts. The 5 handles acquired in the last part are opened for that and the contents of each handle's first 10 posts are scraped. It prepares a list of all the terms used in all the scraped articles and measures the frequency of each word. The hashtags most common among these bloggers are contained in a csv file with two columns: the word and its frequency are created. In the context of a pie map, the top 5 hashtags collected and the number of times these bloggers have used them in the scrapped posts are plotted. 
- The third case of usage is forming a metric to measure the percentage of average followers. The metric is called "Follower: Likes ratio" and is measured as follows: the likes of the 5 handles are derived from the top 10 entries. In order to get the average followers, the average likes for a handle are determined by the average likes received by the number of followers of the handle: the ratio of each handle is divided. To reflect the data, a bar graph is plotted.

----

## How to run?

- Clone or download the project locally

- Install Selenium 

- Install the compatible Chromedriver version in your local directory

- Open the ipynb file in Jupyter Notebook and make sure the requirements are satisfied

- Voila! Selenium magic awaits !

