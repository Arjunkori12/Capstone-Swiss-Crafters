# Capstone-Swiss-Crafters
Swiss Crafters Inventory Visualization

Project Overview

This Power BI project, Swiss Crafters Inventory Visualization, is an inventory monitoring system for managing 3,000 Swiss luxury watches (Omega Seamaster Diver 300M, Longines Master Collection, Tissot PRX, Hamilton Khaki Field, Swatch Sistem51) imported annually from Biel/Bienne, Switzerland, to a retail store in Montreal, Canada. The dashboard visualizes the shipment route, monthly sales trends, and inventory levels, enabling efficient supply chain management by tracking stock depletion and identifying reorder needs.

Objectives
-Track the inventory of 3,000 watches, with 1,500 imported in Q1 (Jan 1, 2025) and 1,500 in Q3 (Aug 1, 2025).
-Visualize monthly sales (~250 watches/month) across five watch models to analyze demand patterns.
-Monitor inventory levels to prevent stockouts, using a reorder threshold (20% of annual units per model).
-Display the shipment route from Switzerland to Montreal to contextualize the supply chain.

Data Sources
-Inventory Plan: Details annual units (3,000 total), Q1/Q3 imports (1,500 each), and costs ($4.35M total) for five watch models.
-Sales Data: Monthly sales (e.g., 33–34 units for Omega, 83–84 for Tissot) summing to 3,000 annually, with calculated revenue and COGS (50% markup).
-Inventory Timeline: Monthly inventory levels, accounting for imports and sales (e.g., Omega drops to 2 units by Jul, replenished to 169 in Aug).
-Shipment Route: Coordinates for Biel/Bienne (47.1402, 7.2461) and Montreal (45.5088, -73.5534).

Key Features
-ArcGIS Map: Visualizes the shipment route from Biel/Bienne, Switzerland, to Montreal, Canada, highlighting the supply chain origin and destination.
-Monthly Sales Line Chart: Displays sales trends for each watch model (e.g., Tissot peaks at 84 units in Nov), enabling demand analysis.
-Inventory Levels Stacked Area Chart: Tracks stock levels (e.g., 1,500 units in Jan, 252 by Jul, 1,752 post-Q3), with a 300-unit threshold for visual alerts.
-Inventory Value Line Chart: Shows monetary value (e.g., ~$2.175M post-Q1 import), aiding financial planning.
-KPI Cards: Summarize total capacity (3,000), Q1/Q3 imports (1,500 each), and current stock.

Repository Contents

+ SwissCraftersInventoryVisualization.pbix: Power BI project file with the interactive dashboard.
+ SwissCraftersInventoryVisualization.pptx: PowerPoint presentation with static visuals (map, sales chart, inventory chart, KPIs).

Data Files:

+ Sales Assumption and Inventory Plan : Monthly sales, revenue, COGS, units, imports and costs also Coordinates for shipment route.

+ InventoryTimeline.xlsx: Monthly inventory levels and values.

+ Capstone.docx: Word document detailing project methodology, data preparation, and insights.

Technical Details

+ Tools Used: Power BI Desktop, Power Query, Excel.
+ Data Preparation: Used Power Query to transform and clean data from Excel files, ensuring accurate sales and inventory calculations.
+ Data Modeling: Created relationships between InventoryPlan, SalesAssumption, InventoryTimeline, and ShipmentOrigin tables, with a DateTable for time intelligence.
+ Visualizations: ArcGIS Map, Line Chart, Stacked Area Chart, KPI Cards.

Skills Demonstrated: Data visualization, data modeling, Power Query ETL, supply chain analytics, Power BI development.

Key Insights

Shipment Route: Watches are shipped from Biel/Bienne to Montreal, visualized for supply chain clarity.

Sales Trends: Tissot and Hamilton drive sales (83–84 units/month), with a peak in Nov (254 units total).

Inventory Dynamics: Stock drops to 252 units by Jul 2025, replenished to 1,752 post-Q3 import. Omega and Longines approach reorder thresholds (80 units) in Jun–Jul.

Financial Impact: Inventory value peaks at ~$2.175M post-imports, supporting cost management.

How to View

Interactive Dashboard: Download SwissCraftersInventoryVisualization.pbix and open in Power BI Desktop (requires a Power BI account).
Static Visuals: View SwissCraftersInventoryVisualization.pptx for screenshots of the dashboard.
Data: Explore *.xlsx files for raw data.

Documentation: Read Capstone.docx for detailed methodology.

Future Improvements
Incorporate predictive analytics for sales forecasting using Power BI’s built-in tools.
Integrate real-time sales data via Power BI dataflows.
Enhance map with shipment logistics details (e.g., transportation modes).

Contact

Connect with me on LinkedIn for feedback or collaboration. Visit the live demo on GitHub Pages!

 #PowerBI #DataVisualization #InventoryManagement #BusinessIntelligence #DataAnalytics
