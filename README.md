# Wrangle-and-Analyze-Data

Project Details
Tasks in this project are as follows:

•	Data wrangling, which consists of:
o	Gathering data 
o	Assessing data
o	Cleaning data

•	Storing, analyzing, and visualizing wrangled data

•	Reporting on data wrangling efforts and  data analyses and visualizations


Gathering Data for this Project

Gather each of the three pieces of data as described below in a Jupyter Notebook titled wrangle_act.ipynb:
1.	The WeRateDogs Twitter archive. Provided by Udacity  and downloaded this file manually 
2.	The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network. This file (image_predictions.tsv) is hosted on Udacity's servers and was downloaded programmatically using the Requests library and provided URL. 
3.	Each tweet's retweet count and favorite ("like") count at minimum, and any additional data found interesting. Using the tweet IDs in the WeRateDogs Twitter archive, query the Twitter API for each tweet's JSON data using Python's Tweepy library and store each tweet's entire set of JSON data in a file called tweet_json.txt file. Each tweet's JSON data should be written to its own line. Then this .txt file is read line by line into a pandas DataFrame with tweet ID, retweet count, and favorite count. 


Assessing Data for this Project

After gathering each of the above pieces of data, assess them visually and programmatically for quality and tidiness issues. Detect and document quality issues and tidiness issues in wrangle_act.ipynb Jupyter Notebook. 


Cleaning Data for this Project

Clean each of the issues that were documented while assessing. Perform this cleaning in wrangle_act.ipynb as well. The result is a high quality and tidy master pandas DataFrames






Files contained in this repository:
1.	wrangle_act.ipynb: code for gathering, assessing, cleaning, analyzing, and visualizing data
2.	wrangle_report.pdf: documentation for data wrangling steps: gather, assess, and clean
3.	act_report.pdfor act_report.html: documentation of analysis and insights into final data
4.	twitter_archive_enhanced.csv: file as given by Udacity
5.	image_predictions.tsv: file downloaded programmatically
6.	tweet_json.txt: file constructed via API
7.	twitter_archive_master.csv: combined and cleaned data twitter_archive_enhanced.tsv and tweet_json.txt
8.	image_prediction_master.csv: combined and cleaned data of image_predictions.tsv and twitter_archive_enhanced.tsv
