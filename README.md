Electric Vehicle Market
Performance & Insights
Project Documentation

Project Title
Electric Vehicle Market Performance & Insights
Dashboard Name
EV Market Lens
Project Member
Individual
Date
28-10-2026
Tool Used
Tableau Public

Data Analytics with Tableau

About This Document
This report documents the Tableau project “Electric Vehicle Market Performance & Insights,” built as the EV Market Lens dashboard. It follows the structure of the supplied reference report and describes the dashboard’s nine views, dataset context, preparation approach, dashboard composition, validation considerations, publishing details, and learning outcomes.
The dashboard photograph was used only as a visual reference. Individual chart figures in this document have been recreated as clean, separate graphics rather than inserting the photograph of the laptop screen. Where labels were too small to read reliably, the report identifies values or visuals as approximate/illustrative instead of presenting them as verified facts.
1. Problem Statement
1.1 Introduction and Background
Electric vehicles are becoming an important part of the transportation market as manufacturers develop different vehicle categories, battery technologies, driving ranges, and pricing options. A dashboard can bring these market indicators together so users can compare patterns without manually inspecting individual records.
1.2 Problem Statement
EV market information can be difficult to interpret when vehicle categories, manufacturer sales, battery specifications, customer ratings, environmental indicators, and model years are examined separately. This project uses Tableau visualisations to organise these indicators into a single dashboard for exploratory analysis.
1.3 Objectives
    • Summarise EV records by battery type and vehicle category.
    • Compare annual sales across manufacturers and model years.
    • Explore average driving range and battery capacity by battery type.
    • Review customer ratings and average CO₂-saving indicators by category.
    • Visualise EV records by manufacturing country and compare average price with range.
    • Combine nine individual views into one dashboard named EV Market Lens.
1.4 Scope of the Project
The scope is descriptive dashboard analysis based on the views visible in the supplied Tableau screenshot. Predictive modelling, causal claims, and formal statistical testing are not claimed.
1.5 Intended Users and Their Needs
    • Students and learners exploring EV market indicators.
    • Analysts who need a visual overview of battery types, sales, range, ratings, and sustainability-related measures.
    • Reviewers who need clearly titled charts and a concise explanation of what each view is intended to show.
2. Dataset
The dashboard displays fields and measures related to EV records, battery type, manufacturer, vehicle category, average range, customer rating, manufacturing country, average price, CO₂ savings, battery capacity, annual sales, and model year. The exact source filename, row count, date of extraction, and complete field definitions were not readable in the supplied screenshot and should be confirmed from the Tableau Data Source page.
2.1 Visible Fields and Their Uses
Field / measure
Dashboard view
Purpose
Battery Type
EVs by Battery Type; Range by Battery Type; Battery Capacity by Type
Compare records and battery-related performance indicators.
Manufacturer
Sales by Manufacturer
Compare annual sales units across manufacturers.
Category
Rating by Category; CO₂ Saving by Category
Compare category-level customer and environmental indicators.
Manufacturing Country
EV Records by Manufacturing Country
Show the geographic distribution of records.
Average Price and Range
Price vs Range
Explore how price and driving range vary across records.
Model Year and Annual Sales
Annual Sales by Model Year
Review the visible sales trend across model years.
Important: confirm the exact dataset name, units, field types, and aggregation rules in Tableau before submission. Some chart labels in the provided screen photograph are small, so the recreated figures flag uncertain values accordingly.
3. Data Preparation
    • The dashboard uses a common EV dataset across its visible worksheets.
    • Battery type, manufacturer, category, and manufacturing country are used as dimensions for grouping records.
    • Range, customer rating, price, CO₂ saving, battery capacity, and annual sales are shown as measures.
    • Model year is used as the horizontal axis in the annual sales trend.
    • The exact handling of missing values, duplicate records, calculated fields, filters, and data relationships cannot be verified from the dashboard photograph and should be documented from the workbook if required.
4. Data Visualizations
Nine dashboard views are visible. Each figure below is provided separately, in a clean report-ready format, with a caption and a short explanation. Some values that could not be read clearly from the photograph are explicitly identified as approximate or illustrative.
4.1 EVs by Battery Type

Figure 1. EV records by battery type.
The chart compares the counts shown for NMC, LFP, NCA, Sodium-ion, and Solid-state battery types. In the visible labels, NMC and LFP have the largest counts among the listed types.
4.2 Sales by Manufacturer

Figure 2. Annual sales units by manufacturer.
This view compares the manufacturers shown in the dashboard. The reconstructed bar lengths reflect the relative pattern visible in the photo; exact manufacturer values should be checked in Tableau.
4.3 Average Range by Battery Type

Figure 3. Average driving range by battery type.
The chart compares average range across the five battery types. The visible labels are close to 321–325 km, with Solid-state shown lower than the other listed types.
4.4 Average Customer Rating by Category

Figure 4. Average customer rating by vehicle category.
This view compares average customer ratings across categories. The recreated values are approximate because the original labels were small; use the Tableau worksheet for exact values.
4.5 EV Records by Manufacturing Country

