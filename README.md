
The notebook `DelhiMetro_Analysis.ipynb` contains an analysis of the Delhi Metro system, including data visualization and mapping. The analysis uses several libraries such as Pandas for data manipulation, Folium for mapping, and Plotly for interactive visualizations. The code involves reading data from a CSV file, cleaning and transforming the data, and then creating visual representations to analyze various aspects of the Delhi Metro system.

The code is the creation of an interactive map using Folium, which visualizes the locations of Delhi Metro stations with color-coded markers based on the metro lines they belong to. Here's an explanation of this functionality:

1. **Data Loading and Preparation:**
   - The data is read from a CSV file and stored in a DataFrame.
   - Missing values and data types are checked and adjusted as necessary.
   - A dictionary is created to map metro lines to specific colors.

2. **Interactive Map Creation:**
   - A Folium map is initialized with the geographical center of Delhi.
   - For each metro station in the dataset, a marker is added to the map:
     - The marker's location is set using the station's latitude and longitude.
     - A popup and tooltip provide information about the station name and the line it belongs to.
     - The marker's color is determined by the line it represents, using the predefined color dictionary.

3. **Visualization:**
   - The map is rendered to visually display all metro stations in Delhi, color-coded by line, providing an intuitive way to understand the geographical distribution and the extent of the metro network.

This interactive map helps users quickly identify the location and line association of each metro station in Delhi, enhancing the overall analysis by adding a spatial dimension to the data.
