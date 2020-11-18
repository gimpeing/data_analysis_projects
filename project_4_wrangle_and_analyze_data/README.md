# Project 4: Wrangle and Analyze Data

In this project, the goal is wrangle **WeRateDogs Twitter** data to create interesting and trustworthy analyses and visualizations. The Twitter archive data available in csv format is only contains very basic tweet information. Thus, I need to gather additional data, then assessing and cleaning it before analysing and come out with visalizations


## Contents:
### Part 1 :Data collection
1. **WeRateDogs** Twitter archive, `twitter_archive_enhanced.csv`
2. The tweet image predictions, i.e. what breed of dog is present in each tweet. Data store in `image_predictions.tsv`
3. Additional tweet's data, for example the `retweet count` and `favorite` ("like") count, using the `tweet ID` in the **WeRateDogs** Twitter archive, query the Twitter API for each tweet's JSON data using Python's **Tweepy** library and store each tweet's entire set of JSON data in a file, named `tweet_json.txt`.

### Part 2: Assess and Clean
After gathering each of the above pieces of data, assess them visually and programmatically for quality and tidiness issues. Detect and document at least eight (8) quality issues and two (2) tidiness issues.

### Part 3 : Analysis and Visualization
To analyze the data and come out with at least 3 insights and 1 visualization

## Conclusion:
**Summary**
- Vast majority of user post tweet via their **iphone**.
- Majority of rating is within the range of 1 - 1.5.
- No correlation observed between rating and favourites count.
- Strong positive correlation found in favorites count and retweet count, which is not surprising, as normally people retweet the post that they **like**.
- **Golden retriver** is the dog with highest tweet, whereas **Labrado retriever** has the highest favorites count.
- Most posted dog stage goes to **pupper**. 
- Relatively higher user post their tweet on Monday, and Wednesday in general get the highest mean favorites count.
- Rating increases over time, and popularity increases as favorites count increases over time.

I am not able to gather user's data that push the tweet. The JSON data obtained is with only ONE user's ID. Else, it will be interesting to find out information like average tweet per user, any correlation betwen favorites count and number of followers, number of friends of the user. Any correlation between tweet's favorites count and the user's total favorites count, correlation between tweet's favorites count and number of tweet push by the user.

**Conclusion**   
I would like to conclude by listing down what I have learnt in this project:
- Programmatically download file from html using the `Requests` library.
- Setup up Twitter's Developer account and query twitter data using `Tweepy`.
- Writing and reading Twitter JSON data.
- Data wrangling by gathering data from various sources, assessing data to detect data quality issues and data tidiness issues, and cleaning data. 

[linkedin post:](https://www.linkedin.com/pulse/weratedogs-gim-pei-ng)

```python

```
