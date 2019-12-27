# OrgaSwell
Automated microscopy-image analysis using a deep-learning model, particle tracking and  regression  to  quantify  swelling  of mini-organs.

# Description
This repository contains a multistep algorithm to detect swelling of mini-organs (organoids) in subsequent microscopy images. All notebooks are specifically written for deployement using [Google Colab](https://colab.research.google.com). First, organoids are detected using the [organoid_recognition.ipynb](./organoid_recognition.ipynb) notebook. In this notebook, a pre-trained neural network [OrgaQuant](https://github.com/TKassis/OrgaQuant), described in this [open-access paper](https://www.nature.com/articles/s41598-019-48874-y), is used for organoid detection of image uploaded to google drive. In a second [organoid_recognition.ipynb](./post_processing.ipynb), we use particle tracking to track organoid movement over the subsequent microscopy images. Next, we use linear regression to quantify swelling of each organoid. 

 
