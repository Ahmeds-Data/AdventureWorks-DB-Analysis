# Executive Summary
# Selected Dataset
<div align="justify">
The Adventure works dataset is obtained from Kaggle, an open-source 
platform which provides a large number of datasets and problems for users to work 
on, and it also provides tools for users to submit and evaluate their models.
</div>

<a href="https://www.kaggle.com/datasets/ukveteran/adventure-works" target="_blank">Adventure Works on Kaggle</a>

<br>
<div align="justify">
The Adventure Works dataset consists of 18,000 customers, both women and 
men are involved in purchasing the company’s products. Each of the customers' data 
recorded consists of their personal information including customer Key, first Name, 
last Name, email address, and annual income.
</div>
<br>
<div align="justify">
The dataset also involves products and its subcategories that includes different 
brands of bikes that are categorized into four groups: bikes, components, clothing, and 
accessories. Since the company manufactures its own components, accessories, and 
clothing. The primary selling products of AW are several different brands of bikes 
including mountain, road, and touring bikes.</div> <br>
It also has more than 56,000 sales records from years 2015, 2016, and 2017 
with their returned orders and the territories where it has shipped from and into.

# Business Background
<div align="justify">
Adventure works cycles, is a company on which the adventure works sample 
databases are based, is a large, multinational manufacturing company. The company 
manufactures and sells metal and composite bicycles to ten territories, including northAmerican, 
European and Asian commercial markets. The company is focusing on four 
different categories like Bikes, Components, Clothing and Accessories. While its base 
operation is located in Bothell, several regional sales teams are located throughout 
their market base. 
</div>
<br>
<div align="justify">
In early 2001, adventure works cycles bought a small manufacturing plant 
located in Mexico. And most of the products were modelled by outside vendors. In 
such instances, AW becomes the reseller. The company started manufactures several 
critical subcategories for the AW cycles products. These subcategories are shipped to 
those vendor’s location for final product assembly. In late 2001, the company stock 
started to store different assembled products and ship these products to customers 
throughout the United States, Canada, France, Germany, Australia, and the United 
Kingdom
</div>

# The Schema
<div align="justify">
  After data collection, we have created the Adventure Works Database Schema 
by combining different attributes of the data and created ten different tables. we have 
combined different types of products and its subcategories with the products main four 
categories, and we’ve collected the sales of these products in three-year operations and 
the sales return in this period and combined it with sales territories such as regions and 
countries. We also obtained the customers with their personal data such as names, 
Email and their annual income.
We had to make sure that the date type of all the columns is in the right format, 
for example DATE type had to be changed into "YYYY-MM-DD" format, as well as 
Annual Income containing US dollar Symbol “$”, we had to remove it so it matches 
the integer data type and gives us access to make statistical queries or order by 
ascending and descending. We also had to assure that the primary keys must be unique.
</div>

