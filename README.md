# Healthcare Dashboard

## Problem Statement

The goal of this project was to create an interactive Power BI dashboard to analyze patient waitlists and associated metrics. The dashboard needed to provide insights into various key performance indicators (KPIs) such as total waitlists, case types, specialty performance, and trends over time. Additionally, the dashboard had to allow for easy exploration of granular data through interactive features like slicers, drill-through options, and dynamic filtering.

## Conclusion

I developed a two-page Power BI dashboard to address the business needs of tracking patient waitlists effectively. Below are the key steps and technical decisions that contributed to the success of this project:

### 1. **Data Import and Transformation**
   - Imported structured data from Excel files, ensuring consistency across multiple data sources.
   - Cleaned and transformed the data using Power Query, validating data types, renaming columns, and applying necessary transformations.
   - Documented the entire data transformation process in Power Query for transparency.

### 2. **Data Modeling and Design**
   - Designed a data model with well-structured relationships and ensured optimal performance by eliminating unnecessary columns.
   - Applied efficient DAX measures to dynamically calculate aggregates such as totals and averages based on user inputs.
   - Ensured that all data transformations and model changes aligned with the business goals, particularly in tracking patient waitlists and specialties.

### 3. **Dashboard Design and Layout**
   - Designed a user-friendly layout with a clear distinction between summary-level and granular data views.
   - The summary page included:
     - Key metrics such as total waiting list counts for the current and previous months.
     - Visualizations such as pie charts, column charts, and a trend analysis over time.
   - The detailed page provided deeper insights with advanced visualizations such as:
     - A matrix displaying case types and metrics.
     - Filters and slicers for interactive exploration of the data.

### 4. **Interactivity and User Experience**
   - Incorporated slicers, filters, and drill-through options to enhance interactivity.
   - Enabled dynamic updates with DAX formulas, ensuring all visuals responded to filter selections and updated in real-time.
   - Designed dynamic titles and "No Data" messages using DAX to improve user clarity when filtering data.

### 5. **Data Quality and Optimization**
   - Identified and resolved data quality issues, such as inconsistent values in the "time band" column (e.g., “18 months plus” vs. “18+ months”) during data cleaning.
   - Used Power Query's transformation tools to standardize these values, improving chart accuracy and consistency.
   - Optimized the dashboard's performance by removing unnecessary columns and applying efficient DAX measures to minimize processing time.

### 6. **Testing and Sharing**
   - Conducted thorough testing to verify data accuracy and responsiveness of all visualizations.
   - Published the final dashboard on Power BI Service, ensuring appropriate access control and permissions for stakeholders.

### 7. **Routine Data Refresh and Maintenance**
   - Set up automated data refresh schedules to ensure the dashboard remained up-to-date with the latest data.
   - Verified data connectors and automated the refresh process, ensuring seamless updates without manual intervention.

By following these steps, I successfully delivered a comprehensive and efficient dashboard that empowered stakeholders to make data-driven decisions regarding patient waitlists and specialties.

## Key Technologies Used
- **Power BI**: Dashboard development, data transformation, and visualization
- **DAX**: Data analysis expressions for dynamic calculations and measures
- **Power Query**: Data cleaning, transformation, and optimization
