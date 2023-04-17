# NetCDF Tutorial

This project contains documentation and examples on how to use
the outputs of the default simulation EXP-0 described in
Benoît-Gagné et al. (submitted).

The documentation and examples are available on
https://github.com/maximebenoitgagne/for_wintertime_users/tree/main.

The original project of Benoît-Gagné et al. (submitted) can be found on
https://github.com/maximebenoitgagne/wintertime/tree/v1.5.

# Installation steps

These installation steps were tested for MacOS X 10.13 (High Sierra).

* Install Panoply (https://www.giss.nasa.gov/tools/panoply/download/).
* Install Anaconda for Python 3
(see https://datacarpentry.org/python-ecology-lesson/setup.html).
* Enter the following commands in the Terminal.
The creation of the conda environment can take approximately 15 minutes.
```
git clone git@github.com:maximebenoitgagne/for_wintertime_users.git
cd for_wintertime_users/
conda env create -f for_wintertime_users.yml
conda activate for_wintertime_users
jupyter notebook
```

Once the environment for_wintertime_users is created, the Jupyter notebook can be launched simply with:

```
cd for_wintertime_users/
conda activate for_wintertime_users
jupyter notebook
```
