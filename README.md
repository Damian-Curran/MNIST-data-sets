# MNIST-data-sets

## Problem Sheet 2

In this repository we will be taking a look at the MNIST data set and investigating its different aspects.
We will then read MNIST data(image bytes/ label bytes).
We will also print out images using dots and hashes.

## MNIST Data Set

There are 4 different files. Two training and two test files, both are layed out in the same way.

The Image files are comprised of initially 16 bytes split into 4 parts of 4 bytes each. 
Theses parts are:
* Magic Number
* Number of Images
* Number of Rows
* Number of Columns

The rest of the Image file holds the bytes for 60,000(10,000 for test) Images.

The Label files consist of 8 bytes which spplit into two parts.
Theses parts are:
* Magic Number
* Number of Labels

The rest of the Label file holds the bytes for 60,000(10,000 for test) Labels.

## Installing needed technologies

You'll will first need to install Python, this can be done by following this link and its instructions, install Python 3 [Pyton Install](https://www.howtogeek.com/197947/how-to-install-python-on-windows/)
Make sure Python is in your enviroment variables path.
To check if Python installed properly, open your cmd and type "Python".

You will need the numpy library too, to do so, open your cmd and enter: pip install numpy

Install Jupyter notebook using: pip install jupyter

Install Matplotlib using: pip install matplotlib

## Using this repository

git clone https://github.com/Damian404/MNIST-data-sets.git

Then open Jupyter notebook and open clone
