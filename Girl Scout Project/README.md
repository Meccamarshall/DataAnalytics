# Girl Scout Cookie Sales Analysis 🍪

Who doesn’t love Girl Scout cookies? This project dives into the world of cookie sales with a custom dataset I created and cleaned to answer 20 critical questions behind what makes these treats sell like hotcakes! Here’s a look at the journey:

## Project Files
- **Dataset**: [Cookie Sales CSV](https://github.com/Meccamarshall/DataAnalytics/blob/main/Girl%20Scout%20Project/Cookie_sales.csv)
- **SQL Analysis**: [Girl Scout Analysis SQL File](https://github.com/Meccamarshall/DataAnalytics/blob/main/Girl%20Scout%20Project/SQL)

## Data Creation and Cleanup 🧹
After generating the initial dataset, I scrubbed duplicate entries, standardized cookie names (Thin Mints vs. “ThinMints”—only one version allowed!), and ensured dates were tidy for accurate analysis.

## Cookie Insights with SQL 🔍

- **Sales Functions**: Leveraged `SUM` and `AVG` functions to reveal total and average sales, uncovering key insights like Thin Mints’ top-seller status.
- **Region and Cookie Rankings 🏆**: Using window functions, I highlighted the **Northeast** as the top region in terms of order volume, with **Thin Mints** leading in total sales.

## Key Takeaways

- 🍫 **Regional Sales Leader**: The **Southeast** had the highest total sales amount, coming in at **$115,866**.
- 🍪 **Most Popular Cookie Variety**: **Thin Mints** led by a significant margin with a total sales amount of **$84,132**.
- 📊 **Average Sales Amount per Sale**: Sales averaged **$33.32** per transaction.
- 🏪 **Top Sales Channel**: The **Booth** channel had the highest number of transactions, totaling **3,368**.
- 🌟 **Top Troop Leader**: **Lily** from Troop **9042** achieved the highest total sales amount.
