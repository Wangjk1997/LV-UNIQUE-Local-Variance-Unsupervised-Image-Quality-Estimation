# UNIQUE-Unsupervised-Image-Quality-Estimation

This is a demonstration of the algorithm described in the paper ["UNIQUE: Unsupervised Image Quality Estimation"](https://ghassanalregibdotcom.files.wordpress.com/2016/10/temel2016_spl1.pdf). Given an original and a distorted image, UNIQUE gives out a score 
that approximates the perceptual quality of the distorted image. The score lies between 0 and 1 (1 being the best quality).

You can change this program as you like and use it anywhere, but please refer to its original source ([cite](https://ghassanalregibdotcom.files.wordpress.com/2016/10/can_spl2016-bib.zip) our [paper](https://ghassanalregibdotcom.files.wordpress.com/2016/10/temel2016_spl1.pdf) and our web page at
https://ghassanalregib.com/unique-unsupervised-image-quality-estimation/).

### Usage :

Run the demo.m file. 

### ABSTRACT 

In this paper, we estimate perceived image quality using sparse representations obtained from generic image databases through an unsupervised learning approach. A color space transformation, a mean subtraction, and a whitening operation are used to enhance descriptiveness of images by reducing spatial redundancy; a linear decoder is used to obtain sparse representations; and a thresholding stage is used to formulate suppression mechanisms in a visual system. A linear decoder is trained with 7 GB
worth of data, which corresponds to 100,000 8x8 image patches randomly obtained from nearly 1,000 images in the ImageNet 2013 database. A patch-wise training approach is preferred to maintain local information. The proposed quality estimator UNIQUE is tested on the LIVE, the Multiply Distorted LIVE, and the TID 2013 databases and compared with thirteen quality estimators. Experimental results show that UNIQUE is generally a top performing quality estimator in terms of accuracy, consistency, linearity, and monotonic behavior.

### UNIQUE : UNSUPERVISED IMAGE QUALITY ESTIMATION

The learnt filter weights and the results of the algorithm :

![UNIQUE Filters](/Images/Visualization.png)  
![Results Filters](/Images/Results.png)

### Citation

@ARTICLE{7546870, 
author={D. Temel and M. Prabhushankar and G. AlRegib}, 
journal={IEEE Signal Processing Letters}, 
title={UNIQUE: Unsupervised Image Quality Estimation}, 
year={2016}, 
volume={23}, 
number={10}, 
pages={1414-1418}, 

doi={10.1109/LSP.2016.2601119}, 
ISSN={1070-9908}, 
month={Oct},}


