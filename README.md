# New Orleans Business License Analysis

## Business Problem
City planners, economic analysts, and local stakeholders often need to understand how business activity changes across time and geography to support ecomonic development decisions

This project analyzes active business license data from New Orleans to identify long-term business growth trends, seasonal patterns, industry concentration and geographic clustering. 


## Key Findings
- Business openings show sustained long-term growth with noticeable year-to-year variation.
- Q4 consistently demonstrates elevated business creation activity.
- Business activity clusters heavily within specific commercial zones and ZIP Codes.
- Vendor and even-related categories experienced significant growth in recent years. 

## Interactive Project
[View Full Interactive Project (GitHub Pages)](https://hcbrooks-lab.github.io/nola_business_license_analysis/)

## Project Snapshot
Analyzed approximately 10,900 business license records from 2000-2025 using Python visualization tools, and geospatial mapping to evaluate business opening trends across New Orleans. 

## Project Overview
This project analyzes active business license records from New Orleans to examine how business activity changes across time, industry categories, and geographic regions. 

Using time-series analysis, category aggregation and geospatial visuals, the project explores where business formation is concentrated and how local business trends evolved between 2000-2025. 

## Key Insights
- Business creation shows long-term growth with noticeable year-to-year
  variation.
- Q4 consistently shows elevated business formation, showing seasonal business
  planning and tourism influence.
- A small number of industries dominate new business registrations.
- New businesses tend to cluster within specific commercial zones and ZIP codes.
- Vendor and event-related business categories experienced notable growth in recent
  years.

## Recommendations
- Monitor commercial zones with growth to better anticipate zoning and infrastructure needs.
- Allocate seasonal permitting resources around elevated Q4 business formation periods.
- Investigate rapidly vendor and event-related categories to support economic planning initiatives. 

## Skills Demonstrated
- Exploratory Data Analysis (EDA)
- Data Cleaning and Transformation (Python/Pandas)
- Time-series Trend Analysis
- Business Category and Industry Analysis
- Geospatial Analysis and Mapping (Folium)
- Data Visualization and Storytelling
- Insights and Business Recommendations 

## Methodology
The analysis followed a data preparation and exploration process:
- Collected active business license records from the City of New Orleans open data portal.
- Cleaned and standardized business, date, and location fields.
- Removed incomplete records and corrected formatting inconsistencies.
- Performed time-series analysis to evaluate long-term business opening trends. 
- Aggregated business categories to identify the most common industries.
- Created geospatial visuals to examine business concentration across the city of New Orleans.
- Developed static and interactive visuals to communicate key findings. 

## Visualizations

### Business Starts Over Time (2000–2025)
This analysis reveals continued long-term growth in business openings across New Orleans, despite periodic year-to-year fluctuations. 
![Business Starts Over Time](docs/images/business_type_trends_over_time.png)

---

### Top 10 Business Types in New Orleans
Business activity is concentrated within a relatively small number of industry categories. Understanding which sectors dominate new registrations can help identify areas of economic strength and opportunities for future development. 
![Top 10 Business Types](docs/images/top_10_business_types.png)

---

### Geographic Distribution of Businesses
Business activity is heavily concentrated within key commercial corridors and ZIP code regions throughout New Orleans. Geographic clustering helps identify areas with stronger commercial presence and highlights where economic development activity is most active. 
![Business Density Map](docs/images/business_density_heatmap.png)

*View the interactive map on GitHub Pages:*  
[Open Interactive Business Density Map](https://hcbrooks-lab.github.io/nola_business_license_analysis/business_density_map.html)

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Folium (Geospatial Analysis)
- VS Code

## Dataset
- Source: City of New Orleans - Active Occupational Licenses
- Records: ~10,900 business license records
- Time Range: 2000-2026
- Analysis Time Range: 2000-2025
- Granularity: Individual business license records


## Limitations & Future Improvements
- Incorporate demographic and economic indicators to better understand factors influencing business growth
- Compare business formation trends with tourism, employment, and economic development data.
- Expand geographic analysis to evaluate business activity at the neighborhood and ZIP code level.
- Conduct deeper industry-specific trend analysis to identify emerging business sectors. 


## Author
H. Brooks

