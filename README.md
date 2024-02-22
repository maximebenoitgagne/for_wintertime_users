# NetCDF Tutorial

This project contains documentation and examples on how to use
the outputs of the default simulation EXP-0 described in
Benoît-Gagné et al. (submitted).

The documentation and examples are available on
https://github.com/maximebenoitgagne/for_wintertime_users/tree/main.

The original project of Benoît-Gagné et al. (submitted) can be found on
https://github.com/maximebenoitgagne/wintertime/tree/v1.5.

# Installation steps

These installation steps were tested for MacOS 11 (Big Sur).

* Install Panoply (https://www.giss.nasa.gov/tools/panoply/download/).

- Install Anaconda for Python 3 as described on 
  https://datacarpentry.org/python-ecology-lesson/setup.html:
  - Go to https://www.anaconda.com/products/distribution.
  - Click Download.
  - Double-click the graphical installer `.pkg` file.
  - Follow the instructions. Select the default settings.
  - Verify the installation by entering the following command in the Terminal
    (Launchpad icon in the Dock, type Terminal, click Terminal):
```
conda --version
```
If your version of conda is < 4.4:
```
conda update conda
```
 
* Enter the following commands in the Terminal. The creation of the conda environment can take approximately 5 minutes.
```
git clone https://github.com/maximebenoitgagne/for_wintertime_users.git
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
