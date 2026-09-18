# Sales-Insights-Dashboard
## Dashboard Link : https://app.fabric.microsoft.com/groups/4a76293a-f3ad-4ceb-8a65-e2a3318f5878/reports/e8a02764-238d-4234-abad-c706e980ad83/cbd89ee1c9a98b16fbe5?experience=fabric-developer

## Problem Statement
This dashboard provides insights into retail brand performance by analyzing sales, discounts, profit margins, and product variety. It helps businesses identify top-performing brands, track profitability, and optimize discount strategies. By combining cloud-based data pipelines with Power BI analytics, the dashboard enables data-driven decision-making for retail growth.

## Steps followed
 - Step 1 : Uploaded dataset into Microsoft Azure Cloud.

 - Step 2 : Performed data cleaning using Azure SQL queries (handled nulls, standardized brand names, removed duplicates).

 - Step 3 : Connected the cleaned dataset to Power BI Service through a Dataflow.

 - Step 4 : Configured the Dataflow to refresh and transform the dataset, ensuring reusable and scalable pipelines.

 - Step 5 : Connected the Dataflow output into Power BI Desktop for report building.

 - Step 6 : Created DAX measures to calculate KPIs such as average discount %, profit %, sales price, and product variety.

 - Step 7 : Designed multiple visuals:

   - Top 5 Brands by Average Discount %

   - Top 5 Brands by Average Profit %

   - Top 5 Brands by Highest Number of Varieties

   - Top 5 Brands by Average Sales Price

   - Bottom 5 Brands by Average Profit %

 - Step 8 : Added slicers for filtering by Brand, Category, and Region.

 - Step 9 : Inserted text boxes for project title and company tagline.

 - Step 10 : Styled the dashboard with a professional theme and published it to Power BI Service.

## Snapshot of Dashboard (Power BI Service)
<img width="960" height="540" alt="Image" src="https://github.com/user-attachments/assets/c0e30fa2-5fa0-4945-90cf-50cfa3b43271" />

<img width="960" height="540" alt="Image" src="https://github.com/user-attachments/assets/71b3335f-5685-4c77-b10a-551aebdb4179" />

## Insights
A single-page report was created in Power BI Desktop and published to Power BI Service.

Following inferences can be drawn from the dashboard:

### [1] Discounts
Brands like iVOC (89%) and Voroxy X AG (85%) offer the highest average discounts.
 Indicates aggressive discount strategies to attract customers.

### [2] Profitability
Brands such as JOVEN, SHOWOFF, and URBANAUT lead with ~17% average profit margin.
 These brands balance pricing and profitability effectively.

### [3] Product Variety
The Indian Garage Co (51 varieties) and U.S. Polo Assn. (44 varieties) dominate in product diversity.
 Higher variety correlates with stronger market presence.

### [4] Sales Price
Premium brands like Armani Exchange (6.1K) and Brooks Brothers (5.1K) have the highest average sales prices.
 Indicates positioning in the luxury segment.

### [5] Low Profit Brands
Brands such as Qumash Fashion, Maniac, and Colorplus show the lowest profit percentages (~2%).
 Suggests need for pricing or cost optimization.
