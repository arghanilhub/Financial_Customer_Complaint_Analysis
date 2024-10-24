# Consumer Complaint Analysis ( Bank of America )
<br/> 
<h3>Project Background</h3> 
<hr>
Analyzing the consumer complaints on the financial products and services for the bank of america from 2017 to 2023. 

Normally, customers submit their complaints to the **Consumer Financial Protection Bureau (CFPB)**, which then forwards them to the bank. However, due to the recent rise in complaints, the bank wants to analyze seven years of complaint data to identify any trends related to specific products receiving the most complaints.  The dataset used for this analysis is real and sourced from the CFPB database.<br/> 

This project throughly analyzes and synthesizes this data in order to uncover critical insights which will help the bank improve services and enhance customer retention.

**Answering the following key questions through my analysis in these areas :** <br/> 

**Complaint trend** : Do consumer complaints show any kind of seasonal pattern?<br/> 
**Product analysis** : For which Product and services, customer's are complaining about most? what are their common issues? and how they are being typically resolved?<br/> 
**Company Responce** : Is there any trend in the company's responses to the problems arising from the products with the most complaints? Can we learn anything from the issues where the company is providing *untimely responses*?<br/> 
**Complaint tracker** : In 2023, how many complaint are still *in-progress*?<br/>  
Both the complaint analysis and tracker reports, created in Excel, can be downloaded from the following link: [Download the Excel report](https://github.com/arghanilhub/Customer_Complaint_Analysis/blob/main/Financial_Consumer_Complaints.xlsx) 
<br/> 
<br/> 
<br/> 

<h3>Data structure and Initial checks</h3> 
<hr> 
The dataset contains 62,000 complaint records spanning from May 2017 to August 2023, including the following details :<br/> 

* The dates the complaints was submitted to the CFPB and then sent to the company.<br/> 
* The product and the issue types mentioned in the complaints.<br/>  
* The company's responce how they resolved it and<br/>  
* How many complaits are still in-progress to solve.<br/>


&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;![Complaint ERD](https://github.com/arghanilhub/Customer_Complaint_Analysis/blob/main/complaint_ERD.png) 

I added **two** additional calculated columns: **Starting Week** and **Open/Close**, with data types *Date* and *Boolean*,' respectively. The 'Starting Week' column breaks down the complaint received dates by week, making it easier to track open and closed cases on a weekly basis. You can view the functions I used to create these columns in my newly prepared dataset, which is included in the final report file along with the raw data.   
<br/> 

<h3>Executive Summery</h3> 
<hr> 
<h4>Overview Findings</h4> 

There has been a gradual increase in the complaint rate from 2017 to 2023, with a sharp rise **after 2021**, particularly during **July and August**, which consistently see the highest volume of complaints. Most complaints stem from issues with **savings accounts and credit-card** related problems. While the majority of complaints have been resolved promptly, with responses typically provided within 2-3 days, addressing consumer concerns during peak months remains a challenge.<br/>  
Below is the overview page from my Excel report, which provides insights to answer the set of questions on key areas which mentioned above and includes recommendations that highlight key opportunities for improvement.<br/>  
**1. Complaint trend** 
* The incoming complaints do not follow any strict seasonal patterns. Month-over-month, the rise or fall of complaints appears very random.
* Since the last quarter of 2020, there has been a sudden rise in the number of complaints for most products, which continued until July 2023. After that, there was a sharp decline in complaints within just one month.
* From **Q4 2018 to Q1 2019**, this was the only time when the rate of complaints significantly dropped compared to the rest of the months in the analyzed time period.<br/>


&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ![complant trend](https://github.com/arghanilhub/Customer_Complaint_Analysis/blob/main/Complaint_trend.png) <br/> 
<br/> 
 
**2. Product analysis** 
* **Credit card and savings account**-related issues have *received the most complaints*, and these have increased over the last 3 years.
* Credit cards received the most complaints in **Q1 and Q4 (i.e., during tax and holiday periods)**.
* **Mortgage and student loans** are the only two products showing completely **opposite trends** from the rest, as their complaint rates have decreased over the years.
* *Common issues*- For savings accounts, people are mostly facing issues with **managing their accounts**, particularly with **deposits, withdrawals, and using their debit/ATM cards**.
* For credit cards, customers are mainly facing two issues :                                                                                 
     1.  Their **statements** show purchases they did not make, and the credit card company is not resolving these issues.
     2.  Customers are receiving new credit cards due to **identity theft** or fraud.
* The company *resolved* most of these complaints either through **explanations** or by providing **monetary relief**.
<br/> 
   
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ![product](https://github.com/arghanilhub/Customer_Complaint_Analysis/blob/main/Product.png) <br/> 
<br/> 
**3. Company responce** 
* For **fraud issues**, the company is providing more *non-monetary relief*, particularly in cases of credit card identity theft.
* The company's *public response* regarding these top two products is mostly private to the consumer and the CFPB, and it has not been disclosed to the public.
* For almost all issues, the companies' timely response percentage is significantly higher than the untimely responses. However, if there is an **untimely response** regarding particular issues that may raise concerns for customers—such as when people are unable to use their debit cards or when there are unknown purchases listed on their credit card statements—the bank often resolves these complaints with **monetary relief, especially since 2022**.
* There has been a noticeable **trend in untimely responses** for the most common issues between 2017 and 2023. From 2017 to 2020, untimely responses were very low, but they spiked sharply in 2021. Since then, they have gradually decreased throughout 2022 and 2023.
<br/>

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ![untimely responce](https://github.com/arghanilhub/Customer_Complaint_Analysis/blob/main/Untimely_responce.png) 
<br/> 
**4. Complaint tracker** 
* Complaints that are **still unresolved** are only found in the last year of this seven-year period (**2023**). Before that, all complaints have been closed.
* In 2023, open complaints are concentrated in the last three months (**June, July, and August**), with the majority occurring between the **week** of **June 10th to August 7th**.<br/> 
  
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ![complaint tracker N](https://github.com/arghanilhub/Customer_Complaint_Analysis/blob/main/complaint_tracker_N.png) 
<br/> 
<br/> 

<h4>Recommendations</h4> 

* To counter the surge of incoming complaints, we should *analyze the strategies* implemented during the periods of **Q4 2018 – Q1 2019** and **August 2023**, when a noticeable decrease in complaint rates occurred. These effective methods can be applied to other months experiencing higher complaint levels.<br/> 

   
 * For *Savings account* problems: We need to further investigate the specific withdrawal or ATM issues customers are facing. 
                                  However, there are some immediate steps we can take to address these problems, such as:<br/> 
                                   &nbsp; &nbsp; i) Implementing a 24/7 **dedicated customer support** hotline or in-app services for ATM card issues.<br/> 
                                  &nbsp; &nbsp; ii) Offering **self-service resolution** options and **real-time tracking** through mobile banking apps for deposit and  withdrawal queries, along with financial literacy resources.<br/>   


* For *credit issues* - we can **enhance fraud detection systems** to identify and block unauthorized transactions in real time, combined with **stronger identity verification** (like two-factor authentication or biometrics) to prevent identity theft. Additionally, establishing a **Rapid Response Team** for quick handling of disputed cases can ensure faster resolution and improve customer confidence. 







