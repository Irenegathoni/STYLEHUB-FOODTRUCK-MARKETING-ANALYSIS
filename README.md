# Marketing Analytics: StyleHub Fashion Truck Profitability Analysis

## Project Overview

This project analyzes customer profitability across multiple mobile fashion truck locations to identify which locations generate the most valuable customers. The analysis goes beyond simple revenue metrics to create a comprehensive profitability score that balances immediate sales, customer spending behavior, and loyalty patterns.

## Business Context

**Company:** StyleHub - Mobile fashion retail targeting customers aged 18–35  
**Challenge:** Limited marketing budgets and rising competition require strategic focus on the most profitable locations  
**Goal:** Identify which truck locations bring in the most valuable customers for optimal resource allocation

## Business Question

**Primary Question:**  
Which truck location generates the most profitable customers?

**Supporting Questions:**
- Which location has the highest average order value?
- Where do we see the most customer loyalty (repeat purchases)?
- How should we allocate marketing resources across locations?

## Dataset Structure

| Column             | Description                                 |
|--------------------|---------------------------------------------|
| date               | Transaction date                            |
| truck_location     | Physical location of the truck              |
| marketing_channel  | Marketing channel driving traffic           |
| customers          | Number of customers served per day          |
| avg_order_value    | Average order value per customer            |
| total_sales        | Total sales made per day                    |
| repeat_customers   | Count of customers who returned             |
| weather            | Weather condition on transaction date       |

## Methodology

### Profitability Score Calculation
Profitability_Score = (total_sales / customers) + (avg_order_value * 0.4) + (repeat_customers / customers)

**Score Components:**
- **Revenue per customer:** Immediate value generated
- **Average order value (weighted 0.4):** Customer spending behavior
- **Repeat customer ratio:** Loyalty and long-term value indicator

### Analysis Approach

1. Data Exploration: Identify trends across locations, channels, and time
2. Profitability Scoring: Generate a score for each location
3. Comparative Analysis: Evaluate locations across multiple metrics
4. Business Insights: Translate data into strategic recommendations

## Key Findings

### Location Performance Summary

| Metric                     | Top Performer | Value              |
|----------------------------|----------------|---------------------|
| Overall Profitability      | Suburbia       | 8.94 score          |
| Highest Average Order Value| Suburbia       | $12.65              |
| Most Loyal Customers       | Midtown        | Highest repeat rate |
| Total Revenue              | Downtown       | Highest volume      |
| Revenue per Customer       | Suburbia       | Highest efficiency  |

### Strategic Insights

**Suburbia – Premium Customer Hub:**
- Highest profitability score
- Highest AOV indicates affluent customers
- Lower volume but high per-customer value

**Midtown – Loyalty Champion:**
- Strongest repeat customer base
- Ideal for loyalty-focused initiatives

**Downtown – Volume Leader:**
- Highest total sales and traffic
- Opportunity to optimize pricing and conversion

## Business Recommendations

### Immediate Actions

1. Focus marketing budget on Suburbia for high-value customer acquisition.
2. Launch loyalty programs in Midtown to reward return customers.
3. Review pricing and efficiency in Downtown to improve profitability.

### Strategic Considerations

- Shift budget allocation to high-profit locations
- Customize product offerings by location
- Optimize marketing channels per truck region

## Tools and Technologies

- **Python 3.x**
- **Jupyter Notebook**
- **Libraries:**
  - pandas
  - matplotlib
  - seaborn
  - numpy


## Key Learnings

**Analytical Insights:**
- High total revenue does not mean high customer profitability
- Composite scoring adds more clarity than using revenue alone
- Location-specific tactics are more effective than generic strategies

**Business Intelligence:**
- Loyal customers drive long-term profit
- Each location needs custom analysis
- Strategic allocation leads to better ROI

## Future Analysis Opportunities

- Explore seasonal changes in location performance
- Analyze marketing channel performance per location
- Segment customers based on demographics and behavior
- Use predictive models for inventory and staffing optimization




A composite profitability score was created to evaluate customer value:

