Part 3: Regression-Based Business Insights & Model Interpretation

Business scenario
This analysis investigates the factors that influence monthly sales performance across retail stores using regression techniques. The leadership team needs to know which business variables most strongly affect sales to guide decisions on marketing, staffing, inventory, discounting, and regional strategy.

Dataset overview
Dependent variable

monthly_sales

Independent variables

marketing_spend

footfall

avg_discount_pct

staff_count

inventory_availability_pct

competitor_distance_km

holiday_flag

customer_rating

region

store_type

Numerical variables

marketing_spend

footfall

avg_discount_pct

staff_count

inventory_availability_pct

competitor_distance_km

customer_rating

monthly_sales

monthly_profit

Categorical variables

region

store_type

holiday_flag

Data cleaning and preparation

Checked for missing values.

Cleaned customer_rating and competitor_distance_km.

Created dummy variables for region.

Used East as the reference category.

Prepared a regression-ready dataset.

Dummy variables created

Region_North

Region_South

Region_West

Reference category

East

Regression models
Simple regression 1

Dependent variable: monthly_sales

Independent variable: footfall

R² = 0.7363

Simple regression 2

Dependent variable: monthly_sales

Independent variable: marketing_spend

R² = 0.1672

Multiple regression

Dependent variable: monthly_sales

Predictors:

marketing_spend

footfall

inventory_availability_pct

staff_count

clean_customer_rating

holiday_flag

Region_North

Region_South

Region_West

R² = 0.8229

Key findings
The variables with the largest impact on monthly sales are:

Footfall

Marketing spend

Inventory availability

Customer rating

Variables with weak influence

Region_North

Holiday_flag

Final recommendations
Leadership should focus on:

Increasing customer footfall

Improving marketing efficiency

Ensuring inventory availability

Enhancing customer experience

Model conclusion
The multiple regression model delivers the best predictive accuracy, explaining 82.29% of the variance in monthly sales.