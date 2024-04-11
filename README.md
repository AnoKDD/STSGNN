# STSGNN
The source code for Spatial-Temporal Spectral Graph Neural Network 

This is an implementation of 'Learning Specialized Spatial-Temporal Graph Spectral Filters for Traffic Flow Forecasting'


* ## Dataset
The datasets used in our paper are collected by the Caltrans Performance Measurement System(PeMS). Please refer to [STSGCN (AAAI2020)](https://github.com/Davidham3/STSGCN) for the download url.


## Requirements

Python 3.6.5, Pytorch 1.1.0, Numpy 1.16.3, argparse and configparser



To replicate the results in PEMSD4 and PEMSD8 datasets, you can run the the codes in the "model" folder directly. If you want to use the model for your own datasets, please load your dataset by revising "load_dataset" in the "lib" folder and remember tuning the learning rate (gradient norm can be used to facilitate the training).

Please cite our work if you find useful.
