# Tutorials


### Setting up your environment

I like to use [virtualenv](https://pypi.org/project/virtualenv/) to make sure I'm running in a well-defined environment. 

To create a clean Python3 virtual environment:

``
virtualenv --no-site-packages -p python3 p3env
``

then activate it:

``
source p3env/bin/activate
``

You can then install all of the libraries for these tutorials using:

``
pip3 install -r requirements.txt
``

### Tutorial 1: Simulating an interferometer and making an image

### Tutorial 2: Machine Learning Classification of Pulsar Candidates

This tutorial is based on the [IAU OAD Data Science Toolkit](https://github.com/astro4dev/OAD-Data-Science-Toolkit) tutorials by [Rob Lyon](http://www.scienceguyrob.com) and uses the [HTRU2 Dataset](https://archive.ics.uci.edu/ml/datasets/HTRU2) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.883844.svg)](https://doi.org/10.5281/zenodo.883844)
