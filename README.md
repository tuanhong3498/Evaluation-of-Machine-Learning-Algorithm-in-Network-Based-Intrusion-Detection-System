# Evaluation-of-Machine-Learning-Algorithm-in-Network-Based-Intrusion-Detection-System
This repository provides the source code of the experiments conducted in "Evaluation of Machine Learning Algorithms in Network-Based Intrusion Detection System" (A thesis submitted for the degree of Bachelor of Engineering in Software Engineering (Honours) in Xiamen University Malaysia)

The following of this file provides information on how the files are organized and instruction to execute the Jupyter Notebook. 

## Organization of Files
The notebooks in this repository are organized in a similar structures as Chapter 4 in the thesis. The files are seperated into two folders, according to the dataset that is used for the experiment. In each folder, there are five notebooks, each for one step of the experiment processes as descirbed in Chapter 3 of the thesis. The results of each notebook are further discussed in corresponding subchapter of Chapter 4.

## Instruction to run the notebook
The output of execution results are available in the notebook. In case some would like to run the notebooks on their own, please take note of the following:

1. **In this experiment, three IDS datasets are used but they are not uploaded to this repository due to the size constrain.**
   
   The datasets that are used for this work and its source are listed below (please note that the datasets are created by other studies and is not part of this work):
   
   #### CIC-IDS2017 dataset
   source: https://www.unb.ca/cic/datasets/ids-2017.html

   #### CSE-CIC-IDS2018 dataset
   source: https://registry.opendata.aws/cse-cic-ids2018/
   
   #### LUFlow dataset
   source: https://github.com/ruzzzzz/LUFlow
   
   *note: In our experiment that use the LUFlow dataset, we only use the data collected in July 2020 and January 2021 for experiment*
   
   
2. **Make sure to organize the dataset as follow (otherwise, modify the first notebook of each experiment):**

   *Note: place the CSV files of the dataset in the location specified in the table below*
   
   |Dataset|Location|
   |-|-|
   |CIC-IDS2017|`/CIC/Dataset/CIC-IDS2017`|
   |CSE-CIC-IDS2018|`/CIC/Dataset/CSE-CIC-IDS2018`|
   |LUFlow (July 2020)|`/LUFlow/Dataset/LUFlow`|
   |LUFlow (January 2021)|`/LUFlow/Dataset/LUFlow_2021`|



3. **For step 4 and 5, user should manually copy the optimal hyperparameters of each models from the step 3's notebook**

4. **The software environment that has been used for successful execution of the notebook:**
   
   conda 4.10.1, based on Python 3.8.8
   
   *If the notebook failed to run, please check if it is caused by the version of the libraries that is used in this work*
   
   |Library     |Version|
   |------------|-------|
   |scikit-learn|0.24.1 |
   |pandas      |1.2.4  |
   |NumPy       |1.20.1 |
   Matplotlib   |3.3.4  |
   
