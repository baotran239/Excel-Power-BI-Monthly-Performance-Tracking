# [Excel & Power BI] Monthly Performance Tracking

## I. Introduction
The projects involves using Excel to quickly process sales data of a particular month and creating a Power BI dashboard to track the monthly performance of a Top-up service for an e-wallet company.

### **Note:**
- For Excel processing, please refer to the attached file named ''.
- For Power BI dashboard and analysis, please refer to both the attached file named '' and the following parts. 

## II. Dataset
To access to the dataset, please refer to the [link](https://docs.google.com/spreadsheets/d/188usb3WqsBDGYeB1nSsc2uamqaoVIEKY/edit?gid=231710739#gid=231710739)

## III. Design thinking approach
### Step 1. Empathize 
#### 5W-1H
| **Question** | **Answer** |
|---------------|----------|
| **Who will see the dashboard?** | Marketing Team |
| **If we have to choose only one stakeholder, who will it be?** | Marketing Team |
| **What problem will the dashboard help to solve?** | Monthly performance tracking dashboard: It will help the team to track the performance of the service based on the transaction data collected. |
| **Where and when will our stakeholders see the dashboard?** | In meetings, presentation sessions, or anywhere they have to make decisions. |
| **Why do we have to build the dashboard?** | Without the dashboard, the monthly tracking will be more complicated when the raw data are not structured, combined, and visualized. |
| **How will our stakeholders see the dashboard to solve their business objectives?** | The dashboard will provide the overall-to-detailed monthly performance for the team to adjust their strategies for the next months. |

#### Empathy Map
| **Category** | **Details** |
|--------------|-----------|
| **Thinking and Feeling** | They feel confused and find it hard to gain insights when looking at the raw data. They do not know whether their strategies are suitable or not. They think they can utilize transactional data to devise the right strategies. |
| **Seeing** | They see a massive and chaotic pool of raw data. |
| **Saying and Doing** | "I want to deep dive into the collected data to find the insights. I need to give data-driven decisions." They seek data analysis and visualization to support their decision-making process. |
| **Pains** | Insufficient data and information may lead to inefficient solutions and decisions. |
| **Gains** | Key insights, unmet needs, straight-to-the-point strategies, data-driven solutions. |

### Step 2. Dataset Understanding
| **Table Type** | **Details** |
|----------------|----------|
| **Fact Table** | Data Transaction |
| **Dim Table** | Data User Info, Data Commission, RFMTable |

### Step 3. Define Point of View
#### Northstar Metric
| **Question**                          | **Answers**                                                                                               |
|----------------------------------------|----------------------------------------------------------------------------------------------------------|
| **What VALUE you want to measure?**    | **1. Customer**  <br> **2. Profit**  <br> **3. Order**                                                   |
| **WHEN the value DELIVERY SUCCESS?**   | When they reach their maximum value                                                                      |
| **WHY do you choose this metric?**     | 1. To divide customers into different groups based on their transaction behavior, combined with their demographics to tailor suitable strategies for each customer group  <br> 2. To track the company's health via business growth and profitability  <br> 3. To identify customer behavior and transaction trends |

#### Dimension Data Group
| **Define Point of View** | **Group 1** | **Group 2** | **Group 3** | **Group 4** | **Group 5** | **Group 6**            |
|--------------------------|-------------|-------------|-------------|-------------|-------------|------------------------|
| **Dimension Data Group** | Time        | Location    | Age         | Gender      | Merchant    | Purchase Status        |

## IV. Dashboard
### Data modeling
![Image](https://github.com/user-attachments/assets/48a7714f-0df6-406b-ac69-84f9f90b116c)

### Dashboard
<img width="1073" alt="Image" src="https://github.com/user-attachments/assets/e908f491-d409-4aaa-b62c-d4c21aba2f22" />

## V. Insights & Recommendations
| **Insights** | **Recommendations** |
|-------------|---------------------|
| While **total order volume** is high, the **total profit per order** might be relatively low, suggesting either **low-margin products** or **high operational costs**. | **Optimize pricing strategies** to improve **profit margins** by identifying and promoting **high-margin products** through **strategic pricing, upselling, and promotions**. |
| The business experienced **seasonal fluctuations**, with a notable **peak in September**. | **Analyze seasonal trends** to launch **targeted marketing campaigns** before **peak months** and introduce **limited-time discounts** or **product bundles** in **low-revenue months** to stimulate sales. |
| The largest **customer segments** are **Potential Loyalists (4.5K)** and **At Risk (3.3K)**. | **Engage Potential Loyalists** by offering **loyalty programs** and **personalized discounts** to convert them into **repeat buyers**, while implementing **win-back campaigns** for **At Risk customers** to prevent **churn**. |
| **Viettel (7.2M VND)** and **Mobifone (5.8M VND)** are the **top-performing merchants**, while **Gmobile (0M VND)** has negligible contribution. | **Strengthen partnerships** with **top-performing merchants** such as **Viettel** and **Mobifone** by negotiating **exclusive deals** and increasing **promotions**, while **reassessing low-performing merchants** like **Gmobile** to determine their **viability**. |
| **Young adults (23-32)** are the **most profitable customer base**: The **23-27 age group** contributes the **highest profit (4.5M VND)**, followed by **28-32 (4.1M VND)**. The **lowest spending** comes from **18-22 (1.6M VND)** and **37+ age groups**. | **Focus marketing efforts** on the **23-32 age group**, which generates the **highest profit**, by leveraging **social media advertising** and **influencer collaborations**, while offering **student discounts** or **budget-friendly product bundles** to attract **younger consumers (18-22 age group)**. |
| **Women** are the **dominant purchasing group**: **Female customers (58.15%)** contribute **more orders** than **males (41.85%)**. | **Tailor marketing campaigns** toward **female customers**, who make up the **largest purchasing group**, by promoting **relevant products** and **messaging** that align with their **buying behaviors**. |
| **Ho Chi Minh City** is the **strongest market (58.98%)**, followed by **Hanoi (30.5%)**. | **Expand market penetration** in **Hanoi** and other **underperforming regions** by introducing **location-based promotions** and increasing **brand awareness campaigns** in these areas. |
| **Resellers (Mua hộ)** drive most of the **revenue (82.96%)**. | **Enhance reseller relationships** by providing **bulk discounts** and **loyalty incentives** to encourage **repeat purchases**, while also creating **exclusive benefits** for **direct consumers** to increase **self-purchase engagement**. |


