# Dashboard: Historical Trends in Automobile Sales

This project is a Dash web application designed to visualize and analyze automobile sales data. It provides tools for users to filter and explore data based on date ranges, chart types, and various metrics. The application is built using Dash for web interactivity, Plotly for data visualization, and dash_bootstrap_components for a responsive, attractive design.

## Features:
### Date Range Picker:
- Allows users to filter data by selecting a start date and an end date using a date picker interface. This is useful for focusing on specific periods of time, such as annual trends or quarterly reports.
- **Example**: If you're interested in data from 2015 to 2020, you can simply select these dates.

### Dropdowns:
- **Chart Type**: Users can choose from multiple chart types such as Bubble, Pie, Line, Scatter, and Subplot.
  - **Bubble Chart**: Visualizes data points with size variation, indicating different metrics like revenue or sales count. Useful for identifying relationships between variables.
  - **Pie Chart**: Displays the proportion of different categories (e.g., vehicle types) as segments of a circle, showing their relative sizes.
  - **Line Plot**: Illustrates trends over time, such as sales numbers or advertising expenditure over the years.
  - **Scatter Plot**: Shows the relationship between two variables by plotting them as points on a graph.
  - **Subplot**: Combines multiple charts in a grid layout for a more comprehensive analysis.

### Interactive Charts:
- **Automobile Sales**: Visualize the total revenue from automobile sales. The data is filtered based on the selected date range.
- **Recession Impact**: Analyze the effect of economic recessions on automobile sales. The application provides insights into periods of high or low recession statuses.
- **Vehicle Type Distribution**: Pie chart displaying the distribution of different vehicle types with respect to sales or other metrics.
- **Unemployment Rate**: Examine the relationship between automobile sales and the unemployment rate, providing insights into economic impacts.

### Responsive Design:
- Utilizing Bootstrap ensures the application is visually appealing and works seamlessly across different devices (desktop, tablet, and mobile).

## How to Use:
1. **Select Date Range**:
   - Use the date picker to choose a start and end date for your data analysis. This allows you to focus on a specific time frame, such as a quarter, year, or decade.
   - **Example**: To view sales trends from January 2015 to December 2020, simply select these dates.

2. **Choose Chart Type**:
   - Pick a chart type from the dropdown menu.
     - **Bubble Chart**: Ideal for visualizing sales data with multiple metrics. The bubble size indicates the volume of sales.
     - **Pie Chart**: Perfect for displaying the distribution of vehicle types or other categorical data.
     - **Line Plot**: Best used for seeing trends over time, such as how sales have fluctuated year over year.
     - **Scatter Plot**: Useful for comparing two related variables directly.
     - **Subplot**: Allows for a detailed comparison across different metrics (e.g., sales trends vs. advertising expenditure).

3. **Select Axes**:
   - Choose which columns will represent the X-axis (typically time-related) and the Y-axis (usually a metric like sales or revenue).
   - **X-axis Example**: "Year" or "Month"
   - **Y-axis Example**: "Automobile Sales", "Revenue", "Advertising Expenditure".

4. **Generate the Chart**:
   - Click the "Search" button to generate the chart. The application will display the selected chart type with the filtered data.
   - **Result**: A visual representation that aligns with your choices, helping you to quickly interpret data insights.

## Data Columns:
- **Year**: The year associated with the data entry.
- **Automobile Sales**: The cumulative revenue from automobile sales. It represents the total monetary value of cars sold during a given period.
- **Recession**: Indicators of economic recession status.
- **Vehicle Type**: Different categories of vehicles (e.g., sedan, SUV, truck).
- **Advertising Expenditure**: Amount spent on advertising for promoting vehicles.
- **Unemployment Rate**: Data reflecting the unemployment rate, providing economic context to sales trends.

## Notes:
- Ensure all required columns (`Year`, `Automobile Sales`, `Recession`) are present in the data. If any columns are missing, the application will display an error message.
- The `Automobile Sales` column represents cumulative revenues from car sales, not an average or sum.
- The `Recession` value (e.g., 22) indicates the current economic status. Higher values may suggest a stronger recession impact, while lower values indicate economic stability.
- When choosing a "pie chart" with "Vehicle type" and "Recession," the chart shows the percentage of vehicle types to recession. Ensure these proportions are interpreted correctly, as "22" represents 22% recession impact, reflecting how different vehicle types are affected by economic downturns.
- Ensure your choices (chart type and selected columns) are compatible to avoid unclear or cluttered visualizations.
