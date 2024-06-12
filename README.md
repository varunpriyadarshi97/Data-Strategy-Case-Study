# Data Strategy Case Study : OLIST- Brazilian e-commerce company 
> In this assignment, The focus is to demonstrate the road to DS adoption and the monetary benefits that will accompany the adoption.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)

## General Information
- ### What is the background of your project?

Today, almost all companies are trying to adopt DS solutions and techniques into their business programs. The adoption of DS offers certain unique capabilities and opportunities that impact both sides of the balance sheet, increase revenue and reduce costs. For some businesses like fleet management and OTT platforms, DS adoption is easy. However, it is difficult for some other businesses like manufacturing and healthcare. 


Regardless of how difficult it is to implement DS projects, the benefits they offer outweigh the efforts one needs to put in. For instance, in manufacturing companies, workers are required to wear safety equipment. Now, it can be extremely labour intensive for security personnel to look at all the CCTV footage at once to keep a watch on the workers. However, a DS solution can do this quite easily. It can use a computer vision model to consume all the CCTV footage, identify employees who are not wearing safety equipment and highlight these employees to security personnel. The security personnel can then decide the action that needs to be taken. 


Usually, the companies that are at an advanced stage in DS adoption have in-house data science teams, while other companies start by outsourcing projects to consultants. 

- ### What is the business problem that your project is trying to solve?

OLIST is an e-commerce company similar to Amazon; it is a marketplace where sellers and buyers come together. For the immediate short term, the company leadership has come up with the following four business goals: 

  - Increasing the number of active customers  
  - Increasing revenue
  - Increasing the efficiency of services 
  - Improving customer experience

The company is looking to leverage the power of analytics to improve its processes and improve its product offering. The leadership team at OLIST has identified some projects that they think will create value in the business. 

Now, there are certain constraints in the company; the company has set up the data science team recently. The team is small, and resources are limited. Given such a situation, we have to choose the right roadmap for DS adoption based on the size, feasibility, complexity and value of the use case.

We are required to create a presentation that will demonstrate the road to DS adoption and the monetary benefits that will accompany the adoption.

- ### What is the dataset that is being used?
  
OLIST data set contains the company data for approximately 100k orders from 2016 to 2017. The diagram given below shows the different tables included in the data set and how they are connected to each other. 

Each table contains certain attributes that are being recorded. For instance, the ‘sellers_dataset’ table contains the following four attributes: seller_id, seller_zip_code_prefix, seller_city and seller_state. 

Additionally, the seller_data table is attached to the order_items table set via seller_id, and the geolocation_data set via seller_zip_code_prefix. You can use the seller_id attribute to join order_items and seller_data and so on. 

![image](https://github.com/varunpriyadarshi97/Data-Strategy-Case-Study-Brazilian-e-commerce-company-OLIST/assets/57171367/11c02606-28a6-4e12-a9da-51bd05df119d)

 - ### What is the identified Use Cases?

The leadership team at OLIST has come up with the following six use cases: 

- #### Delivery Date Prediction

The logistics team at OLIST uses heuristics to provide an estimated delivery date for the orders placed by the customers. It is very conservative about the delivery dates. As a result, the team is able to deliver the products much in advance. Although this is beneficial for the logistics team’s 'on time delivery' KPI, it is not favourable for the Chief Marketing Officer (CMO). The CMO has found that on average, the estimated time to deliver products that are given to customers is twice that of the actual delivery time. Such a high expected delivery time is driving away OLIST's customers. So, the CMO is looking to use ML to get a far more accurate expected delivery date.

Accurately predicting delivery dates has many benefits; the first and the most obvious one is customer delight. Receiving a delivery on the expected data not only gives customers happiness but also keeps the business competitive. Making accurate date predictions will also set the right expectation with the delivery team, to have tighter control over inventory management and last mile delivery.
 
- #### Sentiment Analysis

The Chief Marketing Officer at OLIST wants to understand the experience of the customers based on the reviews received after the delivery of the orders. He also wants to identify the areas of improvement based on these reviews. He has heard that NLP can be used for sentiment analysis. However, he is also cognizant of the fact that the customer reviews are written in Portuguese, whereas NLP algorithms are not so sophisticated in Portuguese.

Customer sentiment is an intangible but important resource any business has. Like any other resource sentiment, it needs to be managed. There are multiple ways of performing sentiment analysis, but this use case relates to using customer reviews to identify the customers that are happy with OLIST and the ones that are not happy with it. Once the customers are identified, you can think of different ways to manage their sentiment or exploit it.
 
- #### Customer Churn

Customer churn is a critical metric for the CMO of any e-commerce company. OLIST wants to develop customer churn models to identify 'at-risk’ customers so that an appropriate retention strategy can be built. This will provide insights into the factors driving customer churn, thus reinforcing its retention efforts.

Maintaining a large customer base is an important way of increasing revenue. However, as it happens in many businesses, customers tend to move between e-commerce companies. To prevent customers from constantly migrating, the company has built a churn model. The model is used to identify the customers who are likely to migrate. Now, the company wants to come up with a strategy to prevent churn.
 
- #### Customer Acquisition Cost Optimisation

The Marketing team at OLIST runs multiple promotional campaigns to acquire new customers. However, the CFO believes that the marketing team is burning significant cash by offering deep discounts on products and other benefits, which is inflating the customer acquisition cost. The CFO wants to initiate a new process to measure the effectiveness of the acquisition campaigns by comparing them against the lifetime value of customers.

Another way of increasing revenue is to gain more customers. The money that a company spends on getting one customer is called the acquisition cost. For instance, suppose OLIST has to spend 30 BR to acquire one customer. In this case, 30 Brazilian Real (BR) is the acquisition cost of the customer. Obviously, it would be worth spending the 30 BR only if the customer generates more than 30 BR of lifetime revenue. So, the company wants to solve this optimisation problem.
 
- #### Fraud Detection

Fraud is one of the most challenging areas to deal with in the e-commerce industry, as it can result in huge financial losses. There can be fraud in the areas of merchant identity, advanced fee, wire transfer scams, chargeback transactions, etc. The CFO wants to use the power of analytics to identify fraudulent transactions so as to help guard the organisation against such actions.

E-commerce marketplaces are a platform that brings together sellers and buyers. Any fraud that happens between independent sellers and buyers will harm the company’s image. The harm caused will have a direct impact on the revenue of the company.
 
- #### Price Optimisation

Pricing is one of the most important aspects of business for an e-commerce organisation. It has a direct and profound impact on revenue, sales, profit and demand. Price optimisation is performed using a number of factors such as the location, the attitude of the customer, competitor’s pricing, etc. And, the data science algorithm predicts the customer’s segmentation to develop a response to the change in price. The OLIST sales team wants to build a price optimisation algorithm so as to maximise sales and revenue.

Similar to acquisition cost optimisation, price optimisation is also a balancing act. There are multiple factors that go into deciding the price of a product such that a customer is most likely to buy it. If the product is priced high, then the probability of selling the product is low but the profit generated is high. On the other hand, if the price is low, then the probability of selling the product is high but the profit generated is low. Moreover, the probability of selling a product is dependent on multiple factors such as customer segments and special occasions.


## Technologies Used

- Jyupter Notebook
- MS Office

  
## Contact
Created by [Varun Priyadarshi](https://github.com/varunpriyadarshi97) - feel free to contact me!
