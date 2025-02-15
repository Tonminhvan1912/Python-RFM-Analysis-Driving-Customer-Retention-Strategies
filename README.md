# [Python] RFM Analysis Driving Customer Retention Strategies
## **I. INTRODUCTION**

### **1. RFM ANALYSIS**

- RFM is a marketing analysis technique that stands for Recency, Frequency, and Monetary Value.
    - **Recency**: How recently a customer has made a purchase
    - **Frequency**: How often a customer makes a purchase
    - **Monetary value**: How much money a customer spends on purchases
- RFM analysis numerically ranks a customer in each of these three categories, generally on a scale of 1 to 5 (the higher the number, the better the result). The “best” customer would receive a top score in every category.
- These three RFM factors can be used to reasonably predict how likely (or unlikely) it is that a customer will do business again with a firm or, in the case of a charitable organization, make another donation.

**Reference**

[What Is Recency, Frequency, Monetary Value (RFM) in Marketing?](https://www.investopedia.com/terms/r/rfm-recency-frequency-monetary-value.asp)

### 2. **USER PROFILE DEFINITION & PROBLEM STATEMENT**

SuperStore is a global retail company with a large customer base. On the occasion of Christmas and the New Year, the Marketing Department wants to run marketing campaigns to show appreciation to customers who have supported the company over time, as well as to tap into potential customers who could become loyal clients.

However, the Marketing Department has not yet categorized this year's customers due to the large dataset, making it impossible to process manually as in previous years. Thus, they are seeking assistance from the Data Analysis Department to implement a customer segmentation classification task in order to execute tailored marketing programs for each customer group.

The Marketing Director has also proposed using the RFM model. Given the massive amount of data, they hope the Data Department can build a workflow for evaluating segmentation using Python programming.

## **II. DATA DICTIONARY**

**Table:** ecommerce retail

| **Field** | **Type of column** |
| --- | --- |
| InvoiceNo | Dimension |
| Stockcode | Dimension |
| Description | Dimension |
| Quantity | Measure |
| InvoiceDate | Measure |
| UnitPrice | Measure |
| CustomerID | Dimension |
| Country | Dimension |

**Table:** segmentation

| **Field** | **Type of column** |
| --- | --- |
| Segment | Dimension |
| RFM Score | Measure |
