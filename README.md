# CEST Analyzer

## Introduction
CEST Analyzer is the software for B0 correction and generating MTR map of CEST (Chemical Exchange Saturation Transfer) images.

![img1](./readme/Screenshot1.png)

## Features
 - Support various B0 correction methods: Spline correction, Lorentzian correction, [IDE-LF](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6173788/) 
 - CEST mapping: MTR_assymmetry mapping, MTR_Rex mapping, PTR mapping
 - SNR mapping
 - Export processed images as NiFTI file: Z-spectrum, MTR

## Requirements
 - Python3
 - Numpy
 - OpenCV, PIL, scikit-image
 - Pydicom, Nibabel
 - matplotlib

## Installation
    $ git clone https://github.com/kim01414/CEST_Analyzer

## How to Use
When you downloaded files and installed all requiremnts, then running:
    
    $ python main.py

CEST Analyzer must need RF frequency offeset file to handle CEST images. (ex) offset.txt.

    128
    64
    32
    16
    0
    -16
    -32
    -64
    -128
![img2](./readme/Screenshot2.png)

## Screenshot

![img3](./readme/Screenshot3.png)

## Contacts
techman011@gmail.com

[BMRLab](http://bmr.knu.ac.kr/)
