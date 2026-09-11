# superstore_data
🗂️ Dataset

The analysis uses the Tableau Sample Superstore dataset.

The dataset represents a fictional retail business and contains transaction-level information such as:

Order Date
Region
Category
Sub-Category
Sales
Quantity
Discount
Profit
Customer
Order

Source: Tableau Sample Data

🎯 Project Objectives
Analyze overall sales and profitability.
Identify sales growth trends over time.
Compare category-level performance.
Analyze regional sales and profit.
Identify profitability gaps.
Convert analytical findings into business recommendations.
Present the findings as a clear visual story.
📈 Executive KPIs
KPI	Result
Total Sales	$2.30M
Total Profit	$286.4K
Profit Margin	12.47%
Quantity Sold	37,873
Orders	9,994
Customers	793
🔍 Key Insights
1. Sales growth accelerated

Sales increased from approximately $484.2K in 2014 to $733.2K in 2017, representing approximately 51.4% growth across the period.

2017 sales were approximately 20.4% higher than 2016.

Business implication: The business has a strong growth trajectory, creating an opportunity to improve the profitability of that growth.

2. Technology is the main profit engine

Technology generated approximately:

$836.2K sales
$145.5K profit
17.4% profit margin
50.8% of total profit

Business implication: Technology should remain a priority for inventory availability, customer targeting, and regional expansion.

3. Furniture has a major profitability gap

Furniture generated approximately $742.0K in sales, representing about 32.3% of total sales, but generated only $18.5K in profit.

Its profit margin is approximately 2.5%.

Business implication: Furniture should be investigated for pricing, discounting, sourcing, and product/sub-category economics rather than evaluated using sales alone.

4. West is the strongest region

The West region generated the highest sales and profit in the analyzed regional summary.

Business implication: Successful practices in the West can be examined and potentially replicated in lower-performing regions.

5. Central Furniture is a specific loss-making combination

Central-region Furniture generated approximately -$2.9K profit, while West Furniture remained profitable.

Business implication: The Furniture problem is not necessarily uniform across the company. Regional execution, discounting, product mix, and operating conditions should be investigated before applying a blanket category strategy.

📊 Visual Story

The presentation contains six slides:

Executive Overview — business KPIs and central question
Growth Trend — annual sales trajectory
Category Economics — sales vs. profit contribution
Regional Performance — regional sales and profitability
Diagnosis — Central Furniture loss and regional-category comparison
Action Plan — practical 90-day recommendations
💡 Recommendations
01 — Protect the profit engine

Maintain strong availability and customer focus for Technology while studying the practices of high-performing regions.

02 — Fix Furniture economics

Analyze Furniture by sub-category, product, discount level, supplier, and region.

03 — Manage discounts by margin

Introduce controls or approval thresholds for orders where high discounts significantly reduce profitability.

04 — Build a management dashboard

Track:

Sales
Profit
Profit Margin
Category
Region
Discount
Quantity
Customer/Order trends

The dashboard should allow management to move from company-level performance → region → category → product.

🛠️ Tools & Skills

Tools

Microsoft PowerPoint
Microsoft Word
Tableau / Power BI compatible analytical workflow
Python
Pandas
Matplotlib
GitHub

Skills Demonstrated

Exploratory Data Analysis
KPI Analysis
Data Aggregation
Trend Analysis
Profitability Analysis
Data Visualization
Business Storytelling
Insight Generation
Business Recommendations
Documentation

🧮 Reproducibility

The repository includes analysis.py containing the core aggregation logic.

For a full row-level reproduction, place the Sample Superstore CSV in the project directory and run:

python analysis.py

The analysis calculates:

Overall KPIs
Annual sales and YoY growth
Category sales/profit/margin
Regional sales/profit/margin
🚀 Future Improvements

A next version could add:

Discount vs. profit analysis
Sub-category profitability
Product-level loss analysis
State and city profitability
Segment profitability
Shipping mode analysis
Customer profitability
Interactive Power BI dashboard
Tableau dashboard with filters and drill-downs
👩‍💻 Author

Ritika Mishra
Data Analytics Intern

Project

Task 4 — Data Visualization and Storytelling

Turning structured data into a business story and actionable decisions.

⭐ Project Takeaway

The most important lesson from this project is:

High sales do not automatically mean high business value.

A strong analyst connects growth, profitability, product mix, and geography to determine where the business should act next.
