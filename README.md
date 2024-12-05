# **Analysis of Potential *Matatu* Income Data**

![image alt](https://github.com/LexMainye/Transport-Data/blob/main/Plots/Image/AI%20Matatu.jpeg?raw=true![image](https://github.com/user-attachments/assets/b01083a1-67a4-4504-8166-c72b3038b6cf)
) 

# **Brief History of *Matatus***

Matatus are the go to method of public transportation in Kenya, originating in the 1960s. The term "matatu" comes from the Swahili word for "three," referring to the three cents charged per trip when they first began operating. Initially, they were informal, privately owned minibuses or vans that filled a gap in public transportation. Over the years, matatus have become a cornerstone of Kenya's transport sector, evolving into a more structured yet still vibrant and culturally significant industry.

# **Background on Analyzing Hypothetical *Matatu* Income Data**

In this project, I aim to analyze hypothetical income data for matatus, which has been generated synthetically to simulate real scenarios. Using hypothetical data allows us to focus on analytical methods, data modeling, and interpretation without the need for access to actual operational data, which may be sensitive or unavailable.

**What the Hypothetical Data Includes:**
* The data contains simulated data for a week which includes:

**Daily Income:**
* This is fare paid by passengers.
  
**Time Period:**

* The income data is categorized into specific time periods to better analyze trends throughout the day. Below is a breakdown of the time periods:

| **Time Period**     | **Description**                                      | **Approximate Time Range** |
|----------------------|------------------------------------------------------|----------------------------|
| **Early Morning**    | The first part of the day, often busy with commuters starting their day. | 4:00 AM - 6:59 AM          |
| **Morning**          | The regular morning rush with peak passenger traffic. | 7:00 AM - 9:59 AM          |
| **Late Morning**     | A quieter period as the morning rush subsides.       | 10:00 AM - 11:59 AM        |
| **Early Afternoon**  | Transition period with moderate passenger flow.      | 12:00 PM - 1:59 PM         |
| **Afternoon**        | Midday activity with commutters. | 2:00 PM - 3:59 PM          |
| **Late Afternoon**   | Increasing activity as people begin their commute home. | 4:00 PM - 5:59 PM          |
| **Evening**          | High traffic as the majority return home from work.  | 6:00 PM - 6:59 PM          |
| **Night**            | Reduced activity with occasional late-night travelers. | 7:00 PM - 11:59 PM         |

This breakdown helps identify peak and off-peak periods, providing insights into revenue fluctuations and operational efficiency.


**Date:**
* The simulated dates that the transactions happened.

**Payment Channels:**
* This comprises of cash and mobile money channels (M-PESA, Airtel Money & T-Kash)
  
**Gender:**
*  This comprises of male and female genders.
  

