# LSTM Model and Data Segmentation Collaboration: A Deep Learning Strategy for Traffic Flow Anomaly Detection Using SUMO Simulated

* Welcome to this catalogue of project exhibition files for the author's MSc in Advanced Computer Science at the University of Leeds in 2022/2023.

Please feel free to contact the authors if you encounter any other situations or have any other comments about this project while using it.
## Contact email:

* sc22l2h@leeds.ac.uk (before 2023/11/15)
* lai.uk@outlook.com(long-term)

This project focuses on training models using SUMO-generated datasets versus real datasets extracted from NGSIM, comparing the judgments of the two different datasets on abnormal traffic flows and thus suggesting the use of SUMO datasets instead of real datasets.

Methods for downscaling the NGSIM dataset to model inputs are provided in the project, and experimental model files and source data are provided for reference.

You will need to modify the configuration/path files in the code to make it work.

## Master Project Folder

There are three folders in the project, Code Files/Model Files/ Support Data Files.

### Code Files
it contains the methods for training the model and all the functions you will need for this project for SUMO native data processing, NGSIM data processing, result validation and so on.

### The Model Files
it shows the models trained on the real and SUMO datasets used in the final project and contain some experimental models, for information on these experimental models you can contact the authors.

### The Support Data Files
it contains all the files needed for this project, including the extracted NGSIM files. The name of each folder tells you what the files are for, if you need to use the traffic flow files you will need to open the .sumocfg file in a text file editor and change these paths.
The net files are the maps, the route files are the traffic flows, which you can merge with the traffic flows folder, and the additional files are the sensors.
