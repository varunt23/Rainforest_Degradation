# Rainforest_Degradation
collection of notebooks used to analyze forest degradation time series data for the amazon rainforest

Currently using Earth and the Impact Toolbox to extract Landsat images and classify regions based on forest gain, forest loss and non forested areas.

Converting data into a series usable by dask to look at NDVI values over time for a specific coordinate region in the amazon rainforest.
Took this further by using random forest models, and various boosting models to predict ndvi for a region given a ndvi xarray as inputs to the model.
