# Customer-Support-Ticket-Analysis-SQL
SQL-based customer support analytics project analyzing 8,470 tickets to uncover customer satisfaction trends, support workload distribution, and product performance insights.
# Customer Support Ticket Analysis (SQL)

## Project Overview

This SQL project analyzes 8,470 customer support tickets to evaluate operational performance, customer satisfaction, support demand, and product-related support trends. The analysis focuses on identifying key drivers of customer experience and uncovering actionable business insights that can support service improvement initiatives.

## Tools Used

* SQLite
* DB Browser for SQLite
* SQL

## Dataset

The dataset contains 8,470 customer support tickets with information related to:

* Ticket Status
* Ticket Priority
* Ticket Channel
* Ticket Type
* Product Purchased
* Customer Satisfaction Rating

## Business Questions

1. What is the distribution of support tickets by status?
2. How are tickets distributed across priority levels?
3. Which support channels generate the most ticket volume?
4. What are the most common support request types?
5. What is the overall customer satisfaction level?
6. Which ticket types produce the highest and lowest satisfaction scores?
7. Which products generate the most support tickets?
8. Which products have the lowest customer satisfaction ratings?

## Key Findings

### Ticket Status

* Pending Customer Response: 2,881 tickets
* Open: 2,819 tickets
* Closed: 2,769 tickets

### Ticket Priority

Support demand was evenly distributed across Low, Medium, High, and Critical priorities.

### Ticket Channels

Email, Phone, Chat, and Social Media each contributed approximately 25% of total support volume.

### Customer Satisfaction

* Average Customer Satisfaction Score: 2.99 / 5

### Ticket Type Satisfaction

* Highest Satisfaction: Cancellation Requests (3.03)
* Highest Satisfaction: Billing Inquiries (3.03)
* Lowest Satisfaction: Refund Requests (2.93)

### Product Analysis

Products generating both high support demand and below-average customer satisfaction included:

* Sony Xperia
* LG OLED
* Apple AirPods

These products represent the strongest candidates for root-cause analysis and service improvement efforts.

## Business Recommendations

* Investigate recurring issues associated with Sony Xperia, LG OLED, and Apple AirPods.
* Improve refund processing workflows to address lower customer satisfaction scores.
* Continue balanced staffing across support channels due to evenly distributed workload.
* Develop targeted support strategies for products associated with elevated ticket volume and lower customer satisfaction.

## Skills Demonstrated

* SQL Queries
* Data Cleaning
* Aggregations
* GROUP BY
* ORDER BY
* HAVING
* Business Intelligence
* Customer Experience Analytics
* Operational Reporting
* Insight Generation
