# Python-Data-Exercises      Brandon Kerns      bkerns@rsmas.miami.edu
Training exercises for learning how to handle various atmospheric science data sets.

These exercises will use the Anaconda Python setup located on manta at:
/home/python/anaconda2/envs/meteo/bin/python

This Python setup was made by installing the Python 2.7 64 bit Linux Anaconda, and doing the following:
conda update conda
conda create --name meteo ipython scipy matplotlib basemap netcdf4 h5py
source activate meteo
conda install -c ncar pynio
conda install -c scitools cartopy

The exercise order will be:
1) Set up linux environment and plot surface station time series (meteogram).
2) Plot aircraft flight level data.
3) Plot radiosonde and dropsonde data.
4) Plot reanalysis maps.
5) Plot WRF model data.
