# Earth_361_Final_Project
Is Chicago Going Green? - An Assessment of Green Roof Development in Chicago Over Time

## Welcome to my Final Project! 

NOTE: Before you begin, make sure that your Google account is registered with Google Earth Engine - otherwise, this code will not work. 


## To Do (Before Running the Code):
- Download all necessary supporting files
- I could not figure out how to alter the file paths to a web-based environment, so all necessary file paths will need to be readjusted to YOUR Computer
- Run "Neighborhood Analysis.ipynb" & "Landsat Imagery Analysis.ipynb" in a Jupyter Notebook

### Extra: 
Major Bugs Encountered:
1 - Initially, I started this project in Google Colab, however, the folium library stopped working properly for an unknown reason and would not display tiles with such large amounts of data, so I switched to Jupyter Notebooks in order to maintain a web-based environment.
2 - Google Earth Engine does not function well with loops, so the the code for calling particular images had to be written independently, and then aggregated.
3 - Google Earth Engine's built in geographic filter function only functions with coordinate points, so to conduct a Neighborhood Analysis, feature geometries had to manually input as ee.MultiPolygon objects, and images reduced by desired regions.

