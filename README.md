# NullClass-Power-Bi-Project


### Task 1: Highest Engagement Rate Tweets (Top 10%)
**Steps:**
1. **DAX Measures:**
   - Develop a measure for word count]
   - Filter for weekdays and time between 1 PM and 4 PM through slicers or calculated columns
   - Filter tweets with `Likes > 50`
2. **Visuals:**
   - **Stacked Bar Chart**: Tweets sorted in descending order by engagement rate. Top 10% 
   - **Donut Chart**: Number of likes more than 50
   - **Pie Chart**: Word count less than 30 
   - **Line Chart**: Posting time from 1 pm to 4 pm on weekdays

### Task 2: Top 10 Tweets by Sum of Retweets and Likes
**Steps:**

1. DAX Measures:
   - Sum of retweets and likes: `TotalEngagement = [Likes] + [Retweets]`
   - Filters: Even-numbered impressions, odd-numbered dates.
   - Time filter: 3 PM-6 PM.
2. **Images:**
   - **Bar Chart**: Top 10 tweets with user profile.
   - **Pie Chart**: Tweets uploaded during weekends.
   - **Donut Chart**: Impressions even-numbered.
***Clustered Column Chart***: Tweets with a word count of < 30 and odd-numbered dates.

### Task 3: Line Chart of Average Engagement Rate Trend
**Steps:**
1. **DAX Measures:** 
   - Average engagement rate per month.
   - Filters: between 3 PM-6 PM, even engagement rates, odd-numbered dates
2. **Visuals:** 
   - ***Line Chart***: Trend of average engagement rate by month.
   - **Clustered Column Chart**: Tweets with media, without media
   - **Donut Chart**: Engagement rate is even, date is odd


