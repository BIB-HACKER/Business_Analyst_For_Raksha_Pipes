<h1 align="center"><b>Business Analyst Project: Data Management and Visualization for&nbsp;&nbsp;<img align="center" alt="Coding" width="115" src="https://github.com/BIB-HACKER/Business-Analyst-Project/blob/main/mainlogodark.png"> - Pipes </b></h1>
<div align="center">
  <h2>Hi there! 👋 I'm Bibhakar Paul</h2>
  <p>Welcome to my GitHub repository! Here's a glimpse of my skills and expertise:</p>
  <div style="padding: 20px; background-color: #f0f0f0; border-radius: 10px; box-shadow: 0px 0px 10px 0px rgba(0,0,0,0.2);">
    <img src="https://img.shields.io/badge/Python-Expert-3776AB?logo=python&logoColor=white" alt="Python Pro" style="margin: 5px; padding: 10px; border-radius: 5px; background-color: #3776AB;">
    <img src="https://img.shields.io/badge/Web%20Scraping-Pro-FF6F61?logo=webcomponents.org&logoColor=white" alt="Web Scraping Proficient" style="margin: 5px; padding: 10px; border-radius: 5px; background-color: #FF6F61;">
    <img src="https://img.shields.io/badge/SQL%20Master-4682B4?logo=sql&logoColor=white" alt="SQL Proficient" style="margin: 5px; padding: 10px; border-radius: 5px; background-color: #4682B4;">
    <img src="https://img.shields.io/badge/Data%20Analysis-Pro-F15B2A?logo=anaconda&logoColor=white" alt="Data Analysis Pro" style="margin: 5px; padding: 10px; border-radius: 5px; background-color: #F15B2A;">
    <img src="https://img.shields.io/badge/Power%20BI-Advanced-F2C811?logo=power-bi&logoColor=white" alt="Power BI Advanced" style="margin: 5px; padding: 10px; border-radius: 5px; background-color: #F2C811;">
    <img src="https://img.shields.io/badge/MongoDB-Proficient-4EA94B?logo=mongodb&logoColor=white" alt="MongoDB Proficient" style="margin: 5px; padding: 10px; border-radius: 5px; background-color: #4EA94B;">
    <img src="https://img.shields.io/badge/Excel%20Wizard-1F4068?logo=microsoft-excel&logoColor=white" alt="Excel Wizard" style="margin: 5px; padding: 10px; border-radius: 5px; background-color: #1F4068;">
  </div>
</div>

# Introduction 🚀
In today's data-driven world, effective data management and visualization are crucial for making informed business decisions. This project showcases a comprehensive approach to building a data management and visualization system from scratch for Raksha Pipes, a Bangalore-based company. The system encompasses data generation, database creation, and interactive dashboard development, providing valuable insights into business operations.

# Objective
This project aims to build a data management and visualization system from scratch for Raksha Pipes, a Bangalore-based company. The system includes data generation, database creation, and dashboard development, culminating in a detailed report and video presentation.

# Table of Contents 📊
### Step 1: Generate Data and Design Database
   - Generate Data
   - Design Database
### Step 2: Set Up Database in MySQL
### Step 3: Create Dashboard in Power BI

# Project Highlights 
- **Comprehensive Data Management:** From data generation to database creation, this project covers the full spectrum of data management practices.
- **Interactive Visualization:** Utilizing Power BI, the project includes an interactive dashboard that offers deep insights into sales trends, product performance, and customer demographics.
- **Practical Application:** The project mimics real-world business operations, providing a practical framework for similar data management and visualization tasks.

# Why Explore?
- **Enhance Your Skills:** This project offers a hands-on opportunity to enhance your skills in data management, SQL, and data visualization.
- **Real-World Application:** By working on a project that mimics real business operations, you gain practical experience that is highly valuable in the industry.
- **Insightful Analysis:** The interactive dashboard allows for deep dives into data, helping you understand and analyze key business metrics effectively.

# Project Overview 💻
## Step 1:Generate Data and Design Database <a href="https://jupyter.org/" target="_blank" rel="noreferrer"> <img src="https://github.com/devicons/devicon/blob/master/icons/jupyter/jupyter-original.svg" alt="jupyter" width="25" height="25"/> </a>
### Task: Create realistic data for Raksha Pipes and design a MySQL database.

### Generate Data 
- Use the faker library in Python to generate synthetic data.
- Ensure the data includes attributes such as product type, customer details, and sales information.
- Example Python code to generate data:
<p float="left">
  <img src="https://github.com/BIB-HACKER/Business-Analyst-Project/blob/main/Screenshot%202024-05-17%20174510.png" style="float:right"/>
</p>

### Design Database
**Create a MySQL database schema named raksha_pipes with the following tables:**
- customers(customer_id, customer_name, email, gender, product_id)
- products(product_id, product_name, price)
- orders(order_id, customer_id, order_date, total_amount, status, product_id)
- sales(sale_id, product_id, customer_id, quantity, sale_amount)
- suppliers(supplier_id, supplier_name, contact_info, product_id)
<p float="left">
  <img src="https://github.com/BIB-HACKER/Business-Analyst-Project/blob/main/Screenshot%202024-05-17%20021638.png" style="float:right"/>
</p>

## Step 2: Set Up Database in MySQL <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a>
### Task: Create the database in MySQL and add the data you generated.

- Connecting Python to Sql server:
<p float="left">
  <img src="https://github.com/BIB-HACKER/Business-Analyst-Project/blob/main/Screenshot%202024-05-17%20175910-con.png" style="float:right"/>
</p>

- Create the database schema in MySQL:
<p align="center">
  <img src="https://github.com/BIB-HACKER/Business-Analyst-Project/blob/main/Screenshot_20240517-181507~3.png" width="400" height="1000"/>
  <img src="https://github.com/BIB-HACKER/Business-Analyst-Project/blob/main/Screenshot_20240517-181543~2.png" width="400" height="1000" style="float:right"/>
</p>

- Load the generated data into the MySQL database using Python:
<p float="left">
  <img src="https://github.com/BIB-HACKER/Business-Analyst-Project/blob/main/Screenshot%202024-05-17%20022718.png" style="float:right"/>
</p>

## Step 3: Create Dashboard in Power BI <a href="https://powerbi.microsoft.com/en-us/desktop/" target="_blank" rel="noreferrer"> <img src="https://github.com/microsoft/PowerBI-Icons/blob/main/PNG/Power-BI.png" alt="Power-BI" width="25" height="35"/> </a> 
### Task: Make an interactive dashboard in Power BI to display key business metrics.

- Connect your MySQL database to Power BI.
- Develop a user-friendly dashboard that visualizes sales trends, product performance, and customer profiles.
- Example visuals:
   - Sales Trends over Time
   - Top Performing Products
   - Customer Demographics
<p float="left">
  <img src="https://github.com/BIB-HACKER/Business-Analyst-Project/blob/main/Screenshot%202024-05-17%20201316.png" style="float:right"/>
</p>

## 🔗 Connect with Me &nbsp; <a href="https://www.linkedin.com/in/bibhakar-paul-2595a721b"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
 

<h1 align="center"><b> THANK YOU </b> </h1>
