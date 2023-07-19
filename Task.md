In the `task` catalog you will find the Landsat 8 scene from June 5, 2023,
showing the area of the Szamotuły county. Make an unsupervised classification,
which will consist of the following steps:

1. List and load spectral bands.
2. Load vector data and transform CRS.
3. Crop raster data to the area.
4. Scale the values and remove outliers.
5. Prepare the matrix for classification (remove empty values and sample).
6. Use the k-means algorithm for clustering and validate the results with
the silhouette index. Check how the results change depending on the number
of clusters. Optionally, you can test [another clustering method](https://www.statmethods.net/advstats/cluster.html).
7. Try to interpret what the clusters represent using a boxplot and
RGB composition.
8. Present the results on a map and choose the appropriate color scheme.
