# CustomerLifetimeValue
#Understanding Customer Behavior and Boosting Business Value
I had the opportunity to explore and analyze a customer dataset, aiming to gain insights into customer behavior, predict churn, and identify high-value customers. This analysis led to data-driven strategies that ultimately boosted transaction value by 15%.

#Data Exploration:

I began by loading the dataset and conducting initial data exploration:

- I imported essential libraries, including Pandas, NumPy, Matplotlib, Seaborn, and Lifetimes.
- I loaded the dataset and displayed its first few rows to get a sense of its structure.
- Basic statistics and data types of columns were examined to understand the dataset's characteristics.
- I checked for missing values to ensure data integrity.

#Implemented the Gamma-Gamma model to estimate Customer Lifetime Value (CLV):
- A Gamma-Gamma Fitter object was created and fitted to the data.
- Expected average transaction values were calculated based on the Gamma-Gamma model.
- CLV was then calculated for each customer.
- The average CLV across all customers was determined to be $1,653.

#Visualizing CLV Distribution:
To understand the distribution of CLV, I created a histogram with kernel density estimation, which revealed the distribution of customer values.

#Correlation Analysis:
I explored correlations between numerical features in the dataset using a heatmap, helping to identify potential patterns and relationships.

#Policy Type vs. CLV:
A box plot was generated to compare CLV across different policy types, providing insights into the impact of policy type on customer value.

#Pairplot:
A pairplot was created to visualize relationships between CLV and other numerical variables, such as income, monthly premium, and total claim amount.

#Churn Prediction:
To predict customer churn, I built a Random Forest Classifier model. The model was trained, evaluated, and achieved an accuracy of 0.99%. A classification report was generated to provide detailed metrics.

#High-Value Customer Identification:
I identified high-value customers based on a threshold (CLV > $5,000), revealing that 4.20% of customers are high-value. These customers contribute to 9.46% of the total revenue.

#Customer Segmentation:
Using K-Means clustering, I performed customer segmentation based on monthly premium and total claim amount. The Elbow Method was used to find the optimal number of clusters, and I segmented customers into 3 clusters.

#Segment Analysis:
Understanding these customer segments allows for tailored marketing and service strategies. For example, Segment 1, with its higher value, might benefit from premium services or personalized offerings. Segment 0 may appreciate cost-effective solutions, while Segment 2 could be targeted with budget-friendly options. This segmentation analysis enables data-driven decision-making, optimizing customer interactions and potentially increasing overall business value.
