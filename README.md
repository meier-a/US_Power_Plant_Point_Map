# U.S. Power Plants Map

## Overview

The **U.S. Power Plants Map** is an interactive web application designed to visualize the distribution of power generation sources across the United States.

The primary objective of this application is to provide users with an engaging platform to understand the geographical distribution and types of power plants in the U.S. By allowing users to filter power plants by energy source and hover over states for detailed information, the map serves as an educational tool for those interested in energy production and environmental issues.

This project was inspired by the New York Times article titled ["Fossil Fuels Are Still Winning: Global Emissions Head for a Record"](https://www.nytimes.com/2024/11/12/climate/fossil-fuel-emissions-2024-record.html), published on November 12, 2024. The article highlights ongoing challenges in reducing fossil fuel emissions and emphasizes the importance of understanding our energy sources.

## Features

- Filter by energy source using a dropdown menu.
- Hover over states to view state-specific information.
- Click on individual power plants to access detailed data, including the plant's name, primary energy source, and the maximum amount of electricity the plant can generate at full capacity, measured in megawatts (MW).

## Data Sources
The following datasets were used in this project:
- **U.S. Energy Information Administration (EIA)**: [Power Plant Data](https://atlas.eia.gov/datasets/eia::power-plants/explore?location=29.746965%2C61.504000%2C2.98)
- **U.S. Census Bureau**: [State Boundary Shapefiles](https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html)

The basemap tiles are provided by [CartoDB DarkMatter](https://carto.com/attributions), and geographic data is sourced from [OpenStreetMap](https://www.openstreetmap.org/copyright).

## Main Packages and Libraries
This application was built using the following key packages:
- **[Leaflet.js](https://leafletjs.com/)**: For interactive map rendering.
- **Google Fonts**: For custom typography (`Titillium Web`).
- **HTML/CSS/JavaScript**: For web development and styling.
