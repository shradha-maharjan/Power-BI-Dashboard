# Power-BI-Dashboard
1. Dataset: Plant Co's excel file

2. Data Exploration:
Explored the data’s structure—such as tables, fields, and relationships—and understanding the type of information available (e.g., dates, sales figures, product categories). 

3. Power Query
Data Preparation & Transformation:
Using Power Query, I cleaned and transformed the raw data. Common tasks here include:
	• Filtering: Removing unnecessary rows or columns.
	• Renaming and Formatting: Standardizing column names and data types.
	• Data Shaping: Pivoting/unpivoting data to get it in the correct structure.
Ensures that the data is reliable and structured appropriately for building the model.

4. Virtual Tables
Data Modeling:
Virtual tables are created dynamically (often via DAX) without permanently storing the data in your model. They’re used for:
	• Simplifying complex calculations.
	• Creating temporary groupings or aggregations.
	• Serving as an intermediary step for building more advanced measures.
Managed performance and complexity in your calculations.

5. The Model: Building Measures and Core Visuals 
Data Modeling & Calculations:
Here, I built the data model, which involves:
	• Establishing Relationships: Defining how tables like your sales fact table and date dimension relate.
	• Creating Measures: Using DAX to calculate key performance indicators (KPIs) such as Total Sales, Year-to-Date (YTD) Sales, or Previous Year Sales.
	• Core Visuals: Adding basic charts and tables to represent these measures, which form the backbone of your interactive report.
Transformed raw data into meaningful business metrics.

6. Formatting and Conditional Formatting 
Enhancing Readability and Insights:
Visual appeal and clarity are vital in any report. In this phase, you:
	• Applied Consistent Formatting: Used themes, color schemes, and fonts to create a cohesive look.
	• Conditional Formatting: Highlighted important data points (for example, flagging high or low sales periods) to draw attention to key insights automatically.
This makes the report not only informative but also engaging and easy to read.

7. Advanced Visualizations 
Diverse Visual Perspectives:
To provide deeper insights, I incorporated advanced visuals:
	• Treemap: Visualizes data hierarchically, useful for showing parts-to-whole relationships.
	• Waterfall Chart: Displays how individual components contribute to a final value, ideal for showing sales growth or decline.
	• Combo Chart: Combines different chart types (like bars and lines) to compare metrics on a single axis.
	• Scatter Chart with Zoom Slider: Offers detailed insights into the correlation between variables, with the zoom slider allowing users to focus on specific data ranges.
These visualizations help users understand the data from multiple angles.

8. Tidying Up: Dynamic Chart Titles, Axis Titles, Formatting 
Polishing the User Experience:
In this step, I refined the report by:
	• Dynamic Chart Titles and Axis Titles: Making these elements responsive to filter selections ensures that users always see relevant context (e.g., a title that changes based on the selected time period or region).
	• Fine-Tuning Formatting: Ensuring that charts and tables align well, that labels are clear, and that the overall design is both professional and intuitive.
This enhances usability and ensures that the report communicates its insights effectively.

9. Dynamic Report Title 
Interactive Reporting:
Creating a dynamic report title adds an extra layer of interactivity. For instance:
	• The title can update based on filters, reflecting the current view or focus of the data (such as “Sales Analysis – Q2 2023” when Q2 is selected).
	• This immediately informs the user about the context of the displayed data, reducing ambiguity.

10. Final Tweaks, Review, and Publish 
Quality Assurance and Deployment:
Before publishing, you performed a thorough review:
	• Testing: Ensuring that all visuals interact correctly, all measures return expected results, and all dynamic elements update appropriately.
	• Final Adjustments: Addressing any remaining design or performance issues.
	• Publishing: Then I published the report to the Power BI Service.
