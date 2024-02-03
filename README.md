## World Religions Dashboard with Plotly Dash
### Overview

This repository contains Python scripts for creating a dashboard to visualize global religious demographics over five decades (2010 - 2050). The dashboard utilizes Dash, Plotly, and Pandas for data manipulation and visualization. Users can click on a country on the Choropleth map to view its religious demographics. Dropdown menus allow selection by religious group, region, country, and a slider allows users to explore changes over years for detailed insights. The bar chart displays the population distribution of the top four religious groups (Christians, Muslims, Hindus, and Unaffiliated) over time. 
   

### Features

- **Worldwide Distribution**: Explore the distribution of major religions globally over the years using a choropleth map.
- **Country-specific Analysis**: View the change in religious composition for a specific country with a bar chart.
- **Regional Insights**: Analyze the religious composition of different regions using a polar bar chart.


### Dependencies

- `plotly`
- `dash`
- `dash-bootstrap-components`
- `pandas`
- `seaborn`
- `matplotlib`
- `numpy`


### Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/ariyadmir/religious-composition-dashboard.git
    ```

2. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the main script:

    ```bash
    python world-religions-dash.py
    ```

4. Open your web browser and navigate to `http://127.0.0.1:8050/` to interact with the dashboard.

### Note

- The dashboard uses external datasets for religious demographics, ISO codes, and geographical coordinates.
- The EDA can be viewed using the ipython notebook.

### Acknowledgments

- [Pew Research Center](https://www.pewresearch.org/)
- [ISO 3166 Countries with Regional Codes](https://github.com/lukes/ISO-3166-Countries-with-Regional-Codes)
- [Countries Codes and Coordinates](https://gist.github.com/tadast/8827699)
