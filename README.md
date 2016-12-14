# Geophysics Labs Notebooks

This a collection of Jupyter Notebooks that I have written to illustrate or demonstrate the techniques and methods that are described in the blog posts on [geophysicslabs.com](http://geophysicslabs.com/).

---

## Running the notebooks 

The notebooks have been tested with Python 3.4 and 3.5. To install Python, using [Anaconda](https://www.continuum.io/downloads) is a good start. A default installation of Anaconda 4.2 includes Numpy, matplotlib, SciPy and scikit-learn, which should be enough for some notebooks. Additional packages might be required, and this depends on the notebook. 

A common way to deal with different sets of packages and therefore dependencies is to create an environment. For example, the notebook about [cropping and resampling]() needs `rasterio` to run, so you could type this on the command line:

```
# Create a new environment
conda create -n geophysicslabs rasterio

# Then start it (source activate on Linux)
activate geophysicslabs
```