![diagram model](https://user-images.githubusercontent.com/126220185/222852525-e807b4c1-dd15-40cb-a1c0-a6d52a15dd67.png)

<div align="justify">
Diagram above shows the relational schema diagram of the Adventure Works 
database, which elucidates that the selected database consists of ten relations tables 
namely, customers, products, products_subcategories, product_categories, calendar, 
territories, sales_2015, sales_2016, sales_2017 and returns. 
  </div>
  <br>
  <div align="justify">
In each of these sales tables, we had to change the order numbers in the 
OrderNumber table due to duplicates found in the dataset, and as it is a primary key 
it must involves unique values. These sales table have combined most of the other
tables primary keys as a foreign key’s in it, as well as sharing one-to-many relations
from them.
  </div>
  
- Statistical queries
<div align="justify">
Statistical queries were performed for a better understanding of the selected 
dataset. We have created and performed statistical queries to examine the dataset 
which is able to produce count, mean, median, and average values. For instance, 
average sales for the most purchased products in 2015, 2016, and 2017, Median value 
of annual income of our customers and mean value of product sales from years 2015, 
2016, and 2017.
  </div>
  
![staistical queries 1](https://user-images.githubusercontent.com/126220185/222852845-6086c556-a0d0-418b-a153-5b8a6b93c5e8.png)
![statistical queries 2](https://user-images.githubusercontent.com/126220185/222852832-0395d781-5a5f-4a41-a144-ab6627221fec.png)
![statistical queries 3](https://user-images.githubusercontent.com/126220185/222852839-c699e263-2f1b-436c-bfa1-75cd6c2cca00.png)
![statistical queries 4](https://user-images.githubusercontent.com/126220185/222852842-14e8a734-8415-4c91-b71d-6ff9cb3cb363.png)


# Scenario for Adventure Works
<div align="justify">
The management of Adventure Works would like to have a complete analysis 
during the three-years operation. An analysis of how well a firm’s products is selling, 
and the success of their sales forces by using product's initial costs analysis. As well 
as using customer segmentation to further understand the customers and do better 
marketing or promotions to the them, by analysing customer's personal data like annual 
incomes and their occupation and mark their preferred products. 
  </div>
  <br>
  <div align="justify">
The company would like to know the top sold products in each year. In 
addition, this analysis may aim at discovering the territory and regions with which 
most of the sales were made. Moreover, in order to increase revenue, we would like to 
discover the weakness of the company, for instance; products that were returned by 
the customers as a result of some damages, faults or any kind of complaint lodged by 
the customers. So that the management would tackle and handle such lapses in the 
future. Setting role-specific targets, such as a revenue target and a sales productivity 
goal, is a typical example of a sales analytics activity.
  </div>
  <br>
  <div align="justify">
Based on the available dataset and the database we created earlier, we would 
have to undergo some queries as follows:
</div>

![sinario 1](https://user-images.githubusercontent.com/126220185/222853136-e285eff7-aad3-464b-a095-935fc78ee630.png)
![scinario 2](https://user-images.githubusercontent.com/126220185/222853134-7c51eadd-9924-4978-a60d-71dcadcc6637.png)
![scinario 3](https://user-images.githubusercontent.com/126220185/222853135-b907f8cb-dded-460b-a55b-160bee27e68f.png)
![sinario 4](https://user-images.githubusercontent.com/126220185/222853138-454a652a-3ae4-461f-8141-4d12b3b38613.png)
![sinario 5](https://user-images.githubusercontent.com/126220185/222853139-85eebd79-690d-4ad0-9135-cd536ba84cc9.png)
![sinario 6](https://user-images.githubusercontent.com/126220185/222853141-326fb250-64cd-4d02-85a9-42bc880eaec2.png)
![sinario 7](https://user-images.githubusercontent.com/126220185/222853143-61b5e8f5-96e5-4019-81ae-7d6d447c2aff.png)
![sinario 8](https://user-images.githubusercontent.com/126220185/222853145-a2fc04d2-ea21-4761-9181-667aea0f51b6.png)
![sinario 9](https://user-images.githubusercontent.com/126220185/222853146-dc6f1da8-e8ff-4645-b752-ee9c138dedfe.png)
![sinario 10](https://user-images.githubusercontent.com/126220185/222853147-e43cadb3-9e5e-4d06-bc35-da2a20d02231.png)
![sinario 11](https://user-images.githubusercontent.com/126220185/222853149-2ea33176-10c7-4889-9838-40767f16a11e.png)
![sinario 12](https://user-images.githubusercontent.com/126220185/222853155-73d78e65-7b60-49a0-b525-4dd2640bd1de.png)
![sinario 13](https://user-images.githubusercontent.com/126220185/222853158-d34e6a56-1e28-463b-8cf3-94d9ff383c84.png)
![sinario 14](https://user-images.githubusercontent.com/126220185/222853160-93cf2688-6112-48a9-8b8e-04944aa4888f.png)
![sinario 15](https://user-images.githubusercontent.com/126220185/222853163-f9c43971-27fe-44b4-8904-f0c1e3495b93.png)
![sinario 16](https://user-images.githubusercontent.com/126220185/222853166-33f965d5-55e5-4eb5-a667-d6227f46953c.png)
![sinario 17](https://user-images.githubusercontent.com/126220185/222853169-e9c05d4c-cc6a-40e6-b66c-f0d5f8c776a4.png)
![sinario 18](https://user-images.githubusercontent.com/126220185/222853170-a6a29291-eb68-4e02-be33-e29a85f0c7a4.png)
![sinario 19](https://user-images.githubusercontent.com/126220185/222853175-d4345b14-35cf-478f-8586-0831b26221db.png)
![sinario 20](https://user-images.githubusercontent.com/126220185/222853123-a2d119c6-de9e-4e00-9291-4e88d2e8132d.png)
![sinario 21](https://user-images.githubusercontent.com/126220185/222853130-86179126-cbe0-4e05-b21f-a771a5ed40f7.png)
![sinario 22](https://user-images.githubusercontent.com/126220185/222853133-ef187d9b-2a6c-4719-bdaa-325fc07e7668.png)
