## Global Superstore Orders Project
### Project Overview
This project deals with a global retail store that ships products to various regions. It has a large range of products that has been subdivided into categories and subcategories. This project aims to understand the purchasing behaviors of customers and different products.

### Objectives
•	Which category had the most profits?

•	The best sub-category for each category.

•	Which category sold the most quantities?

•	Which segment is making a lot of orders/sales/Units?

•	Product performance per region, market, country, state, city.

•	Which product has the most discount and how did it perform (Category, Subcategory)

### Data sources
This dataset was downloaded from Google Datasets. It consists of over 50k rows and ranges of data from all over the world with various products. It consists of 24 unique columns. It shows all the sales, profit and discounts of very many products.

### Data Cleaning/Preparation
•	Data filtering- I displayed only the rows that met certain criteria, making it easier to focus on specific information in a large dataset. Here's a basic guide on how to filter data in Excel.

•	Data Deduplication- It involved removing duplicate records or entries from the dataset in order to maintain data accuracy and consistency. In Excel, you can perform data deduplication using various methods. It removes entire rows that are considered duplicates based on the selected columns. 

•	Data validation- It helped control what kind of data can be entered into a cell. It ensures data accuracy and consistency by defining rules or criteria for the input. It is a powerful tool for maintaining data integrity in your Excel sheets. It helps prevent errors and ensures that data adheres to specified criteria, making your spreadsheets more accurate and reliable.

•	Data Aggregation-In this process I created the total sales and also organized the profits and quantities to enable easy exploration and presentation of data.

•	Data Cleansing- is the process of detecting and correcting (or removing) corrupt or inaccurate records from a dataset, table, or database. It involves identifying incomplete, incorrect, irrelevant, etc., parts of the data and then replacing, modifying, or deleting this dirty data. In Excel, data cleansing might involve several steps, depending on the complexity and nature of your data. Ensuring that your data follows a consistent format, is especially important for dates, categorizations, and any text-based information. Sometimes, numbers are formatted as text, which can prevent calculations or logical operations. Outliers can affect averages and other statistical calculations. Missing data can lead to biased analysis and incorrect conclusions.

### Exploratory Data Analysis
The store made very many sales all over the world which have tremendously increased over time. This has also enabled an increase in net profit over the four years.
Technology has made massive gains and profits for the store. It also made slightly more than other categories. However, Office supplies lead massively in the number of quantities it sold.

![Profit By Category](https://github.com/datawithlusaka/Superstore-Orders-Project/blob/main/Images/profit_by_category.jpg)


![Sales By Category](https://github.com/datawithlusaka/Superstore-Orders-Project/blob/main/Images/sales_by_category.jpg)


![Quantity By Category](https://github.com/datawithlusaka/Superstore-Orders-Project/blob/main/Images/quantity_by_category.jpg)


Many orders mostly used the standard class which was the cheapest mode to ship. However, a good number have also preferred first and second-class. The standard class was averagely half of all the other ship modes. The least used was same day which was also the most expensive in the ship mode.

![Preferred Ship Mode](https://github.com/datawithlusaka/Superstore-Orders-Project/blob/main/Images/preferred_ship_mode.jpg)

![Ship Mode By Category](https://github.com/datawithlusaka/Superstore-Orders-Project/blob/main/Images/category_ship_mode.jpg)

![Avg Shipping Cost](https://github.com/datawithlusaka/Superstore-Orders-Project/blob/main/Images/avg_cost_by_ship_mode.jpg)



The majority of customers are consumers mostly. They stand for over 40% of the total market. The least is the home office.

![Customer By Segment](https://github.com/datawithlusaka/Superstore-Orders-Project/blob/main/Images/customers_by_segment.jpg)



The most discounted products performed the least. Products such as tables brought losses to the store. In every category, the most discounted products performed very poorly. In categories, the furniture got the most discounts which made it perform well in sales. However, It didn't yield as much profit as expected.

![Discounts](https://github.com/datawithlusaka/Superstore-Orders-Project/blob/main/Images/discounts.jpg)


