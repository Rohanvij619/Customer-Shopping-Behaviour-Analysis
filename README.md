<h1 align="center">📊 Customer Shopping Behavior Analysis</h1> <h3 align="center">End-to-End Data Analytics Project using Python, SQL & Power BI</h3>
<h2>📌 Overview</h2>

This project presents a complete end-to-end analysis of customer shopping behavior using 3,900 transactional records.
It includes Python-based EDA, data cleaning, SQL business queries, and a Power BI dashboard.

The project highlights insights related to:

<ul> <li>Spending patterns</li> <li>Customer segmentation</li> <li>Product and category performance</li> <li>Discount behavior</li> <li>Subscription trends</li> </ul>

<img width="3004" height="1406" alt="_- visual selection" src="https://github.com/user-attachments/assets/a17ae000-5d4e-4eac-a2a9-9324be821512" />

<h2>📂 Dataset Details</h2>

<strong>Rows:</strong> 3,900
<strong>Columns:</strong> 18

<strong>Key Attributes:</strong>

<ul> <li>Demographics: Age, Gender, Location, Subscription status</li> <li>Purchase details: Category, Season, Price, Size, Color</li> <li>Behavior: Discount usage, Review rating, Previous purchases</li> <li>Operational: Shipping type, Purchase frequency</li> </ul>

<strong>Missing Values:</strong>

<ul> <li>37 missing review ratings filled using category-wise median.</li> </ul>
<h2>🛠️ Tools & Technologies</h2> <ul> <li>Python (Pandas, NumPy, Matplotlib, Seaborn)</li> <li>SQL Databases (PostgreSQL, MySQL, SQL Server)</li> <li>Power BI (Interactive Dashboard)</li> <li>Gamma App (Presentation)</li> <li>Excel (Optional)</li> </ul>
<h2>📝 Project Workflow</h2> <h3>1️⃣ Data Loading & Cleaning (Python)</h3> <ul> <li>Loaded dataset using Pandas</li> <li>Explored structure with .info() and .describe()</li> <li>Filled missing ratings</li> <li>Standardized columns to snake_case</li> <li>Removed redundant column: promo_code_used</li> <li>Created new features: age_group, purchase_frequency_days</li> <li>Exported cleaned dataset to SQL</li> </ul> <h3>2️⃣ Exploratory Data Analysis (EDA)</h3> <ul> <li>Distribution analysis</li> <li>Outlier detection</li> <li>Correlation analysis</li> <li>Category-level insights</li> <li>Discount vs spending behavior</li> <li>Subscription trend analysis</li> </ul> <h3>3️⃣ SQL Analysis (PostgreSQL / MySQL / SQL Server)</h3> <ul> <li>Revenue by gender</li> <li>High-spending discount users</li> <li>Top 5 highest-rated products</li> <li>Standard vs Express shipping comparison</li> <li>Subscribers vs non-subscribers</li> <li>Most discount-dependent products</li> <li>Customer segmentation (New, Returning, Loyal)</li> <li>Top 3 products per category</li> <li>Repeat buyers & subscription relationship</li> <li>Revenue by age group</li> </ul>
<h2>📊 Power BI Dashboard</h2> <ul> <li>KPI summary</li> <li>Demographic insights</li> <li>Subscription analysis</li> <li>Category performance</li> <li>Shipping method comparison</li> <li>Review rating distribution</li> <li>Discount usage patterns</li> </ul> <img width="1289" height="738" alt="Screenshot 2025-12-05 081543" src="https://github.com/user-attachments/assets/1de579df-e9a9-41a8-998f-6a94b2dd97e0" />
<h2>📈 Key Results & Insights</h2> <ul> <li>Subscribers generate higher revenue than non-subscribers.</li> <li>Express shipping customers have higher average order value.</li> <li>Female shoppers contribute more total revenue.</li> <li>Loyal customers (5+ purchases) show higher subscription likelihood.</li> <li>Top-rated products often overlap with best-sellers.</li> <li>Age group 18–30 contributes the highest revenue share.</li> </ul>
<h2>▶️ How to Run This Project</h2> <h3>1. Clone Repository</h3>
git clone <(https://github.com/Rohanvij619/Customer-Shopping-Behaviour-Analysis.git)> <br>
cd customer-shopping-analysis

<h3>2. Open Customer_Shopping_Behavior_Analysis.ipynb notebook</h3>
This file contains:
<ul> <li>Data Import</li> <li>Data Exploration</li> <li>Data Cleaning</li> <li>Connection to SQL Database</li> </ul>

<h3>3. Load the data from Python notebook into MySQL/PostgreSQL/MS SQL Server</h3>
<ul> <li>Create a database in SQL</li> <li>Run Python code to load data into SQL database</li> <li>Open customer_behavior_sql_queries.sql</li> <li>Answer Business Questions using SQL Queries</li> </ul>

<h3>4. Connect the SQL Database to Power BI</h3> <ul> <li>Open customer_behavior_dashboard.pbix
</li> <li>Create interactive dashboard in Power BI</li> </ul> <h3>5. Create Project Report and Presentation</h3> <ul> <li>Create project report</li> <li>Build presentation deck using Gamma AI</li></ul>
<h2>📬 Contact</h2>

For any queries:
<strong>LinkedIn:</strong> (https://www.linkedin.com/in/rohan-vij-217036291/)
