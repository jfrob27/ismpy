# ISMPY

## Python library for interstellar medium (ISM) analysis

The main purpose of this repository si to give the essential tools to perform a power spectrm analysis.

Here is a non-hexaustive description of some functions:

* The function **powspec()** calculates the classical Fourier Power Spectrum of an image where the Fourier coefficients are averaged over the azimuthal angles as a function of the wavenumber.

* The function **gauss_beam()** allows one to model the transfer function of a telescope by a Gaussian function.

* Functions **subfits()**, **congrid()** (in *rebin.py*) and **imsmooth()** allow respectively to cut a fits file, rebin a map and smooth a map.

* Finally, the function **fbm2d()** in *noisegen.py* allows one to create a fractional Brownian motion map, i.e. a fractal image, respecting a specific power law.

Many of these functions are strongly inspired by the [mamdlib](https://www.ias.u-psud.fr/pperso/mmiville/mamdlib.html) IDL library.

## Installation

Clone this repository

`git clone https://github.com/jfrob27/ismpy.git`

and add the folder path to your `PYTHONPATH`.

This short library can be completed with functions in the repository **pywavan**

`git clone https://github.com/jfrob27/pywavan.git`