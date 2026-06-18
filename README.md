# EDA_Flipkart_Product_Data
### Objective

Identify which product categories generate the highest sales volume on Flipkart.

### Method

Grouped products by category and calculated the total units sold for each category using Pandas.

### Findings

* Toys recorded the highest sales volume with approximately 25.6 million units sold.
* Home & Kitchen recorded the lowest sales volume with approximately 24.7 million units sold.
* Sales volume remained relatively balanced across all categories, with less than a 4% difference between the highest and lowest performing categories.

### Additional Investigation

To understand the reasons behind category performance differences, average price, rating, discount percentage, and delivery time were compared across categories.

### Key Insight

The analysis revealed minimal variation in average price, ratings, discount percentages, and delivery times across categories. Therefore, these factors alone do not sufficiently explain the observed differences in sales volume.

### Business Implication

Further analysis is required to evaluate additional factors such as seller quality, stock availability, brand distribution, product assortment, and customer demand patterns.
---
### Analysis 2: Impact of Discount Percentage on Sales Volume

#### Objective

Evaluate whether higher discount percentages lead to increased product sales.

#### Method

Performed Pearson correlation analysis between discount percentage and units sold.

#### Result

Correlation coefficient = -0.000088

#### Interpretation

The correlation coefficient is extremely close to zero, indicating no meaningful linear relationship between discount percentage and sales volume.

#### Key Insight

Products offering larger discounts did not consistently achieve higher sales volumes. Based on this dataset, discount percentage does not appear to be a primary driver of sales performance.

#### Business Implication

Decision-makers should investigate other factors such as product category, brand reputation, customer reviews, inventory availability, and seller performance rather than relying solely on discount strategies.
---

### Analysis 3: Revenue-Based Category Performance

#### Objective

Evaluate category performance using revenue instead of sales volume.

#### Findings

Revenue rankings differed slightly from unit-sales rankings. Beauty and Fashion categories moved higher when evaluated on revenue, despite not being among the highest categories in terms of units sold.

#### Key Insight

This suggests that certain categories generate higher revenue per unit sold, indicating stronger monetization potential. Revenue-based analysis provides a more accurate measure of business value than sales volume alone.

#### Business Implication

Decision-makers should evaluate both sales volume and revenue when allocating marketing budgets, inventory resources, and category expansion efforts.

---

### Revenue Contribution by Price Segment

To understand how products from different price ranges contribute to overall business performance, the products were divided into four segments: Budget, Mid-Range, Premium, and Luxury.

The analysis showed that the Luxury segment generated the highest revenue, followed by Premium products. Although lower-priced products are generally more accessible to customers, their contribution to total revenue was significantly lower compared to high-priced products.

This indicates that product value plays a major role in revenue generation. Even when sales volume is similar, higher-priced products contribute substantially more to overall business performance.

From a business perspective, this suggests that maintaining a strong portfolio of premium and luxury products can have a significant impact on revenue growth while budget products may help attract a larger customer base.

---

### Product Price Distribution Across Categories

A box plot was used to compare the distribution of product prices across different categories.

The median prices across all categories were found to be very similar. In addition, the spread of prices and the overall range showed little variation between categories.

This suggests that the dataset contains a relatively balanced price distribution across product categories. No category demonstrated a significantly higher or lower pricing structure compared to others.

The analysis indicates that category-level differences in revenue and sales are unlikely to be driven solely by product pricing.

---

Impact of Product Ratings on Sales Performance

To understand whether highly rated products achieve better sales performance, products were grouped based on their ratings and the average units sold were calculated for each rating level.

The results showed that average sales remained relatively consistent across all rating levels, generally ranging between 2,450 and 2,570 units sold. No clear upward or downward trend was observed as ratings increased.

This suggests that product ratings alone were not a major factor influencing sales volume within the dataset. Products with higher ratings did not consistently outperform lower-rated products in terms of units sold.

From a business perspective, this indicates that factors beyond customer ratings, such as pricing, product availability, brand recognition, or marketing efforts, may play a larger role in driving sales performance.

---

Analysis: Review Count vs Sales Performance
Objective

The purpose of this analysis was to examine whether products with a higher number of customer reviews tend to achieve greater sales volumes.

Method

A scatter plot was created using review count and units sold for all products in the dataset. Each point represents an individual product listing.

Findings

The visualization did not reveal a clear relationship between review count and sales volume. Products with both low and high review counts were distributed across the full range of sales values. No noticeable upward or downward trend was observed.

Key Insight

The number of customer reviews does not appear to be a significant factor influencing sales performance within this dataset. Products with a large number of reviews did not consistently achieve higher sales compared to products with fewer reviews.

Business Implication

Based on the available data, review count alone may not be a reliable indicator of product success. Other factors such as product positioning, pricing strategy, brand value, marketing efforts, or inventory availability may have a greater impact on sales performance.

---

Impact of Return Policy on Sales Performance
Objective

The objective of this analysis was to examine whether products with longer return policies achieve higher sales volumes compared to products with shorter or no return periods.

Method

Products were grouped based on their return policy duration, and the average units sold were calculated for each return policy category. A line chart was used to compare sales performance across different return periods.

Findings

The analysis showed only minor differences in average units sold across return policy durations. Products with a 10-day return policy recorded the highest average sales, while products with a 30-day return policy recorded the lowest. However, the overall variation between categories was very small.

Key Insight

The results suggest that return policy duration does not have a significant impact on sales performance within this dataset. Products offering longer return periods did not consistently achieve higher sales volumes than products with shorter return policies.

Business Implication

While flexible return policies may improve customer confidence and satisfaction, this analysis indicates that return policy duration alone is unlikely to be a major driver of product sales. Businesses should consider other factors such as product quality, pricing strategy, brand reputation, and marketing efforts when attempting to increase sales performance.
