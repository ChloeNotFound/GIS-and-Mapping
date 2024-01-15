# Working with geospatial data 

Lab Part1: Data types, Storage, and Conversion

Part 1 will focus on the many different data types that exist within GIS and will provide an overview of the major data types in GIS and How to use the previously covered Python code libraries to read and write geospatial data. Apart from Reading and writing different geospatial data types, you'll learn how to use these libraries to perform file conversion between different data types and how to download data from geospatial database and remote sources.

The following vector and raster data types will be covered here.

Shapefiles
GeoJSON
KML
GeoPackages
GeoTiff
The following file actions will also be covered, using Python geospatial data libraries.

Opening existing files
Reading and displaying different attributes (spatial and non spatial
Creating and writing new geospatial data in different formats
Converting one file format to another
Downloading geospatial data
Lab2 Part 2: Working with vector data

This part will cover geospatial analysis and processing of vector data. The following three Python libraries will be covered: 1) Shapely, 2) OGR, and 3) GeoPandas.

The reader will learn how to use these Python libraries to perform geospatial analysis, including the writing of basic and advanced analysis scripts.

Each library is covered separately, with an overview of its data structures, methods, and classes where appropriate. We will discuss the best use cases for each library and how to use them together for geospatial workflows. Short example scripts illustrate how to perform the basic geographical analysis. The GeoPandas library enables more complex functionality for doing data science tasks and incorporating geospatial analysis.

In this chapter, we'll cover the following topics:

Reading and writing vector data
Creating and manipulating vector data
Visualizing (plotting) vector data on a map
Working with map projections and reproject data
Performing spatial operations such as spatial joins
Working with vector geometries and attribute data in tabular form
Analyzing the results to answer questions, such as how many wildfire are there in area x?
After this chapter, you'll have a solid foundation to start working with geospatial vector data. You will know the characteristics and use cases of all three geospatial libraries, and know how to do basic vector data processing and analysis.

 

Deliverables:
Part 1.
HTML export of a Jupyter notebook with:

Your practice code from the Part 1 exercises
Code that you have written and executed to plot "world_[LASTNAME].geojson" from the "Your Turn" section
An explanation in a Markdown cell of what your code does in the "Your Turn" section
Part 2. 
HTML export of a Jupyter notebook with:

Your practice code from the Part 2 exercises
"Your Turn" code that you have written and executed to:
join the two wildfire datasets in Canvas (Wildfire count from 1/1/1985 to 12/31/1999 Download Wildfire count from 1/1/1985 to 12/31/1999and Wildfire count from 1/1/2000 to 12/31/2014 Download Wildfire count from 1/1/2000 to 12/31/2014) to the states file
list wildfire counts for each state by each time period
plot these two datasets
One or two paragraphs in Markdown explaining how you analyzed in "Your Turn" from start to finish
