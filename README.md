# Marketing Campaign Analysis
![Multi-Channel-Digital-Marketing-Campaign](https://github.com/WuCandice/Marketing-Campaign-Analysis/assets/127648422/617fcf21-65ed-4d2b-8591-0801b6afebc3)

## PROJECT OVERVIEW
As a data analyst working for an advertising agency, Client A, a cosmetic company, has been implementing digital advertising across various channels such as search, display, and social media. They seek your expertise in understanding the seasonality and devising effective marketing campaign strategies for peak seasons to optimize sales.</p>
What approach would you recommend taking in this scenario?

## Analysis Process

### Step 1: Identify Key Metrics
<img width="904" alt="Screenshot 2024-01-07 at 16 03 11" src="https://github.com/WuCandice/Marketing-Campaign-Analysis/assets/127648422/0c3739e2-60b1-4233-aad9-769f4d2a8cff"></p>
To analyze seasonality, I'll focus on Sales Volume to gauge revenue fluctuations, while Web Traffic and Keyword Search Volume will provide insights into customer engagement on the website. To identify the campaign performance, I'll leverage Attributed Sales, Conversion Rate, and ROAS to measure campaign strategy efficacy and pinpoint opportunities for optimization.

### Step 2: Collect Data From Database
 <img width="856" alt="Screenshot 2024-01-07 at 16 05 58" src="https://github.com/WuCandice/Marketing-Campaign-Analysis/assets/127648422/471319fe-1c0f-4f1c-8e85-41aeaf2e2a6a"></p>
Once I know what metrics I need to use, I would collect the data from the relevant database.

### Step 3: Analyze Sales Seasonality with Visualizations
<img width="1044" alt="Screenshot 2024-01-07 at 16 07 19" src="https://github.com/WuCandice/Marketing-Campaign-Analysis/assets/127648422/169fc3c6-dff1-42c3-b4f3-a20c1ff6c3b3"></p>
I translated those datasets into powerbi and started to explore patterns. Based on these insights, dark green represents sales and yellow represents how the group of users interact with the website. I found that they had the first peak at new year, second peak at valentine’s day, third peak during summer holidays and fourth and fifth at thanksgiving and christmas. The Keyword Search Volume had the same pattern. They also had peak holiday seasons. I was able to determine that during these holiday seasons, the company had significant sales.

### Step 4 (1) : Create Measures in Power BI
<img width="947" alt="Screenshot 2024-01-07 at 16 09 11" src="https://github.com/WuCandice/Marketing-Campaign-Analysis/assets/127648422/0c373ab1-2194-4664-b52f-9adaed758a60"></p>
Since all of the datasets don't obtain those metrics, I created measures in power bi. 
And I was able to get insights about how each channel was performing. 

### Step 4 (2): Analyze Campaign Effectiveness with Visualizations
<img width="891" alt="Screenshot 2024-01-07 at 16 10 20" src="https://github.com/WuCandice/Marketing-Campaign-Analysis/assets/127648422/52bb4284-b8e0-4c09-a35d-d84e89d8aa35"></p>
The data reveals that the Search channel had the highest Attributed Sales, conversion rate, ROAS, and Net Profit, followed by Social. However, the Display channel shows a negative profit, with the lowest Conversion Rate and ROAS. Those insights indicate that we should invest more on search channels during the holiday season and optimize the display channel.

## Optimize Marketing Campaigns
### Step 5 (1): Optimize Marketing Campaigns - Budget Allocation
The client maintains a fixed budget allocation but wants to make minor adjustments based on performance </p>
For example, during the holiday season, the total budget is $100K, with $50K for search, $25K for social, and $25K for display. Given our performance analysis, we provided a strategic opportunity to optimize budget allocation for marketing campaigns. During the holiday season, we propose to reallocate the $100K budget to invest $10K more in search and remain the same for social channels, while reducing the display budget to $15K due to having the lowest performance. 

### Step 5 (2): Optimize Marketing Campaigns – Campaign Targeting
<img width="868" alt="Screenshot 2024-01-07 at 16 14 49" src="https://github.com/WuCandice/Marketing-Campaign-Analysis/assets/127648422/6b687d7f-c52b-4048-87bb-b89752e2497b"></p>
Secondly, we will consider optimizing the campaign by targeting the ideal customer. I will analyze customer demographic information such as age, gender, and region and behavioral data such as most purchased categories, purchase frequency, days since last purchase. 

### Step 5 (3): Campaign Targeting – Demographics Targeting
<img width="991" alt="Screenshot 2024-01-07 at 16 15 55" src="https://github.com/WuCandice/Marketing-Campaign-Analysis/assets/127648422/6236ddbc-95d8-404a-bb82-51451f5eb1dc"></p>
Based on the insights, I determined that the majority of our customers are females aged 35 to 39 living in New York. 

### Step 5 (4): Campaign Targeting – Behavioral Targeting
<img width="672" alt="Screenshot 2024-01-07 at 16 17 36" src="https://github.com/WuCandice/Marketing-Campaign-Analysis/assets/127648422/e6afcfde-2563-4412-bae8-c9cd8915d63b"></p>
I utilized mySQL to discover which product categories they purchased the most. Here's my query in MySQL that showed that cosmetics is the category they purchased the most, followed by hair care and eyeliner.

### Step 5 (5): Campaign Targeting – Behavioral Targeting
<img width="1000" alt="Screenshot 2024-01-07 at 16 20 31" src="https://github.com/WuCandice/Marketing-Campaign-Analysis/assets/127648422/2fd09463-326f-44cd-950c-ec82479a27b4"></p>
Additionally, I used SQL to find that the average number of transactions per customer per period is 5 times, and the average number of days since the last purchase is 43 days

## Recommendations
1. The highest points of sales, website traffic, and keyword searches were observed during the New
Year's, Valentine’s Day, summer, and holiday seasons, suggesting that there is potential to optimize
marketing strategies to enhance sales.</P>
2. Allocate a larger budget to the highly effective search and social campaigns, while also incorporating display advertising to enhance awareness and acquire new users. </P>
3. Based on historical data, our focus should be on women aged 35-39 who reside in New York. To improve customer retention, we should implement the following marketing strategies:</P>
A.Utilize email campaigns that offer incentives to encourage customers to return. By sending targeted emails with personalized incentives, we can entice customers who have not made a purchase within 43 days to engage with our brand again.</P>
B.Set up behavioral display campaigns specifically targeting customers who haven't made a purchase in the last 43 days. By displaying relevant ads to these customers based on their browsing behavior, we can increase the chances of re-engagement and improve our retention rate.</P>



