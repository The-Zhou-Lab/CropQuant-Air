# CropQuant-Air

Jiawei Chen<sup>1</sup>, Jie Zhou<sup>1</sup>, Ji Zhou<sup>1,2*</sup>

<sup>1</sup>State Key Laboratory of Crop Genetics & Germplasm Enhancement, Plant Phenomics Research Centre, Academy for Advanced Interdisciplinary Studies, Nanjing Agricultural University, Nanjing 210095, China;

<sup>2</sup>Cambridge Crop Research, National Institute of Agricultural Botany (NIAB), Cambridge CB3 0LE, UK.

•	ChenJiawei@njau.edu.cn
•	JieZhou@njau.edu.cn
•	Ji.Zhou@njau.edu.cn; Ji.Zhou@NIAB.com


## Overview
In this release, we uploaded the latest version of CropQuant-Air, a graphical user interface (GUI, in .exe format) based analytic software that integrate deep learning algorithms and traditional image processing algorithms, directly extract and output yield- and performance-related phenotypic traits, and added the function of batch processing a series of images collected by low-cost drones.

## Relevant publications 
CropQuant-Air: an AI-powered system to enable phenotypic analysis of yield- and performance-related traits using wheat canopy imagery collected by low-cost drones (DOI: 10.3389/fpls.2023.1219983)

## Install Python, Anaconda and Libraries
If you wish to run CropQuant-Air from the code, you will need to set up Python on your system. 

1. Install Python releases:
   
   •	Read the beginner’s guide to Python if you are new to the language: 
   https://wiki.python.org/moin/BeginnersGuide
   
   •	For Windows users, Python 3 release can be downloaded via: 
   https://www.python.org/downloads/windows/
   
   •	CropQuant-Air only supports Python 3

2. Install Anaconda Python distribution:
   
   •	Read the install instruction using the URL: https://docs.continuum.io/anaconda/install
   
   •	For Windows users, a detailed step-by-step installation guide can be found via: 
   https://docs.continuum.io/anaconda/install/windows 
   
   •	An Anaconda Graphical installer can be found via: 
   https://www.continuum.io/downloads

   •	We recommend users install the latest Anaconda Python distribution

3. Install packages:

   • CropQuant-Air uses a number of 3rd-party libraries that you may need to add to your conda environment.
   These include, but are not limited to:
   
       Scikit-image=0.20.0
       Opencv-python=4.7.0.72
       Matplotlib =3.7.1
       Pandas=2.0.1
       Numpy=1.24.2
       Scipy=1.9.1
       Torch=1.11.0+cu113

## Running CropQuant-Air

Before using the software and source code, please see the CropQuant-Air user guide.pdf file on this repository. A compressed Windows (exe format, i.e. CropQuant-Air.zip) file can be downloaded from the release link as well.
