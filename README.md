# Power BI Project Overview

## Dataset
- **Dataset:** Plant Co's Excel file

## Data Exploration
- **Exploration:**  
  Explored the data’s structure—such as tables, fields, and relationships—and understood the type of information available (e.g., dates, sales figures, product categories).

## Power Query Data Preparation & Transformation
- **Power Query:**  
  Used Power Query to clean and transform the raw data.
  - **Filtering:** Removed unnecessary rows or columns.
  - **Renaming and Formatting:** Standardized column names and data types.
  - **Data Shaping:** Pivoted/unpivoted data to achieve the correct structure.
- **Outcome:**  
  Ensures that the data is reliable and structured appropriately for building the model.

## Virtual Tables Data Modeling
- **Virtual Tables:**  
  Created dynamically (often via DAX) without permanently storing the data in the model.
  - **Benefits:**
    - Simplifies complex calculations.
    - Creates temporary groupings or aggregations.
    - Serves as an intermediary step for building advanced measures.
- **Outcome:**  
  Managed performance and reduced calculation complexity.

## The Model: Building Measures and Core Visuals
- **Data Modeling & Calculations:**
  - **Establishing Relationships:** Defined how tables (e.g., sales fact table and date dimension) relate.
  - **Creating Measures:** Used DAX to calculate key performance indicators (KPIs) such as Total Sales, Year-to-Date (YTD) Sales, or Previous Year Sales.
  - **Core Visuals:** Added basic charts and tables to represent these measures, forming the backbone of the interactive report.
- **Outcome:**  
  Transformed raw data into meaningful business metrics.

## Formatting and Conditional Formatting
- **Enhancing Readability and Insights:**
  - **Consistent Formatting:** Applied themes, color schemes, and fonts to create a cohesive look.
  - **Conditional Formatting:** Highlighted important data points (e.g., flagging high or low sales periods) to draw attention to key insights.
- **Outcome:**  
  Made the report informative, engaging, and easy to read.

## Advanced Visualizations
- **Diverse Visual Perspectives:**
  - **Treemap:** Visualizes data hierarchically, useful for showing parts-to-whole relationships.
  - **Waterfall Chart:** Displays how individual components contribute to a final value, ideal for illustrating sales growth or decline.
  - **Combo Chart:** Combines different chart types (like bars and lines) to compare metrics on a single axis.
  - **Scatter Chart with Zoom Slider:** Provides detailed insights into variable correlations, allowing users to focus on specific data ranges.
- **Outcome:**  
  Helped users understand the data from multiple angles.

## Tidying Up: Dynamic Chart Titles, Axis Titles, Formatting
- **Polishing the User Experience:**
  - **Dynamic Chart and Axis Titles:** Made these elements responsive to filter selections, ensuring that users always see relevant context.
  - **Fine-Tuning Formatting:** Ensured charts and tables align well, with clear labels and a professional design.
- **Outcome:**  
  Enhanced usability and ensured the report effectively communicates its insights.

## Dynamic Report Title
- **Interactive Reporting:**  
  Created a dynamic report title that updates based on filters, reflecting the current view (e.g., “Sales Analysis – Q2 2023”).
- **Outcome:**  
  Immediately informs the user about the context of the displayed data.

## Final Tweaks, Review, and Publish
- **Quality Assurance and Deployment:**
  - **Testing:** Ensured all visuals interacted correctly and all measures returned expected results.
  - **Final Adjustments:** Addressed any remaining design or performance issues.
  - **Publishing:** Published the report to the Power BI Service.
- **Outcome:**  
  Delivered a polished, functional report ready for stakeholder use.
