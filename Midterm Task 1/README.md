# Midterm Lab Task 1 - Data Cleaning and Preparation using Excel
In this activity, we cleaned an excel sheet fill of errors and redundancy using different excel features.
## Step by step
# Identify Dirty Data
Spot missing values (e.g., blank revenue, payment).
Fix errors (like #DIV/0! in profit margin).
Standardize names (contacts, departments).

# Map IDs to Real Entities
Match Client_id, Department_id, State_id, Payment_id with actual names from the first sheet.
This ensures consistency across datasets.

# Clean Values
Replace blanks with correct numbers or mark them as NULL.
Recalculate profit margin = (Profit ÷ Revenue) × 100.

# Aggregate Data
Compute totals: revenue, profit, average profit, average margin.
Group by state and client for comparisons.

# Visualize
Bar chart: Top 5 clients by revenue.
Bar chart: Revenue per state.
Pie chart: Revenue per month (May vs June).

## Build Dashboard
Display KPIs (total revenue, total profit, average margin).
Add charts for quick insights.
Highlight Texas as top state and May as top month.
## Step 3 Before
![screenshot](/Midterm%20Task%201/Images/Before.png)

## Step 4 After
![screenshot](/Midterm%20Task%201/Images/After.png)

## Here's the Physical Data Model
![screenshot](/Midterm%20Task%201/Images/Relation.PNG)
