In this project, I worked with a Sentinel-2 data cube containing only raw spectral bands. The main objective was to process this data to create a new layer representing the Normalized Difference Vegetation Index (NDVI), which could be used for map and time series visualization.

### Materials
I used the following resources to complete the task:
- A netCDF file containing the Sentinel-2 data cube.
- A GeoJSON file defining a sub-area of interest (sub-AOI).

### Deliverables
Here are the deliverables I produced to meet the project requirements:

1. **Jupyter Notebook**: I developed a comprehensive Jupyter notebook that covered the entire process, including:
   - **Data Processing and Visualization**: Opening, exploring, and visualizing the geospatial data.
   - **Calculation of NDVI**: I computed the NDVI for each date in the data cube and added it as a separate data layer.
   - **Visual RGB Image**: I generated a color visualization (RGB) for a selected date.
   - **Histogram of NDVI Pixels**: I created a histogram to show the distribution of NDVI pixel values.
   - **NDVI Time Series**: I developed a time series displaying the average NDVI over the area of interest (AOI) for each given date.

2. **NDVI Visualization Clipped to Sub-AOI**: In addition to the above, I created a visualization of the NDVI layer clipped to the provided sub-area of interest. This visualization helps to focus on a specific region within the broader AOI, providing more detailed insights.
