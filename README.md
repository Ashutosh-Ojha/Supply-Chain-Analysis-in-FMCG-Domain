
![Atliq Mart](https://github.com/Ashutosh-Ojha/Supply-Chain-Analysis-in-FMCG-Domain/blob/master/Resources/ATLIQ.png)

# Problem Statement
AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India. It is currently operational in three cities Surat, Ahmedabad and Vadodra. They want to expand to other metro/tier1 cities in the next 2 years.

AtliQ Mart is currently facing a problem where a few key customers did not extend the annual contract due to service issues. It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, which could have resulted in bad customer service. Management wants to fix this issue before expanding to other cities and requested their supply chain analytics team to track the ’On time’ and ‘In Full’ delivery service level for all the customers on a daily basis so that they can respond swiftly to these issues.

The Supply Chain team decided to use a standard approach to measure the service level in which they will measure ‘on-time delivery (OT) %’, ‘In-full delivery (IF) %’ and OnTime in full (OTIF) % of the customer orders on a daily basis against the target service level set for each customer.

## Task  
As the data analyst in the supply chain team who joined Atliq Mart recently. You have been briefed about the the task in the stakeholder business review meeting. Now Imagine yourself play the role of the new data analyst who is excited to build this dashboard and perform the following task

1.Create the metrics according to the metrics list.

2.Create a dashboard according to the requirements provided by stakeholders in the business review meeting. You will be provided with the transcript of this business review meeting in the form of a comic.

3.Create relevant insights that are not provided in the metric list/stakeholder meeting
 
## **Datasource**
The data, metrics list, domain concepts, business stakeholder meetings can all be sourced on [codebasics.io](https://codebasics.io/event/codebasics-resume-project-challenge)

## Data Cleaning and Transformation
To perform this task, the process involved were:

1.Importing data as a CSV file and creating a data model from scratch to link the tables 

![Data Model](https://github.com/Ashutosh-Ojha/Supply-Chain-Analysis-in-FMCG-Domain/blob/master/Data%20model.png)
                    **power BI Data Modeling**

2. Using the appropriate data types and creating calculated columns to aid in providing more insights

3. Creating Measures & calculations using DAX to track requested metrics, like;

    a. DOT% - Delivery on Time
    
    b. DIF% - Delivery in Full
    
    c. OTIF% - On Time In Full
    
    d. Total orders and Total Orderlines
    
    e. LIFR% - Line Fill Rate
    
    f. VOFR% - Volume Fill Rate
    
    g. Delivery Days, etc
    
 4. Creating tooltips and visuals using appropriate charts to communicate findings


## **Insights**


- OTIF is a 'Hard' metric from customer's point of view, but we are unable to meet the customer's demand both by quantity ordered and timely delivery in all the cities. We are trailing with an average of 36.6% in all cities, which is hampering the reliability of customer.

- VOFR is performing good compared to LIFR in all the cities which means we are unable to deliver all requested products from customers. So, we should be prepared with inventory beforehand. At least in the demand season.

- 'Delay in Delivery' has been a major problem in all cities. We were able to deliver 18% of order before agreed delivery date. But, for so many orders were unable deliver 'On Time'. The delay is seen for 1,2, and 3 days with an average of 1.21 days.

- Vadodara, being our biggest market, has much efficient supply chain compared to other two cities since COCD in Ahmedabad and Surat is very high. We should have serious attention to this particular case.

- Customers who are our biggest client and facing serious issues are follows. Their issues should be resolved first.
    
    - Acclaimed Stores.

    - CoolBlue.

    - Lotus Mart.

    - Vijay Stores.