**The generated matatu data can be accessed here** : [Download the Excel file](https://github.com/LexMainye/Transport-Data/blob/main/Matatu%20Data/Matatu.xlsx)


# **Data Findings**

**Total Revenue per Day**

![image alt](https://github.com/LexMainye/Transport-Data/blob/fcb16e1695f4c8fbc97b4053998cd5431ce83e64/Plots/Total%20Revenue%20Per%20Day.png) 

- The above plot gives a breakdown on the total revenue earned per day with the highest revenue being earned on the 07/11/2024.

**Number of transactions per time period**
![image alt](https://github.com/LexMainye/Transport-Data/blob/fcb16e1695f4c8fbc97b4053998cd5431ce83e64/Plots/Number%20of%20Transactions%20per%20Time%20Period.png) 

- The graph shows the average number of transactions happening in each time period with the highest number of transactions taking place late morning periods.

**Gender Distribution**
![image alt](https://github.com/LexMainye/Transport-Data/blob/c273b7fbe0db0903517a96104188111d0356063e/Plots/Gender%20Distribution.png)

- The above plot shows that females appear to use *matatus* more than males.

**Payment Distribution by Time Period**
![image alt](https://github.com/LexMainye/Transport-Data/blob/62a11783865d5fd3b6db1a437c132f12a81a59c8/Plots/Payment%20Channel%20Distribution%20by%20Time%20Period.png)

- The above plot shows the breakdown of the payment distribution used at different time periods.

**Average Fare Per Time Period**
![image alt](https://github.com/LexMainye/Transport-Data/blob/62a11783865d5fd3b6db1a437c132f12a81a59c8/Plots/Average%20Fare%20per%20Time%20Period.png)

- The above plot shows the average fare paid during each time period.

**Payment Channel by Gender**
![image alt](https://github.com/LexMainye/Transport-Data/blob/62a11783865d5fd3b6db1a437c132f12a81a59c8/Plots/Payment%20Channel%20by%20Gender(Weekly).png)

- The above plot show the above breakdown of the payment channel by gender.

**Average Weekly Fare Comparison**
![image alt](https://github.com/LexMainye/Transport-Data/blob/62a11783865d5fd3b6db1a437c132f12a81a59c8/Plots/Weekly%20Average%20Fare%20Comparison.png)

- The above plot shows the comparison between the average farea paid between the off-peak and peak periods.

**Transaction Load vs Vehicle Availability**
![image alt](https://github.com/LexMainye/Transport-Data/blob/62a11783865d5fd3b6db1a437c132f12a81a59c8/Plots/Transaction%20Load%20vs.%20Vehicle%20Availability.png)

- The above plot shows the transaction volume between the transaction load versus the vehicle availability of 1 *matatu*.

**Transaction Volume Trend**
![image alt](https://github.com/LexMainye/Transport-Data/blob/62a11783865d5fd3b6db1a437c132f12a81a59c8/Plots/Transaction%20Volume%20Trend.png)

- The above plot show the volume trend of the data showing trends in transactions across different days.

**Profitability by Payment Channel**
![image alt](https://github.com/LexMainye/Transport-Data/blob/62a11783865d5fd3b6db1a437c132f12a81a59c8/Plots/Profitability%20by%20Payment%20Channel.png)

- The above plot show the profitability across the different payment channel by each prefered payment channel that may be preferred by a *matatu* passenger

**Forecast of transactions**
![image alt](https://github.com/LexMainye/Transport-Data/blob/62a11783865d5fd3b6db1a437c132f12a81a59c8/Plots/Transaction%20Forecast%20using%20ARIMA.png)

- The above plot shows the observed and predicted fare rates.

**Linear Regression of Actual Vs Predicted Fare Amounts**
![image alt](https://github.com/LexMainye/Transport-Data/blob/62a11783865d5fd3b6db1a437c132f12a81a59c8/Plots/Linear%20Regression%3A%20Actual%20vs.%20Predicted%20Fare%20Amounts.png)

- The above plot shows the linear regression between the predicted and actual fare amounts where there is comparison of the model's predicted values to the actual values and shows how well they align

### Findings from the Apriori Analysis

The analysis conducted using the Apriori algorithm yielded a set of association rules that highlight patterns in the hypothetical matatu income data. 

**Link to the association rule spreadsheet**:[Download the Excel file](https://github.com/LexMainye/Transport-Data/blob/62a11783865d5fd3b6db1a437c132f12a81a59c8/Matatu%20Data/association_rules.xlsx)

Below is a summary of the key findings from the spreadsheet:

---

#### Key Metrics Overview:
1. **Support:**  
   - Support values across the rules are relatively low (<5%), indicating that the specific combinations of antecedents (e.g., time periods) and consequents (e.g., payment methods) are not very frequent.
   - Example: The rule *"Early Morning → Cash"* has a support of **3.1%**, meaning this combination is present in 3.1% of all transactions.

2. **Confidence:**  
   - Confidence values indicate the likelihood of a consequent occurring given the antecedent.
   - Higher confidence rules include *"Morning → Cash"* with **28.8%**, suggesting a strong association between the morning time period and cash payments.

3. **Lift:**  
   - Lift values mostly hover slightly above 1 (e.g., 1.05–1.12), indicating weak but positive associations.
   - For example, the rule *"Afternoon → Cash"* has a lift of **1.079**, showing that afternoon transactions are only slightly more likely to involve cash payments than by random chance.

4. **Jaccard, Leverage, and Conviction:**  
   - These secondary metrics further validate the associations:
     - **Jaccard values** are low (<0.05), reinforcing that the intersections of antecedents and consequents occur infrequently.
     - **Leverage values** are close to zero, confirming that the discovered rules do not drastically deviate from random co-occurrences.
     - **Conviction values** (>1) suggest modest dependency between antecedents and consequents.

---

#### Notable Patterns:
1. **Cash as a Predominant Payment Method:**  
   - Many rules indicate **Cash** as a frequent consequent across various time periods, reflecting its dominance as the primary payment channel.

2. **Time Period Influence:**  
   - Rules highlight specific patterns, such as:
     - *Early Morning → Cash* (28.8% confidence)
     - *Late Morning → Cash* (27.1% confidence)

3. **Weak Relationships Overall:**  
   - While the confidence levels suggest some predictable trends, the low support and moderate lift values indicate that these rules are not strongly definitive for most transactions.

---

#### Practical Applications:
1. **Optimize Payment Methods:**  
   - Insights into dominant cash payments during specific times can help introduce digital payment incentives during low-confidence periods (e.g., late afternoon or night).

2. **Peak Time Adjustments:**  
   - High-confidence rules for busy periods like *Morning* can guide scheduling and resource allocation strategies.

3. **Future Data Needs:**  
   - The weak associations suggest potential benefits in expanding the dataset or including additional variables, such as passenger demographics or route types, to uncover more actionable patterns.

---
### Cluster Analysis Findings

The cluster analysis conducted on the transaction amounts grouped the data into three clusters. Each cluster represents a group of transactions with similar patterns in terms of the average transaction amount. Below is a summary of the findings:

---

#### Cluster Grouping

| **Cluster** | **Average Transaction Amount (KES)** | **Description**                              |
|-------------|--------------------------------------|----------------------------------------------|
| 0           | 103.38                               | Transactions with slightly lower-than-average amounts. |
| 1           | 104.42                               | Cluster with the highest average amount, possibly representing peak times or premium routes. |
| 2           | 103.43                               | Similar to Cluster 0 but with a marginally higher average amount. |

---

#### Key Observations
1. **Marginal Differences:**  
   - The average transaction amounts across clusters range from KES 103.38 to KES 104.42, showing only slight variations.

2. **Cluster 1 Dominance:**  
   - Cluster 1 stands out with the highest average amount, suggesting potential alignment with high-demand periods or specific routes.

3. **Homogeneity in Data:**  
   - The minimal variation in amounts suggests a relatively uniform dataset in terms of pricing or income patterns.

---
### Random Forest Classifier Results

The Random Forest Classifier was applied to the income data, producing exceptional results. Below is a summary and interpretation of the findings:

---

#### Performance Metrics

| **Metric**     | **Value** |
|-----------------|-----------|
| **Precision**   | 1.00      |
| **Recall**      | 1.00      |
| **F1-Score**    | 1.00      |
| **Accuracy**    | 1.00      |

---

#### Key Observations:
1. **Perfect Classification:**  
   - The classifier achieved **100% accuracy**, with precision, recall, and F1-score all at their maximum values of **1.00**. This means the model made no errors in classifying the dataset.

2. **Support:**  
   - A total of **421** data points were used, all belonging to a single class (labeled as "0"). This suggests uniformity or imbalance in the dataset.

3. **Feature Importance:**  
   - Random Forest provides a measure of feature importance, which can identify the most influential factors in income classification.

---

#### Insights from Feature Importance:
The most critical features influencing classification should be analyzed to guide practical decision-making. For example:
- **Time of Day:** Which time periods generate the highest or lowest income?  
- **Payment Method:** Is cash or digital payment a more significant contributor to income patterns?  

This information can help optimize operations or pricing strategies.

---
