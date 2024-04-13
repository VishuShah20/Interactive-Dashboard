# Interactive Dashboard for CO2 Emissions

## Overview

This repository hosts an interactive dashboard developed to visualize CO2 emissions globally, leveraging historical data compiled by the OWID (Our World in Data) on CO2 emissions from different countries and continents. Built using Python with libraries such as Panel, hvPlot, and Pandas, this dashboard allows users to explore CO2 emissions trends and their relationship with GDP over time through interactive visualizations.

## Use Case

This dashboard is intended for environmental researchers, policy makers, educators, and anyone interested in understanding the trends of CO2 emissions across different regions and times. It provides valuable insights that can help in making informed decisions regarding environmental policies and understanding the impact of economic activities on carbon emissions.

## Features

- **Interactive Visualizations**: Utilizes hvPlot to generate dynamic graphs that update based on user interactions.
- **Data Filtering**: Allows users to select specific years and CO2 measurement metrics to display relevant data dynamically.
- **Comprehensive Data**: Includes data on CO2 emissions by country, CO2 emissions per capita, and related economic indicators like GDP.
- **Customizable Views**: Users can choose different views and data representations, including line charts for trends, bar charts for comparisons, and scatter plots to correlate CO2 emissions with GDP.

## Getting Started

### Prerequisites

You will need Python 3.8+ installed on your system along with the following Python libraries:
- Pandas
- Numpy
- Panel
- hvPlot
- Jupyter or compatible IPython notebook environment to run `.ipynb` files

## Using the Dashboard
After opening the notebook in Jupyter:

- Execute the cells to start the dashboard.
- Use the interactive widgets such as sliders and radio buttons to filter the data according to year, country, or CO2 metrics.
- View different visualizations like the CO2 emission trends, CO2 vs. GDP scatter plot, and CO2 sources by continent.

## How It Works

1. Data Loading: Data is loaded from OWID's CO2 emissions dataset.
2. Interactive Widgets: Widgets for user interaction are set up using Panel.
3. Data Processing: Data is processed and cached to optimize performance.
4. Visualization: hvPlot is used to create interactive plots that can dynamically update based on widget inputs.

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/interactive-co2-dashboard.git
   cd interactive-co2-dashboard
