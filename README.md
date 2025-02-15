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

## **II. EXPLORATORY DATA ANALYSIS**

In this section, I outline 5 steps for EDA:

1. Descriptive statistics
2. Check data types
3. Handle incorrect values
4. Handle missing values
5. Handle duplicates

Please check the attached code file for more details.

## **III. DATA PROCESSING**

![Image](https://github.com/user-attachments/assets/670a60be-833f-4a5d-9f75-1413d313dd92)

![Image](https://github.com/user-attachments/assets/86da71f1-16c3-475d-838a-12bf887a4970)

![Image](https://github.com/user-attachments/assets/546ef703-4280-4bc0-9fbf-1b1e3f1af61d)

![Image](https://github.com/user-attachments/assets/ffceeb97-3082-4951-8854-1681ef274df9)

After completing the calculation of the Recency - Frequency - Monetary variables, we will detect outliers and process them to ensure more accurate data.

![Image](https://github.com/user-attachments/assets/05bd8a2a-6af5-4560-90a1-4c6b857859fe)

![Image](https://github.com/user-attachments/assets/f0e591a8-b583-416a-ae50-195d25c709f8)

![Image](https://github.com/user-attachments/assets/baef674b-5dd8-4487-9f83-4bc23206c122)

![Image](https://github.com/user-attachments/assets/cd6c8ad4-c296-4496-9504-f3830e398d4b)

![Image](https://github.com/user-attachments/assets/22762e3b-8338-41db-a467-18b4e066e58c)

![Image](https://github.com/user-attachments/assets/9b074e7e-b8cd-43d4-bc6e-0cb484357397)

![Image](https://github.com/user-attachments/assets/3dc7c7d9-4340-4b7c-9d72-85915da63816)

![Image](https://github.com/user-attachments/assets/3ec7f706-e8f4-43b9-9998-d9b69b6ba351)

![Image](https://github.com/user-attachments/assets/879dbd30-4472-48c6-a205-3bb869b9dc39)

Now, all CustomerIDs are segmented according to RFM analysis
