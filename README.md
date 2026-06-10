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



