Overview
This project explores how urbanization has influenced population density near rapid transit systems globally. By using a variety of visualizations, it provides insights into the relationship between urbanization and transit accessibility over time.

The primary focus is on urban planners, transport authorities, researchers, and the general public, offering interactive tools to analyze trends from 1975 onward. The visualizations provide a spatial, temporal, and comparative view of the data.

Live Demo
Check out the live version of the visualization:
Urbanization Future with Transit Access

Repository Contents
This repository contains all the files necessary for the data visualizations, including:

index.html: The main HTML page that renders the dashboard.
dashboard-styles.css: Custom CSS styles for the dashboard layout and dark mode toggle.
Visualization JSONs:
visualization.vg.json: The Vega specification for the map and line chart visualizations.
visualization.vl (1).json: Vega-Lite specification for the bubble chart visualization.
visualization.vl (2).json: Vega-Lite specification for the heatmap visualization.
visualization.vl (3).json: Vega-Lite specification for the violin plot visualization.
visualization.vl (4).json: Vega-Lite specification for the parallel coordinates plot visualization.
visualization.vl (5).json: Vega-Lite specification for the top 10 countries’ rapid transit data.
5ds.pdf: Five Design Sheets detailing the design process and decisions behind this project.
Data Source
All data used in this project is sourced from atlas.itdp.org, which provides comprehensive data on global urbanization and transit access.

Features
Interactive Visualizations: Each visualization is interactive, allowing users to hover, click, and explore the data in-depth.
Dark Mode: Toggle between light and dark modes for better readability based on user preference.
Data Filtering: Users can filter by year, region, and transport type to customize their view of the data.
Visualizations
The dashboard consists of the following visualizations:

Line Chart: Shows trends in people near rapid transit systems over time for the top 10 countries.
Geographic Map: Displays global transit access, allowing users to explore transit proximity by country.
Bubble Chart: Visualizes the size of populations near rapid transit over time.
Heatmap: Displays ridership intensity across different years, showcasing peaks in transit access.
Violin Plot: Compares ridership distribution across various countries.
Parallel Coordinates Plot: Visualizes relationships between urban infrastructure indicators, such as population density and transit coverage.
Getting Started
Prerequisites
Web browser with JavaScript enabled.
Internet connection to access live data and visualizations.
Basic understanding of Vega-Lite and JSON (for developers looking to modify the visualizations).
Running Locally
Clone the repository:
git clone https://github.com/jarelgomes1/atlasitdp.git
Open index.html in a web browser to view the visualizations locally.
Optionally, modify the visualization.vg.json or Vega-Lite files to experiment with different data visualizations.
Future Enhancements
Live Data Feeds: Integrating real-time data to keep visualizations up-to-date.
Additional Filters: Adding more granular filters for deeper exploration (e.g., filtering by specific cities or transit systems).
Expanded Analysis: Incorporating other indicators like CO2 emissions, economic impact, or transit affordability.
Contributing
Contributions are welcome! If you have any suggestions for improvements or new features, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License.
