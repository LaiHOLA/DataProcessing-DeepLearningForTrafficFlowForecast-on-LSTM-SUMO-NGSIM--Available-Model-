# LSTM Model and Data Segmentation Collaboration: A Deep Learning Strategy for Traffic Flow Anomaly Detection Using SUMO Simulated

Welcome to this catalogue of project exposition files for the author's MSc in Advanced Computer Science at the University of Leeds in 2022/2023.

Feel free to contact the authors if you meet any other situations or have any other comments on this project during its use.
Contact Email:
sc22l2h@leeds.ac.uk (before 2023/11/15)
lai.uk@outlook.com(Long-trem)

This project focuses on training models using SUMO-generated datasets versus real datasets extracted from NGSIM, comparing the two different datasets' judgements of abnormal traffic flows, and thus suggesting the use of SUMO datasets instead of real datasets.

Methods on how to downscale the NGSIM dataset to model inputs are provided in the project, and experimental model files and source data are provided for reference.

You will need to modify the configuration/path files in the code to make it work.

There are three folders in the project, Code Files/Model Files/ Support Data Files.

Code Files contains the methods for training the model and all the functions you will need for this project for SUMO native data processing, NGSIM data processing, result validation, and so on.

The Model Files show the models trained on the real and SUMO datasets used in the final project and contain some experimental models, for information about these experimental models you can contact the authors.

The Support Data Files contain all the files needed for this project, even the extracted NGSIM files. By the name of each folder you can tell for what purpose the files are used, if you need to use these traffic flow files you need to open the .sumocfg file in the txt file editor and change these paths.
The net-files are the maps, the route-files are the traffic flows, which you can merge with the traffic flows folder, and the additional-files are the sensors.
