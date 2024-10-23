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
Below is the overview page from my Excel report, which provides insights to support my findings and includes recommendations that highlight key opportunities for improvement.
