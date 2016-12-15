# Geophysics Labs Notebooks

This a collection of Jupyter Notebooks that I have written to illustrate or demonstrate the techniques and methods that are described in the blog posts on [geophysicslabs.com](http://geophysicslabs.com/).

Here is the list of notebooks so far, more will come soon!

1. [Color quantization with scikit-learn](notebooks/01_Color_quantization_with_sklearn.ipynb) - part of [How to add maps to OpendTect?](http://geophysicslabs.com/2016/12/15/how-to-add-maps-to-opendtect/)
2. [Cropping and resampling a grid](notebooks/02_Cropping_and_resampling_grid.ipynb) - part of [How to add maps to OpendTect?](http://geophysicslabs.com/2016/12/15/how-to-add-maps-to-opendtect/)

---

## Running the notebooks 

The notebooks have been tested with Python 3.4 and 3.5. To install Python, using [Anaconda](https://www.continuum.io/downloads) is a good start. A default installation of Anaconda 4.2 includes Numpy, matplotlib, SciPy and scikit-learn, which should be enough for some notebooks. Additional packages might be required, and this depends on the notebook. 

A common way to deal with different sets of packages and therefore dependencies is to create an environment. For example, the notebook about [cropping and resampling](notebooks/02_Cropping_and_resampling_grid.ipynb) needs `rasterio` to run, so you could type this on the command line:

```
conda create -n geophysicslabs rasterio scipy matplotlib scikit-learn ipykernel
```
The addition of `ipykernel` allows you to run the notebook with the new environment in Jupyter. In the menu, go to Kernel > Change kernel and select `geophysicslabs`.

