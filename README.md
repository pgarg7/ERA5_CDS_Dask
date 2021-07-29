# ERA5_CDS_Dask
This is an example I have been working on to access ERA5 data using CDS Store and Dask. It is an adaptation of Prof. Ryan Abernathey's lazy loading code he has on his Github Repository. You can access Prof. Abernathey's repo here: https://github.com/pangeo-data/pangeo-era5/blob/master/lazy_loading_expts.ipynb 

The notebook contains two methods to access ERA5 data:
1) Using Dask Lazy loading (Faster but works for one variable at a time for now) 
2) Using CDSAPI and loading data in the memory (Slower but works for multiple variables). 