Figure 5. Geographic view of EV records by manufacturing country.
The original dashboard uses a map to communicate the distribution of records by manufacturing country. The figure here is a clearly labelled schematic summary, not a replacement for the exact map or its counts.
4.6 Price vs Range

Figure 6. Price compared with driving range.
The original view is a scatter plot with average range on the horizontal axis and average price in USD on the vertical axis. The supplied photo does not make individual point values legible, so this clean figure is an illustrative guide only.
4.7 Average CO₂ Saving by Category

Figure 7. Average CO₂ saving by vehicle category.
This chart compares the category-level CO₂-saving measure. Labels are approximate transcriptions from the dashboard image; confirm the measure's units and values in the workbook.
4.8 Average Battery Capacity by Type

Figure 8. Average battery capacity by battery type.
The displayed averages are around 78 in the dashboard’s stated measure. The original axis indicates kWh; confirm the field aggregation and precision in Tableau.
4.9 Annual Sales by Model Year

Figure 9. Annual sales trend by model year.
The original view shows a mostly stable trend with fluctuations from 2018 through 2026. Because exact point values were not legible, the plotted series is illustrative and should not be used as a source of exact sales figures.
5. Dashboard
The EV Market Lens dashboard brings the nine views together on one Tableau canvas. The supplied screenshot shows a grid-style layout with category and manufacturer comparisons at the top, battery and rating measures in the upper and middle areas, and price/range, CO₂ saving, battery capacity, and annual sales views across the remaining space.
5.1 Composition and Layout
    • Bar charts make category and manufacturer comparisons easy to scan.
    • The range and battery-capacity views support comparison across battery types.
    • The geographic map adds a spatial overview of manufacturing-country records.
    • The scatter plot supports exploration of price and driving range.
    • The annual sales line chart gives a time-based view of the displayed model years.
5.2 Functionality
The screenshot confirms that the views are assembled in a Tableau dashboard. Interactive filter actions, tooltips, highlight actions, and dashboard navigation are not sufficiently evidenced by the screenshot and should only be described if verified directly in the workbook.
5.3 Design Observations
    • The dashboard uses consistent blue-toned marks across many views.
    • Several charts include data labels, helping readers compare values quickly.
    • Long category labels may need improved spacing or rotation for readability.
    • The geographic view and scatter plot should retain clear legends and axis titles.
    • Confirm that all nine views remain legible at the intended dashboard size.
6. Story
A separate Tableau Story was not visible in the supplied evidence. If the course requires a Story, a suggested sequence is provided below; it is a recommendation, not a claim that a Story has already been created.
Scene
Suggested caption
View
1
EV market overview
Dashboard
2
Battery types and driving range
EVs by Battery Type; Range by Battery Type
3
Manufacturer sales comparison
Sales by Manufacturer
4
Customer and sustainability indicators
Rating by Category; CO₂ Saving by Category
5
Price, capacity, and annual sales patterns
Price vs Range; Battery Capacity; Annual Sales
7. Performance Testing
7.1 Data Consistency Checks
    • Verify that each view uses the intended measure and aggregation (for example, sum, average, or count).
    • Check that the manufacturer sales values match the source data and expected units.
    • Confirm the range and battery-capacity units, rounding, and null handling.
    • Compare map marks with the underlying manufacturing-country records.
    • Recheck labels and axis formats after publishing or resizing the dashboard.
No measured load time, workbook performance benchmark, or formal test result was visible in the supplied evidence. Those values have therefore not been invented.
8. Web Integration
No evidence of a Flask application or embedded Tableau view was supplied. If web integration is required by the course, complete this section after implementation.
Item
Details
Framework / template used
To be completed if applicable
Pages or routes created
To be completed if applicable
Local address tested
To be completed if applicable
Screenshot of embedded view
Insert after implementation, if required
9. Publishing and Project Links
Add the final links after publishing the workbook and preparing the project repository or demo. Do not submit placeholder text as if it were a live link.
Item
Link
Tableau Public workbook
To be added
GitHub repository
To be added
Demo video
To be added
10. Conclusion and Learnings
10.1 Conclusion
The Electric Vehicle Market Performance & Insights project brings together nine Tableau views in the EV Market Lens dashboard. The views cover battery-type records, manufacturer sales, driving range, customer ratings, manufacturing-country distribution, price versus range, CO₂-saving indicators, battery capacity, and annual sales by model year. Together, they provide a visual starting point for exploring EV market information.
10.2 What Was Learned
    • Creating and arranging multiple worksheets in a single Tableau dashboard.
    • Choosing chart types for categorical comparisons, geographic distribution, relationships, and time trends.
    • Using labels, axes, legends, and layout to improve chart readability.
    • Checking units, aggregation, and data quality before drawing conclusions.
    • Separating verified observations from estimates when source evidence is unclear.
10.3 Limitations
    • Some labels in the supplied dashboard photograph were too small to read with confidence.
    • The manufacturer, category, and annual-sales chart values should be confirmed from the Tableau workbook.
    • The country visual is represented by a schematic in this document because exact country counts were not legible.
    • The Price vs Range and Annual Sales figures are illustrative reconstructions, not verified point-level data.
    • Story, web integration, publishing links, and performance measurements require confirmation if they are part of the final submission.
