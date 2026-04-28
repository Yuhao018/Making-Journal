---
layout: default
---

# Week 06

[← Back to Home](../index.md)

# In-Class Activities 

## Data Exploration

This project uses three data sources to illustrate the visitor patterns of international tourists to NZ The primary data source is the Infoshare database from Stats NZ. This dataset records the number of inbound tourists from eight major source countries (Australia, China, Japan, South Korea, Germany, the United Kingdom, Canada, and the United States). The data spans from February 2023 to January 2026 and is categorised monthly. Furthermore, the data classifies visitor purpose into three categories: business, holiday/vocation, and visit friends/relatives. Currently, this dataset is presented in the form of a pivot table, with time arranged in rows and countries and purpose in columns and needs to be converted to a flattened format for use in p5.js.

The second dataset contains central location data for each country, including latitude and longitude coordinates. This information was manually collected and organised into a simple CSV file. The third dataset is a world map in GeoJSON format, sourced from https://geojson-maps.kyd.au/, which provides the geographical boundaries used for visualising the data.

The main data has limitations. It only provides data for eight countries, which introduces bias by excluding smaller or under-represented countries.

## Visual Research and Precedent Study

### Tourism (Our World in Data)
![Tourism](../assets/week-06/international-tourist-trips.png)

Arrivals of tourists from abroad, 2024 (Our World in Data, n.d.).

Reference:

Our World in Data. (n.d.). Tourism. https://ourworldindata.org/tourism

This map uses varying shades of blue to represent the differences between countries, making the global tourism landscape clear briefly. I can use these varying colour intensities to reflect differences in the number of tourists. This aligns with my idea of using a world map and prompts me to think more carefully about visual hierarchy.

### Population (Maps)
![Population](../assets/week-06/population.png)

Population 2024 (Gapminder Foundation, n.d.).

Reference:

Gapminder Foundation. (n.d.). Map. https://www.gapminder.org/tools/#$chart-type=map&url=v2

These dynamic bubbles make the data appear lively. I want to represent the data values through the size of the bubbles. I’ll add a time slider interactive feature to perfect my project.

### Dot distribution map

![Berlin](../assets/week-06/berlin.png)

Dot distribution map in Berlin (CARTO, n.d.).

Reference:

CARTO. (n.d.). 80 data visualization examples using location data maps. https://carto.com/blog/eighty-data-visualizations-examples-using-location-data-maps/

I like using circles to represent data size, as this creates a clear visual impact. I’ll use circles placed on countries, with the size of the circle representing the number of visitors. This aligns with my idea of using circular icons rather than solid areas.

### Choropleth map

![Australia](../assets/week-06/australia.png)

A choropleth map that visualizes the fraction of Australians that identified as Anglican at the 2011 census (Wikipedia, n.d.).

Reference:

Wikipedia. (n.d.). Choropleth map. Wikipedia. https://en.wikipedia.org/wiki/Choropleth_map

Colour gradients make data differences stand out clearly. I might use varying colour depths to represent different categories. That makes me think about combining colour with circle size, it might express things more clearly.

### Interactive map dashboards

![New York](../assets/week-06/ny.jpg)

The invisible heartbeat of New York City (Tableau Software, n.d.).

Reference:

Tableau Software. (n.d.). 10 examples of interactive map data visualizations. https://www.tableau.com/learn/articles/interactive-map-and-data-visualization-examples

This temporal interaction allows users to explore data in multiple ways. I’d like to add a hover interaction feature that displays detailed information such as the number of visitors for different purposes and their proportions. I will design the project to be more interactive, rather than a static chart.





## AI Usage Statement

*Document any use of AI tools under an AI Usage Statement heading. Explain which tools you used and describe how you used them. Reference any AI-generated content (see [QuickCite](https://auckland.libguides.com/referencing-generative-ai-tools) for guidance).*
