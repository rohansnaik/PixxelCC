The user needs to install pandas,matplotlib,sklearn libraries.
Pixxel_Code.ipynb file is used to read input bands, and create a RGB Geotiff. Once the file is created, we can use the band information to perform Kmeans algorithm.
To test the results, we can extract any of the input labels and read it, and export it to RGB image. This is useful to extract the surface water bodies areas.
Similar combinations of bands can be used to deduce other information, such as land, vegetation (NDVI), and other features.
mndwi_test.tif is the output obtained after reading one fo the green and SWIR bands, and stacking it.
test_cluster_out4.tif is thefile after reading one of hte SWIR bands, and performing kmeans algorithm by dividing into 5 clusters.
test_cluster_out_mask3.tif' is the output after extracting the label 0, out of 5, from the kmeans algorithm. This provides good primary information about the surface water bodies.
