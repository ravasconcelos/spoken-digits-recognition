# spoken-digits-recognition

University of Toronto School of Continuing Studies

Term project for Machine Learning course

Group: Ankur Tyagi, Haitham Alamri, Rodolfo de Andrade Vasconcelos

Professor: Matthew MacDonald

## Presentation
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/_FXqysbYVGs/0.jpg)](https://www.youtube.com/watch?v=_FXqysbYVGs)

## Business Problem
* Inference of the digits as said by users on phone
* Biometric authentication using speech dataset

## Prerequisites
1) if running locally, have Python 3.7 and Junyper installed

## How to run

### Local Jupyter Notebook
1. clone this repository
1. ensure you have the correct version of the Python libraries stated in the file src/lib_version
Example: 
```
python -m pip install -U <library>==<version>
```
1. Run junyper nootebook
```
junyper notebook
```
1. Open src/spoken-digits-recognition.ipynb or src/speaker-recognition.ipynb
1. Run all Cells

### Colab Jupyter Notebook
1. Open
1. Upload the CSV files 
1. Run all Cells

## Contents
* README.md: This file, explaining the project
* UofT_Final_project.pdf: Project presentation in PDF format
* UofT_Final_project.pptx: Project presentation in Power Point format
* spoken_digits_comparison.pdf: Recordings comparisson for each digit for the six speakers

* data/*: wav files with English spoken digits from 0 to 9

* src/lib_version: Python libraries version used in this project
* src/more_test.csv: Features of the files in data/recordings/moreSpeakersTest
* src/more_train.csv: Features of the files in data/recordings/moreSpeakersTrain
* src/speaker-recognition.ipynb: Junyper Notebook with Keras Neural Network model able to recognize the speaker of English digits (Jackson, Nicolas, Theo, Ankur, Caroline and Rodolfo)
* src/speaker-recognition.pdf: PDF version of an execution of speaker-recognition.ipynb
* src/spoken-digits-recognition.ipynb: Junyper Notebook with Neural Network model able to recognize English spoken digits
* src/spoken-digits-recognition.pdf: PDF version of an execution of spoken-digits-recognition
* src/test.csv: Features of the files in data/recordings/test
* src/train.csv: Features of the files in data/recordings/train

## Recording Data
The files stored in data/recordings/test and data/recordings/train were downloaded from FSDD [Ref 1 and 2]: 

Ankur, Caroline and Rodolfo provided the recordings stored in data/recordings/moreSpeakersTest and data/recordings/moreSpeakersTrain

## References
1. https://github.com/Jakobovski/free-spoken-digit-dataset
2. https://github.com/moebg/spoken-digit-recognition


