<div align="center"><img src="./assets/img/jwst_pillar_ofcreation.jpg" width="400" height="400"></div>
<p align="center"><em>Pillars of Creation (NIRCam and MIRI Composite Image). Image Credit: NASA, ESA, CSA, and STScI</em></p>

# Shivaji - Astronomical Software Tools
Welcome to the Astronomical Software Tools repository! This collection is dedicated to providing a comprehensive list of software tools and libraries that are essential for astronomical research and data analysis. Whether you are working with Python-based tools or standalone executable software, this repository aims to be a valuable resource for astronomers and astrophysicists. Explore the various tools listed below to enhance your research and streamline your workflows.

## Table of Contents
- [<img src="./assets/img/pythonlogo.ico" alt="Logo" width="15" height="15"> Python Tools](#python-tools)
    - [Astropy](#astropy)
    - [AstroML](#AstroMl)
    - [Astroquery](#astroquery)
    - [batman](#batman)
    - [Camb](#camb)
    - [CIGALE](#CIGALE)
    - [Cobaya](#cobaya)
    - [Dustpy](#Dustpy)
    - [Eureka](#Eureka)
    - [exoplanet](#exoplanet)
    - [Gala](#gala)
    - [GASTLI](#GASTLI)
    - [H5py](#h5py)
    - [Healpy](#healpy)
    - [Jdaviz](#jdaviz)
    - [Lightkurve](#lightkurve)
    - [PACMAN](#PACMAN)
    - [petitRADTRANS](#petitRADTRANS)
    - [Photutils](#Photutils)
    - [POSEIDON](#POSEIDON)
    - [PyCBC](#pycbc)
    - [Pynbody](#pynbody)
    - [pysynphot](#pysynphot)
    - [RADMC-3D](#RADMC-3D)
    - [REBOUND](#rebound)
    - [Spectral-cube](#spectral-cube)
    - [spiderman](#spiderman)
    - [Starry](#starry)
    - [HEAsoft](#heasoft)
- [<img src="./assets/img/executable_icon.png" alt="Logo" width="17" height="17"> Executable Software](#executable-software)
   - [Aladin](#aladin)
   - [Aperture Photometry Tool](#aperture-photometry-tool)
   - [AstroImageJ](#AstroImageJ)
   - [CASA](#CASA)
   - [CosmoMC](#CosmoMC)
   - [EXOFASTv2](#EXOFASTv2)
   - [JS9](#JS9)
   - [JS9-4L](#js9-4l)
   - [SAOImageDS9](#SAOImageDS9)
   - [TOPCAT](#topcat)
   - [SExtractor](#sextractor)

---

## <img src="./assets/img/pythonlogo.ico" alt="Logo" width="25" height="25"> Python Tools


### Astropy
<div align="center"><img src="./assets/img/astropy_brandmark.png" width="100" height="100"></div>

----

Astropy is a comprehensive library designed to support the core functionality needed for astronomy and astrophysics research. It provides a wide range of tools that are essential for astronomers, including celestial coordinate transformations, time and date handling, unit conversions, and data manipulation. 

One of the key strengths of Astropy is its ability to handle various astronomical file formats, making it easier for researchers to read and write data. Additionally, it offers modules for performing statistical analysis and visualizing data, which are crucial for interpreting astronomical observations.

For more information and to get started with Astropy, visit their [official website](https://www.astropy.org).

- **Installation**: [Install Astropy](https://docs.astropy.org/en/stable/install.html#installing-astropy)
- **Pip Installation**: `pip install astropy`
- **Source Code**: [GitHub Repository](https://github.com/astropy/astropy)
- **Tutorials**: [Learn Tutorials](https://learn.astropy.org/)
- **API Reference**: [Astropy API](https://docs.astropy.org/en/stable/index_user_docs.html)

### AstroML
<div align="center"><img src="./assets/img/astroml.gif" width="300" height="100"></div>

----

AstroML is a Python module for machine learning and data mining built specifically for astronomy. It contains a growing library of statistical and machine learning routines for analyzing astronomical data in a variety of formats. The library is designed to be flexible and easy to use, making it a valuable tool for both researchers and educators.

AstroML includes tools for data preprocessing, feature selection, regression, classification, clustering, and more. It also provides a collection of example datasets and scripts to help users get started quickly.

For more information and to get started with AstroML, visit their [official website](https://www.astroml.org).

- **Installation**: [Install AstroML](https://www.astroml.org/user_guide/installation.html)
- **Source Code**: [GitHub Repository](https://github.com/astroML/astroML)
- **Pip Installation**: `pip install astroML`
- **Tutorials**: [AstroML Tutorials](https://www.astroml.org/examples/index.html)
- **Books**: [AstroML Interactive Book](https://www.astroml.org/astroML-notebooks/)
- **Additional Resources**: [Textbook Figures](https://www.astroml.org/book_figures/)
- **API Reference**: [AstroML API](https://www.astroml.org/modules/classes.html)

### Astroquery
<div align="center"><img src="./assets/img/astropy_brandmark.png" width="100" height="100"></div>

----

Astroquery is a Python package that provides a simple interface for querying astronomical databases and archives. It allows users to access a wide range of data sources, including NASA's archives, the European Space Agency's archives, and many others. The library is designed to be easy to use, with a consistent API that simplifies the process of querying and retrieving data.

Astroquery supports a variety of query types, including cone searches, image searches, and spectral searches. It also provides tools for handling the returned data, making it easier to integrate into your analysis workflows.

For more information and to get started with Astroquery, visit their [official website](https://astroquery.readthedocs.io).

- **Installation**: `pip install astroquery`
- **Tutorials**: [Astroquery Tutorials](https://astroquery.readthedocs.io/en/latest/index.html#using-astroquery)
- **API Reference**: [Astroquery API](https://astroquery.readthedocs.io/en/latest/genindex.html)
- **Source Code**: [GitHub Repository](https://github.com/astropy/astroquery)
- **Python module Index**: [Useful API](https://astroquery.readthedocs.io/en/latest/py-modindex.html)

### batman
<div align="center"><img src="./assets/img/batlogo.jpg" width="200" height="200"></div>

----

batman (Bad-Ass Transit Model cAlculatioN) is a Python package for calculating transit light curves. It is designed to be fast and flexible, allowing users to model light curves for various types of exoplanetary systems. The package supports different limb darkening laws and can handle both primary and secondary eclipses.

batman is particularly useful for fitting transit light curves and deriving parameters such as the planet's radius, orbital inclination, and limb darkening coefficients.

For more information and to get started with batman, visit their [official website](https://lkreidberg.github.io/batman/docs/html/index.html).

- **Installation**: `pip install batman-package`
- **Source Code**: [GitHub Repository](https://github.com/lkreidberg/batman)
- **Documentation**: [batman Documentation](https://www.cfa.harvard.edu/~lkreidberg/batman/)
- **Tutorials**: [batman tutorials](https://lkreidberg.github.io/batman/docs/html/tutorial.html)
- **API Reference**: [batman API](https://lkreidberg.github.io/batman/docs/html/api.html)

### Camb
<div align="center"><img src="./assets/img/cobaya_camb.png" width="200" height="200"></div>

----

Camb (Code for Anisotropies in the Microwave Background) is a cosmology library for calculating theoretical predictions for the cosmic microwave background (CMB) and matter power spectra. It is widely used in the field of cosmology for analyzing data from CMB experiments and large-scale structure surveys.

Camb provides tools for computing the CMB power spectra, matter power spectra, and other related quantities. It is highly configurable, allowing users to specify various cosmological parameters and models.

For more information and to get started with Camb, visit their [official website](https://camb.info).

- **Installation**: `pip install camb`
- **Source Code**: [GitHub Repository](https://github.com/cmbant/CAMB)
- **Documentation**: [Camb Documentation](https://camb.readthedocs.io/en/stable/)
- **Examples**: [Camb Examples Notebook](https://camb.readthedocs.io/en/latest/CAMBdemo.html)
- **API Reference**: [Camb API](https://camb.readthedocs.io/en/stable/genindex.html)

### CIGALE
<div align="center"><img src="./assets/img/cigale.png" width="500" height="100"></div>

----

CIGALE (Code Investigating GALaxy Emission) is a Python package for modeling the spectral energy distribution (SED) of galaxies. It provides tools for fitting observed SEDs with theoretical models, allowing users to derive physical properties such as star formation rates, stellar masses, and dust content.

CIGALE is designed to be flexible and user-friendly, with a range of options for customizing models and fitting procedures. It is particularly useful for studying the multi-wavelength properties of galaxies and interpreting observational data.

For more information and to get started with CIGALE, visit their [official website](https://cigale.lam.fr).

- **Installation**: [Download CIGALE](https://cigale.lam.fr/download/)
- **Documentation**: [Cigate Documentation](https://cigale.lam.fr/documentation/)
- **Source Code**: [Gitlab Repository](https://gitlab.lam.fr/cigale/cigale/)
- **Tutorials**: [CIGALE Tutorials](https://gitlab.lam.fr/cigale/manual/)
- **Example Files**: 
```bash
# Download the zip CIGALE example file using wget
wget http://cigale.lam.fr/wp-content/uploads/2016/05/CIGALE_Howto_v0.9.0.zip
```
- **Research Paper**: [CIGALE Research Paper](https://www.aanda.org/articles/aa/pdf/2019/02/aa34156-18.pdf)

### Cobaya
<div align="center"><img src="./assets/img/cobaya_camb.png" width="200" height="200"></div>

----

Cobaya (Code for Bayesian Analysis) is a framework for sampling and statistical modeling, designed for cosmological parameter estimation. It allows users to define complex models and perform Bayesian inference using various sampling algorithms.

Cobaya is highly modular and can interface with other cosmological codes, such as CAMB and CLASS, to compute theoretical predictions. It also supports parallel computation, making it efficient for large-scale analyses.

For more information and to get started with Cobaya, visit their [official website](https://cobaya.readthedocs.io).

- **Installation**: [`pip install cobaya`](https://cobaya.readthedocs.io/en/latest/installation.html)
- **Source Code**: [GitHub Repository](https://github.com/CobayaSampler/cobaya)
- **Documentation**: [Cobaya Documentation](https://cobaya.readthedocs.io/en/latest/)
- **Examples**: [Cobaya Examples](https://cobaya.readthedocs.io/en/latest/example.html)
- **API Reference**: [Cobaya API](https://cobaya.readthedocs.io/en/latest/py-modindex.html)



### Dustpy
<div align="center"><img src="./assets/img/dustpy_logo.png" width="400" height="100"></div>

----

Dustpy is a Python package for simulating the evolution of dust in protoplanetary disks. It provides tools for modeling the growth, fragmentation, and dynamics of dust particles in these environments.

Dustpy is designed to be flexible and user-friendly, with a range of options for customizing simulations. It is particularly useful for studying the processes that lead to planet formation.

For more information and to get started with Dustpy, visit their [official website](https://stammler.github.io/dustpy/).

- **Installation**: `pip install dustpy`
- **Source Code**: [GitHub Repository](https://github.com/stammler/dustpy)
- **Documentation**: [Dustpy Documentation](https://stammler.github.io/dustpy/index.html#dustpy-documentation)
- **Examples**: [Dustpy Basic Usages](https://stammler.github.io/dustpy/1_basics.html)
- **API Reference**: [Dustpy API](https://stammler.github.io/dustpy/api.html)

### Eureka
<div align="center"><img src="./assets/img/Eureka_logo.png" width="200" height="200"></div>

----

Eureka is a Python package designed for the reduction and analysis of data from the James Webb Space Telescope (JWST). It provides tools for processing time-series observations, including functions for data calibration, light curve extraction, and transit fitting.

For more information and to get started with Eureka, visit their [official website](https://eurekadocs.readthedocs.io).

- **Installation**: [`pip install -e 'eureka[jwst]@git+https://github.com/kevin218/Eureka.git@v1.1'`](https://eurekadocs.readthedocs.io/en/latest/installation.html)
- **Source Code**: [GitHub Repository](https://github.com/kevin218/Eureka)
- **Documentation**: [Eureka Documentation](https://eurekadocs.readthedocs.io/en/latest/)
- **Tutorials**: [Eureka Tutorials](https://eurekadocs.readthedocs.io/en/latest/notebooks.html)
- **API Reference**: [Eureka API](https://eurekadocs.readthedocs.io/en/latest/api.html)

### exoplanet
<div align="center"><img src="./assets/img/e_logo.png" width="200" height="100"></div>

----

exoplanet is a toolkit for probabilistic modeling of time series data in astronomy, with a focus on observations of exoplanets. It leverages the PyMC library to provide a flexible and powerful framework for modeling and analyzing time series data, allowing users to perform tasks such as transit fitting, radial velocity analysis, and more.

These features include:

- A fast and robust solver for Kepler’s equation.
- Scalable Gaussian Processes using celerite.
- Fast and accurate limb darkened light curves using starry.
- Common reparameterizations for exoplanet-specific parameters like limb darkening and eccentricity.
- And many others!

For more information and to get started with exoplanet, visit their [official website](https://docs.exoplanet.codes/en/latest/).

- **Installation**: `python -m pip install -U "exoplanet[pymc]"`
- **Source Code**: [GitHub Repository](https://github.com/exoplanet-dev/exoplanet)
- **Documentation**: [exoplanet Documentation](https://docs.exoplanet.codes/en/stable/)
- **Tutorials**: [exoplanet Tutorials](https://docs.exoplanet.codes/en/latest/tutorials/autodiff/) [Tutorials Gallery](https://gallery.exoplanet.codes/)
- **API Reference**: [exoplanet API](https://docs.exoplanet.codes/en/stable/api/)

### Gala
<div align="center"><img src="./assets/img/Gala_Logo.png" width="100" height="100"></div>

----

Gala is a Python package for galactic dynamics. It provides tools for analyzing the orbits of stars and other objects in the Milky Way and other galaxies. The package includes functions for integrating orbits, estimating potential parameters, and performing various dynamical analyses.

Gala is designed to be flexible and user-friendly, with a range of options for customizing analyses. It is particularly useful for studying the structure and dynamics of galaxies.

For more information and to get started with Gala, visit their [official website](https://gala.adrian.pw).

- **Installation**: `pip install gala`
- **Source Code**: [GitHub Repository](https://github.com/adrn/gala)
- **Documentation**: [Gala Documentation](https://gala.adrian.pw/en/latest/)
- **Tutorials**: [Gala Tutorials](https://gala.adrian.pw/en/latest/tutorials.html)
- **API Reference**: [Gala API](https://gala.adrian.pw/en/latest/user_guide.html)

### GASTLI

GASTLI (Galactic and Stellar Light) is a Python package for simulating and analyzing the light from galaxies and stars. It provides tools for generating synthetic photometry, modeling stellar populations, and fitting observed data.

GASTLI is designed to be flexible and user-friendly, with a range of options for customizing simulations and analyses. It is particularly useful for studying the properties of galaxies and their stellar populations.

For more information and to get started with GASTLI, visit their [official website](https://gastli.readthedocs.io).

- **Installation**: [gastli install](https://gastli.readthedocs.io/en/latest/installation.html)
- **Source Code**: [GitHub Repository](https://github.com/gastli/gastli)
- **Documentation**: [GASTLI Documentation](https://gastli.readthedocs.io/en/latest/)
- **Tutorials**: [GASTLI tutorials](https://gastli.readthedocs.io/en/latest/tutorial.html)
- **API Reference**: [GASTLI API](https://gastli.readthedocs.io/en/latest/autoapi/index.html)

### H5py

H5py is a Python interface to the HDF5 binary data format, which is widely used in scientific computing for storing large datasets. It allows users to read and write HDF5 files, providing a flexible and efficient way to manage complex data.

H5py supports a range of data types and structures, making it suitable for a variety of applications, including astronomy. It also integrates well with other scientific libraries, such as NumPy and SciPy.

For more information and to get started with H5py, visit their [official website](https://www.h5py.org).

- **Installation**: `pip install h5py`
- **Source Code**: [GitHub Repository](https://github.com/h5py/h5py)
- **Documentation**: [H5py Documentation](https://docs.h5py.org/en/stable/)
- **Examples**: [H5py Examples](https://docs.h5py.org/en/stable/quick.html)
- **API Reference**: [H5py API](https://docs.h5py.org/en/stable/genindex.html)
- **BOOKS**:
    - [O'Reilly book, Python and HDF5, written by the lead author of h5py, Andrew Collette](http://shop.oreilly.com/product/0636920030249.do)

### Healpy

Healpy is a Python package for working with HEALPix (Hierarchical Equal Area isoLatitude Pixelation) data, which is commonly used in astronomy for analyzing spherical data, such as maps of the cosmic microwave background.

Healpy provides tools for creating, manipulating, and visualizing HEALPix maps. It also includes functions for performing spherical harmonic transforms and other operations on spherical data.

For more information and to get started with Healpy, visit their [official website](https://healpy.readthedocs.io).

- **Installation**: `pip install healpy`
- **Source Code**: [GitHub Repository](https://github.com/healpy/healpy)
- **Documentation**: [Healpy Documentation](https://healpy.readthedocs.io/en/latest/)
- **Tutorials**: [Healpy tutorial](https://healpy.readthedocs.io/en/latest/tutorial.html)
- **API Reference**: [Healpy API](https://healpy.readthedocs.io/en/latest/genindex.html)

### Jdaviz

<div align="center"><img src="./assets/img/jdaviz-launcher.png" width="400" height="200"></div>

----

Jdaviz is a suite of interactive data visualization tools for astronomy, built on the Jupyter platform. It provides a range of applications for visualizing and analyzing different types of astronomical data, including spectra, images, and cubes.

Jdaviz is designed to be user-friendly and highly customizable, with a focus on interactive exploration and analysis. It integrates with other scientific libraries, such as Astropy and Specutils, to provide a seamless workflow for astronomers.

For more information and to get started with Jdaviz, visit their [official website](https://jdaviz.readthedocs.io).

- **Installation**: [`pip install jdaviz`](https://jdaviz.readthedocs.io/en/stable/installation.html)
- **Source Code**: [GitHub Repository](https://github.com/spacetelescope/jdaviz)
- **Documentation**: [Jdaviz Documentation](https://jdaviz.readthedocs.io/en/latest/)
- **Tutorials**: [Jdaviz video tutorials](https://jdaviz.readthedocs.io/en/stable/video_tutorials.html) [jdaviz example notebook](https://jdaviz.readthedocs.io/en/stable/sample_notebooks.html#sample-notebook)
- **API Reference**: [Jdaviz API](https://jdaviz.readthedocs.io/en/stable/reference/api.html)

### Lightkurve

Lightkurve is a Python package for analyzing time series data from NASA's Kepler and TESS missions. It provides tools for working with light curves, including functions for reading, manipulating, and visualizing the data.

Lightkurve is designed to be easy to use, with a focus on enabling quick and efficient analysis of time series data. It also includes tools for detecting and characterizing exoplanets, making it a valuable resource for researchers in the field of exoplanet science.

For more information and to get started with Lightkurve, visit their [official website](https://lightkurve.github.io/lightkurve/index.html).

- **Installation**: `pip install lightkurve`
- **Source Code**: [GitHub Repository](https://github.com/lightkurve/lightkurve)
- **Tutorials**: [Lightkurve Examples](https://lightkurve.github.io/lightkurve/tutorials/index.html)
- **API Reference**: [Lightkurve API](https://lightkurve.github.io/lightkurve/reference/index.html)
- **Other similar software**[Similar software that may complement lightkurve ](https://lightkurve.github.io/lightkurve/about/other_software.html)

### Minato

Minato (Massive bINaries Analysis TOols) is a Python package designed for the analysis of massive binary stars. It provides tools for spectral analysis, allowing users to fit the spectra of binary stars simultaneously with synthetic spectra. The package returns effective temperatures, log surface gravities, rotational velocities, He/H ratios, and the light ratio.

- **Source Code**: [GitHub Repository](https://github.com/jvillasr/MINATO)
- **Documentation**: [Minato Documentation](https://github.com/jvillasr/MINATO)
- **Tutorials**: [Minato Examples](https://github.com/jvillasr/MINATO/tree/main/minato/tutorials)

### PACMAN
<div align="center"><img src="./assets/img/Pacman.gif" width="400" height="200"></div>

----

``PACMAN`` is a pipeline to reduce and analyze Hubble/Wide Field Camera 3 (WFC3) observations of transiting exoplanets. The pipeline runs end-to-end, beginning with a time series of 2D images and ending with a spectrum for the planet. ``PACMAN`` can easily fit multiple observations simultaneously.
                                                                                
The main steps in the pipeline are:                                             
                                                                                
- optimally extract spectra from the 'ima' data products provided by STScI      
- bin the spectra into user-specified wavelength bins and output the light curve(s)
- fit the light curves with a variety of astrophysical models (transit, eclipse, phase curve) and instrument systematic models (visit-long quadratic trends, orbit-long exponential trends)
- estimate uncertainties on the planet parameters with least-squares, MCMC, or nested sampling
    
For more information and to get started with PACMAN, visit their [official website](https://pacmandocs.readthedocs.io/en/latest/).

- **Installation**: [`pip install 'pacman@git+https://github.com/sebastian-zieba/PACMAN.git@v0.4.0'`](https://pacmandocs.readthedocs.io/en/latest/installation.html)
- **Source Code**: [GitHub Repository](https://github.com/sebastian-zieba/PACMAN)
- **Documentation**: [PACMAN Documentation](https://pacmandocs.readthedocs.io/en/latest/)
- **Tutorials**: [PACMAN  Quickstart](https://pacmandocs.readthedocs.io/en/latest/before_running.html)
- **API Reference**: [PACMAN API](https://pacmandocs.readthedocs.io/en/latest/api.html)

### petitRADTRANS
<div align="center"><img src="./assets/img/petitlogo.png" width="200" height="200"></div>

----

petitRADTRANS is a Python package for modeling the transmission and emission spectra of exoplanet atmospheres. It provides tools for generating synthetic spectra based on various atmospheric parameters, including temperature, composition, and cloud properties.

petitRADTRANS is designed to be flexible and user-friendly, with a range of options for customizing models. It is particularly useful for studying the atmospheres of transiting exoplanets and interpreting observational data.

For more information and to get started with petitRADTRANS, visit their [official website](https://petitradtrans.readthedocs.io).

- **Installation**: [Installation docs](https://petitradtrans.readthedocs.io/en/latest/content/installation.html)
- **Source Code**: [GitHub Repository](https://github.com/exoclime/petitRADTRANS)
- **Documentation**: [petitRADTRANS Documentation](https://petitradtrans.readthedocs.io/en/latest/)
- **Tutorials**: [petitRADTRANS Tutorials](https://petitradtrans.readthedocs.io/en/latest/content/tutorial.html) [Examples](https://petitradtrans.readthedocs.io/en/latest/content/retrieval_examples.html)
- **API Reference**: [petitRADTRANS API](https://petitradtrans.readthedocs.io/en/latest/autoapi/index.html)

### Photutils
<div align="center"><img src="./assets/img/photutils_logo.svg" width="200" height="100"></div>

----

Photutils is a Python package for detecting and performing photometry of astronomical sources. It provides tools for source detection, aperture photometry, point spread function (PSF) photometry, and background estimation.

Photutils is designed to be flexible and easy to use, with a range of options for customizing analyses. It integrates well with other scientific libraries, such as Astropy, making it a valuable tool for astronomers.

For more information and to get started with Photutils, visit their [official website](https://photutils.readthedocs.io).

- **Installation**: `pip install photutils`
- **Source Code**: [GitHub Repository](https://github.com/astropy/photutils)
- **Documentation**: [Photutils Documentation](https://photutils.readthedocs.io/en/stable/)
- **Tutorials**: [Photutils Tutorials](https://photutils.readthedocs.io/en/stable/user_guide/index.html)
- **API Reference**: [Photutils API](https://photutils.readthedocs.io/en/stable/reference/index.html)

### POSEIDON
<div align="center"><img src="./assets/img/POSEIDON_logo.png" width="300" height="100"></div>

----

POSEIDON is a Python package for modeling and analyzing exoplanet atmospheres. It provides tools for generating synthetic spectra, fitting observed spectra, and retrieving atmospheric properties. POSEIDON's main application is modelling and retrieval of 1D, 2D, and 3D exoplanet transmission spectra.

POSEIDON is particularly useful for studying the atmospheres of transiting exoplanets, allowing researchers to infer properties such as temperature, composition, and cloud coverage.

For more information and to get started with POSEIDON, visit their [official website](https://poseidon-retrievals.readthedocs.io/en/latest/).

- **Installation**: [`pip install poseidon`](https://poseidon-retrievals.readthedocs.io/en/latest/content/installation.html)
- **Source Code**: [GitHub Repository](https://github.com/MartianColonist/POSEIDON)
- **Documentation**: [POSEIDON Documentation](https://poseidon-retrievals.readthedocs.io/en/latest/)
- **Tutorials**: [POSEIDON Tutorials](https://poseidon-retrievals.readthedocs.io/en/latest/content/forward_model_tutorials.html)
- **API Reference**: [POSEIDON API](https://poseidon-retrievals.readthedocs.io/en/latest/autoapi/index.html)

### PyCBC
<div align="center"><img src="./assets/img/pycbc_logo.png" width="400" height="200"></div>

----

PyCBC is a Python package for gravitational-wave astronomy, developed by the LIGO and Virgo collaborations. It provides tools for analyzing data from gravitational-wave detectors, including functions for signal processing, parameter estimation, and data visualization.

PyCBC is designed to be flexible and scalable, with support for parallel computation and integration with other scientific libraries. It is widely used in the field of gravitational-wave astronomy for detecting and characterizing gravitational-wave signals.

For more information and to get started with PyCBC, visit their [official website](https://pycbc.org).

- **Installation**: `pip install pycbc`
- **Source Code**: [GitHub Repository](https://github.com/gwastro/pycbc)
- **Documentation**: [PyCBC Documentation](https://pycbc.org/pycbc/latest/html/)
- **Tutorials**: [PyCBC Examples](https://github.com/gwastro/PyCBC-Tutorials) [Library Examples and Interactive Tutorials](https://pycbc.org/pycbc/latest/html/tutorials.html)
- **API Reference**: [PyCBC API](https://pycbc.org/pycbc/latest/html/modules.html)

### PyNbody
<div align="center"><img src="./assets/img/pynbody_logo.svg" width="300" height="200"></div>

----

PyNbody is a Python package for analyzing and visualizing N-body simulations. It is designed for working with large-scale cosmological simulations, such as those modeling galaxy formation, dark matter halos, and the large-scale structure of the universe.

PyNbody provides tools for loading, manipulating, and visualizing simulation data, making it easier for researchers to analyze complex astrophysical systems. It also supports integration with other scientific libraries, such as NumPy and Matplotlib.

For more information and to get started with PyNbody, visit their [official website](https://pynbody.readthedocs.io/latest/).

- **Installation**: `pip install pynbody`
- **Source Code**: [GitHub Repository](https://github.com/pynbody/pynbody)
- **Documentation**: [PyNbody Documentation](https://pynbody.readthedocs.io/latest/)
- **Tutorials**: [PyNbody Tutorials](https://pynbody.readthedocs.io/latest/tutorials/tutorials.html)
- **API Reference**: [PyNbody API](https://pynbody.readthedocs.io/latest/reference/index.html)

---

### pysynphot

pysynphot is a Python package for synthetic photometry, designed to simulate photometric observations. It is part of the Space Telescope Science Data Analysis System (STSDAS) and provides tools for creating synthetic spectra, calculating photometric magnitudes, and performing other photometric analyses.

pysynphot is particularly useful for simulating observations with the Hubble Space Telescope (HST) and other space-based observatories. It allows users to model the effects of different filters, detectors, and observing conditions on the observed photometry.

For more information and to get started with pysynphot, visit their [official website](https://pysynphot.readthedocs.io).

- **Installation**: `pip install pysynphot`
- **Source Code**: [GitHub Repository](https://github.com/spacetelescope/pysynphot)
- **Documentation**: [pysynphot Documentation](https://pysynphot.readthedocs.io/en/latest/)
- **Tutorials**: [pysynphot Tutorials](https://pysynphot.readthedocs.io/en/latest/tutorials.html)
- **API Reference**: [pysynphot API](https://pysynphot.readthedocs.io/en/latest/ref_api.html)


### RADMC-3D

RADMC-3D is a versatile radiative transfer code for astrophysical applications. It is designed to simulate the propagation of radiation through dusty and gaseous media, making it useful for studying a wide range of astrophysical environments, such as protoplanetary disks, molecular clouds, and circumstellar envelopes.

RADMC-3D supports various types of radiative transfer calculations, including continuum and line transfer, and can handle complex geometries and physical conditions. It is highly configurable, allowing users to customize their simulations to match specific scientific needs.

It runs on linux and OS X.

For more information and to get started with RADMC-3D, visit their [official website](https://www.ita.uni-heidelberg.de/~dullemond/software/radmc-3d/).

- **Installation**: [Install RADMC-3D](https://www.ita.uni-heidelberg.de/~dullemond/software/radmc-3d/manual_rmcpy/install.html)
- **Source Code**: [GitHub Repository](https://github.com/dullemond/radmc-3d)
- **Python Module Package**: [RADMC-3D module package](https://www.ita.uni-heidelberg.de/~dullemond/software/radmc-3d/manual_rmcpy/genindex.html)
- **API Reference**: [RADMC-3D API](https://www.ita.uni-heidelberg.de/~dullemond/software/radmc-3d/manual_rmcpy/genindex.html)

### REBOUND
<div align="center"><img src="./assets/img/reboundbanner.png" width="400" height="100"></div>

----

REBOUND is a powerful **N-body simulation package** for gravitational dynamics, written primarily in **C** with a Python interface. It is widely used for simulating planetary systems, exoplanets, and other gravitational interactions. REBOUND is designed to be fast, flexible, and easy to use, making it a popular choice for researchers studying the dynamics of celestial bodies.

REBOUND supports a variety of integrators, including the **IAS15** integrator for high-precision simulations and the **WHFast** integrator for fast, symplectic integrations. It also includes tools for visualizing simulations and analyzing the results.

For more information and to get started with REBOUND, visit their [official website](https://rebound.readthedocs.io).

- **Installation (Python)**: `pip install rebound`
- **Installation (C)**: Follow the instructions in the [REBOUND Documentation](https://rebound.readthedocs.io/en/latest/quickstart_installation/).
- **Source Code**: [GitHub Repository](https://github.com/hannorein/rebound)
- **Documentation**: [REBOUND Documentation](https://rebound.readthedocs.io/)
- **Tutorials**: [REBOUND Examples](https://rebound.readthedocs.io/en/latest/examples/)
- **API Reference**: [REBOUND API](https://rebound.readthedocs.io/en/latest/api/)

### Spectral-cube
<div align="center"><img src="./assets/img/spectral_cube.svg" width="200" height="200"></div>

----

Spectral-cube is a Python package for reading, writing, and analyzing spectral data cubes, which are commonly used in radio and millimeter astronomy. It provides tools for manipulating and visualizing spectral cubes, including functions for spectral extraction, moment calculation, and masking.

Spectral-cube is designed to be efficient and easy to use, with support for large datasets and integration with other scientific libraries, such as Astropy and Dask.

For more information and to get started with Spectral-cube, visit their [official website](https://spectral-cube.readthedocs.io).

- **Installation**: `pip install spectral-cube`
- **Source Code**: [GitHub Repository](https://github.com/radio-astro-tools/spectral-cube)
- **Documentation**: [Spectral-cube Documentation](https://spectral-cube.readthedocs.io/en/latest/)
- **Examples**: [Spectral-cube Examples](https://spectral-cube.readthedocs.io/en/latest/examples.html)
- **API Reference**: [Spectral-cube API](https://spectral-cube.readthedocs.io/en/latest/api.html)

### spiderman

spiderman is an open-source Python package designed to model phase curves and secondary eclipses of exoplanets. It provides tools for simulating the thermal emission and reflected light from exoplanets as they orbit their host stars, allowing researchers to study the atmospheric properties and dynamics of these distant worlds.

spiderman is particularly useful for analyzing data from space-based telescopes, such as the James Webb Space Telescope (JWST) and the Hubble Space Telescope (HST), as well as ground-based observatories.

For more information and to get started with spiderman, visit their [official website](https://spiderman.readthedocs.io).

- **Installation**: `pip install spiderman-package`
- **Source Code**: [GitHub Repository](https://github.com/tomlouden/spiderman)
- **Tutorials**: [spiderman Tutorials](https://spiderman.readthedocs.io/en/latest/quickstart.html)


### Starry
<div align="center"><img src="./assets/img/starry.png" width="200" height="200"></div>

----

Starry is a Python package for fast and accurate computation of light curves and stellar maps. It is designed to model the surface brightness of stars and exoplanets, allowing users to simulate and analyze time-series data from transiting exoplanets, eclipsing binaries, and other variable stars.

Starry leverages spherical harmonics to provide a flexible and efficient framework for modeling complex surface features, such as star spots and planetary albedo variations.

For more information and to get started with Starry, visit their [official website](https://rodluger.github.io/starry/).

- **Installation**: `pip install -U starry`
- **Source Code**: [GitHub Repository](https://github.com/rodluger/starry)
- **Documentation**: [Starry Documentation](https://starry.readthedocs.io/en/latest/)
- **Tutorials**: [Starry Tutorials](https://starry.readthedocs.io/en/latest/tutorials/)
- **API Reference**: [Starry API](https://starry.readthedocs.io/en/latest/api/)


## <img src="./assets/img/executable_icon.png" alt="Logo" width="27" height="27"> Executable Software

### Aladin
<div align="center"><img src="./assets/img/aladin.ico" width="100" height="100"></div>

----

Aladin  is an interactive sky atlas for data visualization. It allows users to visualize and analyze astronomical images and catalogs. Aladin supports a wide range of data formats and provides tools for overlaying and comparing different datasets.

Aladin desktop runs on windows, linux and mac.

For more information and to get started with Aladin, visit their [official website](https://aladin.u-strasbg.fr).

- **Installation**: [Download Aladin](https://aladin.u-strasbg.fr/java/nph-aladin.pl?frame=downloading)
- **Documentation**: [Aladin Documentation](https://aladin.u-strasbg.fr/java/AladinManual6.pdf)
- **Tutorials**: [Aladin Tutorials](https://aladin.u-strasbg.fr/java/AladinManual6.pdf#page=6)

### Aperture Photometry Tool
<div align="center"><img src="./assets/img/APT.png" width="700" height="200"></div>

----

Aperture Photometry Tool (APT) is a software for astronomical research, as well as for learning, visualizing and refining aperture-photometry analyses. It provides tools for measuring the brightness of stars and other point sources in images, with options for background subtraction and error estimation.

APT is designed to be user-friendly and flexible, with a graphical interface that allows users to interactively define apertures and analyze photometric data. It supports a wide range of image formats and includes features for batch processing and data visualization.

For more information and to get started with APT, visit their [official website](https://www.aperturephotometry.org).

- **Installation**: [Download APT](https://www.aperturephotometry.org/downloads/)
- **Documentation**: [APT feature/function Documentation](https://www.aperturephotometry.org/features-functions/)
- **Tutorials**: [APT Tutorials](https://www.youtube.com/watch?v=5lXAWfBW_NQ)

### AstroImageJ
<div align="center"><img src="./assets/img/aij_image_display_w400.png" width="200" height="200"><img src="./assets/img/aij_light_curve_w400.png" width="200" height="200"></div>

----

AstroImageJ is an astronomical image processing software based on ImageJ. It provides tools for analyzing astronomical images, including photometry, astrometry, and image calibration.

For more information and to get started with AstroImageJ, visit their [official website](https://www.astro.louisville.edu/software/astroimagej/).

- **Installation**: [Download AstroImageJ](https://www.astro.louisville.edu/software/astroimagej/installation_packages/)
- **Documentation**: [AstroImageJ Documentation](https://www.astro.louisville.edu/software/astroimagej/AIJ_Documentation/)
- **Tutorials**: [AstroImageJ Tutorials](https://www.astro.physik.uni-goettingen.de/~hessman/ImageJ/Book/index.html)

### CASA
<div align="center"><img src="./assets/img/casa_logo.png" width="200" height="150"></div>

----

CASA (Common Astronomy Software Applications) is a software suite for the calibration and analysis of radio astronomical data. It is widely used for processing data from radio telescopes, such as the Atacama Large Millimeter/submillimeter Array (ALMA) and the Very Large Array (VLA).

CASA provides a range of tools for data calibration, imaging, and analysis, including functions for flagging, calibration, imaging, and visualization. It is designed to be flexible and user-friendly, with a Python-based interface that allows for scripting and automation.

For more information and to get started with CASA, visit their [official website](https://casa.nrao.edu).

- **Installation**: [Install CASA](https://casa.nrao.edu/casa_obtaining.shtml)
- **Source Code**: [GitHub Repository](https://github.com/casangi)
- **Documentation**: [CASA Documentation](https://casadocs.readthedocs.io/en/stable/)
- **Tutorials**: [CASA Tutorials](https://casaguides.nrao.edu/index.php?title=Main_Page)
- **API Reference**: [CASA API](https://casadocs.readthedocs.io/en/stable/api.html)

### CosmoMC
<div align="center"><img src="./assets/img//cmcc_.png" width="300" height="300"></div>

----

CosmoMC is a Markov Chain Monte Carlo (MCMC) engine for exploring cosmological parameter space. It is widely used in the field of cosmology for analyzing data from cosmic microwave background (CMB) experiments, large-scale structure surveys, and other cosmological observations.

CosmoMC provides tools for performing Bayesian inference on cosmological models, allowing users to estimate parameters and their uncertainties. It is highly configurable, with support for various cosmological models and data sets.

For more information and to get started with CosmoMC, visit their [official website](https://cosmologist.info/cosmomc/).

- **Installation**: [Install CosmoMC](https://cosmologist.info/cosmomc/readme.html#Compiling)
- **Source Code**: [GitHub Repository](https://github.com/cmbant/CosmoMC)
- **Documentation**: [CosmoMC Documentation](https://cosmologist.info/cosmomc/readme.html)

### EXOFASTv2

An exoplanet transit and radial velocity fitting software package in IDL. EXOFASTv2 is a software package for modeling and characterizing exoplanetary systems. It provides tools for fitting transit and radial velocity data, allowing users to derive precise parameters for exoplanets and their host stars.

For more information and to get started with EXOFASTv2, visit their [Github](https://docs.google.com/document/d/1H-HMe1No5B4JE93V9kSEW91uSIQcG2eUVScf037biZw/edit).

- **Installation**: [Install EXOFASTv2](https://docs.google.com/document/d/1kcm7_mgfoCdDx6lUeqUJdDkpxtejyTNQf3sIveq3lkk/edit?tab=t.0)
- **Source Code**: [GitHub Repository](https://github.com/jdeast/EXOFASTv2)
- **Tutorials**: [EXOFASTv2 Tutorials](https://docs.google.com/document/d/1H-HMe1No5B4JE93V9kSEW91uSIQcG2eUVScf037biZw/edit)

### JS9
<div align="center"><img src="./assets/img/JS9.png" width="300" height="300"></div>

----

JS9 is a web-based astronomical image display tool that allows users to visualize and analyze FITS images directly in their web browser. It provides a range of features for image manipulation, including zooming, panning, color mapping, and region selection.

JS9 is designed to be lightweight and easy to use, making it a convenient tool for quick image analysis and visualization. It can be integrated into web applications and supports various data formats.

For more information and to get started with JS9, visit their [official website](https://js9.si.edu).

### JS9-4L

JS9-4L is a web-based lightweight version of JS9 designed for use on low-power devices, such as laptops and tablets. It provides many of the same features as JS9, including image visualization and analysis, but is optimized for performance on less powerful hardware.

JS9-4L is ideal for fieldwork and educational purposes, where portability and ease of use are important. It supports various data formats and can be integrated into web applications for remote access.

For more information and to get started with JS9-4L, visit their [official website](https://waps.cfa.harvard.edu/eduportal/js9/software.php).


### SAOImageDS9
<div align="center"><img src="./assets/img/ds9.png" width="300" height="300"></div>

----

SAOImageDS9 is a tool for visualizing astronomical imaging data. It supports a wide range of data formats and provides tools for image analysis, including region selection, filtering, and color mapping.

For more information and to get started with SAOImageDS9, visit their [official website](https://sites.google.com/cfa.harvard.edu/saoimageds9).

- **Installation**: [Install SAOImageDS9](https://sites.google.com/cfa.harvard.edu/saoimageds9/download)
- **Documentation**: [SAOImageDS9 Documentation](https://sites.google.com/cfa.harvard.edu/saoimageds9/documentation)
- **Tutorials**: [SAOImageDS9 Tutorials](https://www.youtube.com/user/4ciaodemos)

### TOPCAT
<div align="center"><img src="./assets/img/tc_sok.png" width="100" height="100"><img src="./assets/img/topcat.png" width="200" height="200"></div>

----

TOPCAT is software for catalog manipulation and visualization. It provides tools for exploring and analyzing large astronomical catalogs, including functions for plotting, filtering, and cross-matching data.

For more information and to get started with TOPCAT, visit their [official website](http://www.star.bristol.ac.uk/~mbt/topcat/).

- **Installation**: [Install TOPCAT](http://www.star.bristol.ac.uk/~mbt/topcat/#install)
- **Documentation**: [TOPCAT Documentation](http://www.star.bristol.ac.uk/~mbt/topcat/#docs)
- **Tutorials**: [TOPCAT Tutorials](http://www.star.bristol.ac.uk/~mbt/topcat/#tutorials)

### SExtractor

SExtractor (Source Extractor) is a tool for source extraction from astronomical images. It provides tools for detecting and measuring the properties of sources in images, including photometry and astrometry.

For more information and to get started with SExtractor, visit their [official website](https://sextractor.readthedocs.io).

- **Installation**: [Install SExtractor](https://sextractor.readthedocs.io/en/latest/Installing.html)
- **Documentation**: [SExtractor Documentation](https://sextractor.readthedocs.io/en/latest/)
- **Github**:[Github Sources](write for github:https://github.com/astromatic/sextractor)
- **Tutorials**: [SExtractor Tutorials](https://sextractor.readthedocs.io/en/latest/Using.html)

---

## Contribution
Feel free to submit issues or pull requests for additional tools or updates.

---

## License
MIT License