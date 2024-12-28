Overview
This project is an interactive data visualization web application built using Python, Dash, and Plotly. It enables users to explore and analyze earthquake data retrieved from the IRIS seismic data service. Users can dynamically adjust the year range and minimum magnitude, interact with scatter plots and bar charts, and highlight specific data points or time periods for deeper insights.

Features
- Interactive Year Range Selection: Adjust the year range using a slider to filter earthquake data.
- Minimum Magnitude Filtering: Set a minimum magnitude threshold to view significant seismic events.
- Scatter Plot of Earthquake Locations: Visualize earthquake locations on an interactive world map with markers sized by magnitude and colored by depth.
- Bar Chart of Earthquake Frequency: Analyze earthquake frequency over time grouped by months.
- Click-Based Highlighting:
  Select a time period from the bar chart to highlight corresponding earthquakes on the map.
  Click a specific earthquake on the scatter plot to highlight related time periods in the bar chart.
-Error Handling for Large Data Fetches: Prevent crashes by limiting large data fetches and displaying error messages.

Technologies Used
- Dash: For building the web application and handling interactive components.
- Plotly: For creating interactive and visually appealing charts (scatter plot, bar chart).
- pandas: For efficient data manipulation and analysis.
- IRIS Web Service Client: To fetch real-time earthquake data from the IRIS seismic data service.
- Bootstrap: For responsive and aesthetically pleasing UI styling.
