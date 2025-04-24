# Data Cleaning:
•	Using combined_amazon_reviews_2020_2022.json file we first converted it to csv format.
•	The dataset in csv file was further cleaned: for example, timestamp column had useful extractions done and extracted features were stored in various time columns.
•	Moreover, sentiment analysis was done and the feature was extracted based on customer’s ratings.
•	The final dataset was used in Tableau Desktop to make possible Dashboards and insights of the data.
# Loading Data:
Load the data in Tableau Public after cleaning and merging and makes possible worksheets out of our data. These worksheets are then combined together to make meaningful Dashboards that storyboards the data.
Load Dashboards.tbwx file in Tableau as it is to see it further.
# Dashboards:
 ## Title: “Customer Review Behavior Dashboard”
  ### Main Purpose:
This dashboard explores various aspects of user activity and sentiment in product reviews, enabling stakeholders to better understand reviewer behavior, sentiment trends, and how these correlate with product categories and overall review volume.
 ![Dashboard 1](https://github.com/user-attachments/assets/c4bb9f13-632d-4880-9295-a7cefab2d5f2)

 ## Business Insights:
### 1.	When do users leave reviews?
o	Insight: The "Review Time of Day" section shows when users are most likely to leave reviews. Are reviews posted more frequently during the day, night, or specific hours? This tells you if there are specific patterns in user behavior or whether users prefer to review during certain times (e.g., after purchasing or at specific hours of the day).
### 2.	How long are users’ reviews?
o	Insight: The "Word Count by Users" section reveals how verbose or concise users are in their reviews. Are certain users more detailed or do they provide short comments? This helps identify engaged vs. less-engaged users or those with higher emotional investment in the product (longer reviews often correlate with stronger feelings).
### 3.	How do users’ ratings compare to the overall product ratings?
o	Insight: The "Average Rating by Users" section displays the average rating given by each user and how this compares to the product's overall rating. It helps identify outliers, such as users who tend to rate highly or critically, and it provides insights into rating consistency across the user base.
### 4.	How does sentiment correlate with ratings and reviews?
o	Insight: By analyzing sentiment (positive, neutral, negative) against ratings, you can see how rating scores align with emotional tone. Are users giving high ratings and leaving positive reviews, or are there discrepancies between ratings and sentiment?
### 5.	Which categories have verified customers and how do they compare?
o	Insight: The "Verified Customers for Each Category" section allows you to see the distribution of verified purchase reviews per category. You can assess if verified reviews tend to skew positive or negative across categories, helping gauge product trustworthiness.
### 6.	Which users write the most reviews?
o	Insight: The "Top Reviewers by Volume" section identifies the most prolific reviewers by volume of reviews written. This tells you which users are consistently leaving feedback, allowing you to pinpoint loyal customers, advocates, or potentially spammy reviewers.
### Section 1: Review Time of Day
•	Purpose: Identify patterns in when users typically post reviews.
•	Visual Type: Bar or Line chart showing the count of reviews across hours of the day or by time.
•	Key Questions Answered:
o	When are the peak review times?
o	Are there time-based trends in user activity?
### Section 2: Word Count by Users
•	Purpose: Compare the length of reviews written by different users.
•	Visual Type: Scatter plot or Bar chart showing the average word count of reviews per user.
•	Key Questions Answered:
o	Are some users more detailed in their reviews than others?
o	Are long reviews correlated with high ratings or sentiment?
### Section 3: Average Rating by Users
•	Purpose: Compare user ratings to overall product ratings.
•	Visual Type: Scatter plot or Bar chart to show average ratings per user.
•	Key Questions Answered:
o	Are certain users consistently giving high or low ratings?
o	How do users' ratings compare to the average product rating?
### Section 4: Verified Customers for Each Category
•	Purpose: See how the verified purchase reviews are distributed across categories.
•	Visual Type: Bar or Pie chart showing verified vs. unverified reviews in different product categories.
•	Key Questions Answered:
o	Which categories have a higher percentage of verified reviews?
o	How do verified customers rate products in these categories?
### Section 5: Top Reviewers by Volume
•	Purpose: Identify the most prolific reviewers in your dataset.
•	Visual Type: Bar chart or Lollipop chart to rank users by number of reviews.
•	Key Questions Answered:
o	Which users are most active in leaving reviews?
o	What patterns can we learn from the top reviewers (e.g., rating consistency, sentiment trends)?
•	Filters: Year, Category, Verified Purchase (Yes/No)
o	Allow users to focus on specific segments and time periods.
o	Help users compare verified vs. unverified review behavior.

# Title: “Amazon Product Review Analysis”
 ##  Main Purpose:
This dashboard provides a comprehensive view of customer reviews on Amazon products. It enables stakeholders to understand customer sentiments, engagement trends, product category performance, and reviewer behaviors. The data is interactively filterable by category, sentiment, verified purchase, and year, making it a flexible tool for both macro and micro-level insights.
 
 ![Dashboard](https://github.com/user-attachments/assets/36d267be-a5e6-4a93-841b-f4ce76594192)

 ## Business Insights and Questions:
•	How many reviews were submitted in total?
•	What is the overall average rating across all products?
•	What is the distribution of sentiments (positive vs. negative)?
•	Which product categories received the highest average ratings?
•	Do verified purchases impact review trends?
•	Which users are the most active reviewers?
•	How has review volume changed over the years for each category?
### 1. Total Ratings
•	Metric Displayed: 300K
•	Insight: A large volume of customer feedback is present, indicating robust customer interaction and a valuable dataset for analysis.
### 2. Average Rating & Star Display
•	Metric Displayed: 4.1 (★★★★☆)
•	Insight: Indicates general customer satisfaction is high but not perfect; valuable for benchmarking performance.
### 3. Sentiment Percentage of Rating
•	Visual: Pie Chart (Positive: 228,891 | Negative: 51,151)
•	Insight: ~82% of reviews are positive. The sentiment analysis validates that customer perception is mostly favorable.
### 4. Top 10 Users with Count of Ratings
•	Visual: Bar Chart
•	Insight: Identifies highly engaged users. Useful for influencer/ambassador programs or detecting review spam.
### 5. Average Ratings By Category
•	Visual: Horizontal Bar Chart
•	Insight:
o	Clothing & Shoes scored the highest (4.3)
o	Electronics scored the lowest (4.0)
•	Stakeholders can investigate why certain categories perform better than others.
### 6. Categories w.r.t Verified Purchase
•	Visual: Stacked Bar
•	Insight:
o	Verified purchases outnumber non-verified.
o	All categories show a similar pattern, suggesting authenticity in review engagement.
### 7. Categories Review Count over Years
•	Visual: Line Chart
•	Insight:
o	Reviews peaked around 2021.
o	Some decline in categories like Electronics in recent years, indicating either saturation or changing customer interest.

# Title: “Review Quality & Helpfulness Analysis”
## Main Purpose:
This dashboard investigates the depth, helpfulness, and patterns in review content to understand how review quality differs across users and categories. It helps businesses uncover trends in helpfulness votes, verbosity of reviews, and patterns in verified purchase behavior.
 <img width="775" alt="Dashboard4" src="https://github.com/user-attachments/assets/d30ebff9-8075-4717-9b83-fae46b5bed8c" />

## Business Insights:
1.	What’s the relationship between review length and helpfulness?
o	Insight: The "Word Count by Helpful Vote Category" section illustrates how longer or shorter reviews correspond to different levels of helpfulness. It shows if users find detailed reviews more helpful or if brevity is appreciated in some categories.
2.	Do verified purchases correlate with more in-depth reviews?
o	Insight: The "Word Count by Verified Purchase" visualization reveals if verified buyers tend to write more detailed reviews. This helps determine if authentic purchase experience influences the quality of feedback.
3.	What keywords are commonly found in helpful reviews?
o	Insight: The "Word Cloud" highlights frequently used terms across reviews. Combined with helpful vote data, it surfaces commonly used language in high-impact reviews.

## Dashboard Sections:
### Section 1: Word Count by Helpful Vote Category
•	Purpose: Show how review length varies by helpfulness.
•	Visual Type: Bar chart or Box plot grouped by helpful_vote_category.
•	Key Questions Answered:
o	Are helpful reviews generally longer or shorter?
o	Does word count correlate with helpfulness?
### Section 2: Word Count by Verified Purchase
•	Purpose: Compare verbosity of reviews by purchase authenticity.
•	Visual Type: Histogram or Box plot showing word counts for verified vs. non-verified purchases.
•	Key Questions Answered:
o	Are verified users more likely to write in-depth reviews?
o	Do non-verified reviews skew short or detailed?
### Section 3: Word Cloud of Customer Reviews
•	Purpose: Highlight common themes in reviews.
•	Visual Type: Word Cloud.
•	Key Questions Answered:
o	What are the most used keywords in product reviews?
o	Do common words align with sentiment or helpfulness?

# Title: “Review Performance Dashboard”
## Main Purpose:
This dashboard offers a high-level overview of how product reviews are performing over time, across categories, and by verification status. It equips stakeholders with the tools to evaluate sentiment, helpfulness, and rating trends at a glance.
 <img width="804" alt="Dashboard3" src="https://github.com/user-attachments/assets/fbc7f1dc-0bf5-45d1-b17f-2513581352aa" />

## Business Insights:
1.	How customer are reviews trending over time?
o	Insight: The "Rating Trend over Time" line chart uncovers whether customer ratings are improving, declining, or staying consistent throughout months or years.
2.	Which categories receive the most helpful reviews?
o	Insight: The "Helpful Vote by Category" bar chart shows which product types tend to attract the most helpful reviews, helping businesses focus on products that drive quality feedback.
3.	What’s the overall performance of reviews?
o	Insight: KPI cards provide quick-glance metrics like average rating, total helpful votes, and sentiment score. These help executives monitor the health of customer feedback in real time.

## Dashboard Sections:
Section 1: KPI Cards (Rating, Sentiment, Helpful Votes)
•	Purpose: Summarize core review metrics.
•	Visual Type: Big Number/KPI cards.
•	Key Questions Answered:
o	What’s the overall average rating?
o	What’s the total helpful vote count?
o	Is the sentiment mostly positive or negative?
Section 2: Rating Trend Over Time
•	Purpose: Identify shifts in customer perception over time.
•	Visual Type: Line chart by year and month.
•	Key Questions Answered:
o	Are ratings improving or worsening?
o	Are there any seasonal dips or spikes?
Section 3: Helpful Vote by Category
•	Purpose: Discover where helpful reviews are concentrated.
•	Visual Type: Bar chart grouped by category.
•	Key Questions Answered:
o	Which product types receive the most helpful reviews?
o	Are helpful votes consistent across categories?

## Overall Insights & Actions
•	High customer satisfaction across most categories, especially in Clothing & Shoes.
•	Verified reviews dominate, strengthening data reliability.
•	Sentiment skew toward positive shows brand/product strength, but monitoring negative trends is still critical.
•	Identifying top users can help with loyalty programs or deeper behavioral analysis.
•	Time-based review trends can help in planning product releases and marketing campaigns.





