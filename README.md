# Udacity-Capstone-Urban-Sound-Classification-Project
 
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Description](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The code should run with no issues using Python versions 3.x
Below are the key libraries needed beyond the Anaconda distribution of Python.

1. IPython
2. librosa
3. matplotlib
4. scipy
5. sklearn
6. keras

## Project Motivation<a name="motivation"></a>

This is an Udacity Data Science Nanodegree project. I chose Urbansound8K dataset. 

The dataset contains 8732 sound excerpts (<=4s) of urban sounds from 10 classes.
1. Air Conditioner
2. Car Horn
3. Children Playing
4. Dog bark
5. Drilling
6. Engine Idling
7. Gun Shot
8. Jackhammer
9. Siren
10. Street Music

The accompanying metadata contains a unique ID for each sound excerpt along with it's given class name. The full dataset can be downloaded from https://urbansounddataset.weebly.com/urbansound8k.html
Sample data is added to the Github repository.
These sound excerpts are digital audio files in .wav format.

I have built a model which takes a .wav sound file as an input and predict which class it belongs to along with a confidence level. 
This project can be considered as a live prototype in today's world of "IoT" (Internet of Things), where with adequate classified samples of sound bits, the model can be trained to predict class of any sound with high confidence level. 
There are numerous real world use cases which such a model can support. Few intersting examples below: 
1. Getting data on different sort of activities happening at a particular area every day --> e.g. # of priority vehicles (ambulance, police cars) passing every hour, Honking frequency and patterns in an area, # of dogs in each of city areas, etc. 
2. Pro-active Crime control: Auto-Alerting police and an ambulance the GPS locations in case of gun shots 

## File Descriptions <a name="files"></a>

1. Audio: The folder contains sample sound files from the main urbansound dataset segrehated in 10 folders - fold1 to fold 10.
Also it has copyright free sound files downloaded from web in folder "WebSamples" for purpose of validation of prediction
2. metadata: Folder contains the file "UrbanSound8k.csv". This file contains meta-data information about every audio file in the dataset.
3. Capstone_project.ipynb: This is the Jupyter notebook file containing the complete code and related documentation for this project

## Results<a name="results"></a>

The main findings of the code can be found at the [post](https://medium.com/@manishbadwe_34658/an-ultrasound-prediction-168864cbbadc) available

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

1. Must give credit to Udacity courses for some of code ideas, and to weebly.com for the data.
2. Image Courtesy : http://soundfile.sapp.org/doc/WaveFormat/ for the image explaining structure of a wav. file
3. https://en.wikipedia.org/wiki/Mel-frequency_cepstrum reference about MFCC
4. Thanks to http://soundbible.com/ for the copyright free sound files used for validation purpose
5.  https://towardsdatascience.com/methods-for-dealing-with-imbalanced-data-5b761be45a18 for ideas on handling data imbalances
Otherwise, feel free to use the code here as you would like!
