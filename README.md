## Key Presentation Principles
- Understand Your Audience: Tailor the detail and complexity based on who will view your reports or dashboards. For distributed or non-technical audiences, include more explanatory text.
- Clear and Effective Graphs/Charts: Choose chart types that best represent your data to maximize clarity.
- Focus on Key Points: Highlight the most critical insights to avoid overwhelming your audience.
- Storytelling: Use a narrative approach to guide your audience through the data logically and compellingly.
- Insightful Dashboards: Design dashboards that not only display data but provide actionable insights.

## Data Visualization
### Column and Bar Charts:
Best for comparing categories or displaying time series data (especially column charts for trends over time).

### Combo Charts:
Combine two chart types (e.g., column + line) to compare related but distinct data series on the same axis.
Stacked column charts stack related data series for visual comparison.

### Waterfall Charts:
Illustrate how sequential positive and negative values contribute to a final total, useful for budget or financial change tracking over time.

## Pre-attentive Attributes
Pre-attentive attributes are visual elements processed instantly by the human brain, helping viewers interpret data faster without conscious effort:
Orientation (horizontal or vertical lines)
- Shape (circles, squares, etc.)
- Length and Width (bar lengths indicate value)
- Color (categorical distinctions or heat maps)
- Enclosure (grouping data through borders or backgrounds)
`to highlight key data points and make dashboards easier to interpret.`

## Why Use Dashboards?
Dashboards enable users to:
- Quickly understand large data volumes via visual summaries
- Track historical performance trends dynamically
- Receive regular updates with fresh data
- Drill down into detailed data models as needed

## Building Dashboards
Power Query’s M Language is essential for advanced data shaping before data reaches your visuals.
Design with interactivity and user experience in mind.

## Microsoft Power Query
Data Types: Correct data typing is essential for accurate calculations and reporting.
For example, numeric columns not used in calculations can be converted to text to prevent errors or unintended aggregations.
`allows transforming,cleaning, and consolidating data efficiently before loading it into the Power BI model.`

## Data Analysis Expressions (DAX)
DAX is the formula language used in Power BI to create custom calculations and aggregations.

### Calendar Table:
Create comprehensive date tables to enable time-based calculations like YTD, MoM, and SPLY. DAX supports adding calculated columns, new tables, and measures.

### Month Over Month (MoM) Variance:
Compares current month’s value to the previous month’s, useful for tracking growth or decline trends.

### Remove Filters:
Use REMOVEFILTERS() or ALL() functions in DAX to calculate overall percentages or totals unaffected by current filter context (e.g., showing each month’s revenue as a percentage of the full year’s revenue).

### Same Period Last Year (SPLY):
Compare data from the current period to the same period last year to identify trends and seasonality.

### Year To Date (YTD):
Aggregate values from the start of the year through the current date, useful for cumulative reporting.

### Forecasting:
Visualizing Measures Forecast on a Line Chart
Apply Power BI’s forecasting capabilities to predict future values based on historical data trends.

## Data Preparation Techniques
### Append Method
Append merges rows from multiple queries or tables, useful for consolidating data from spreadsheets or database tables with similar structures.
Manual Append: Requires manually adding new tables or sheets when data changes.
Automatic Append: More scalable for dynamic data sources that frequently update, automatically including new files or tabs.
### Folder Synchronization
The most efficient method to consolidate multiple data files (e.g., monthly reports).
Power Query can connect directly to folders, automatically combining all files inside.
You can perform data cleaning (such as deleting unwanted rows) before loading.


