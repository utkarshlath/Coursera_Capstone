# Coursera Capstone
---
### This repository is a part of the Coursera Capstone Project for the IBM Data Science Professional Course.
### The content and use of each of the files is explained below. All the code has been written on Jupyter Notebook in Python.
### The main aim of the project is to cluster the different neighborhoods in the city of Toronto. This project serves as a stepping stone towards the final project of this Professional certificate to which I have dedicated another repository.

`Finding Neighborhoods.ipynb`  **In this file we extract information about the different neighborhoods of Toronto from a Wikipedia page. Using this data we create our dataframe. The dataframe is then cleaned for missing values. This dataframe is then saved as** `Neighborhoods.csv`**.**

 `Adding Coordinates.ipynb`  **In this file we use the**  `Neighborhoods.csv`  **data previously saved. To each of the neighborhood in this dataframe we find and add it corresponding coordinates. These coordinates were loaded from** `Geospatial_Coordinates.csv`**. This resultant dataframe is now saved as** `Final_Neighborhood_Data.csv`**.**
 
 `Exploring & Clustering Toronto Neighborhoods.ipynb` **In this final notebook we first load data stored in** `Final_Neighborhood_Data.csv`**. We then create a map of Toronto showing the different Neighborhoods. We choose the neighborhoods with 'Toronto' in there name to be classified. We find out the most common venues in these neighborhoods. This is done using the FourSquare API. KMeans is then used for clustering the neighborhoods. The clustered neighborhoods are finally visualized on the map.** (Errors may arise while viewing maps on Github so I have added images seperately in the Maps folder. Use can also view them by cloning and downloading this repository.)
