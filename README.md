# spoken-digits-recognition
Term project for Machine Learning UoT course

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
1. Open spoken-digits-recognition.ipynb or speaker-recognition.ipynb
1. Run all Cells

### Colab Jupyter Notebook
1. Open
1. Upload the CSV files 
1. Run all Cells

## Contents
* data/recordings/*: wav files with English spoken digits from 0 to 9
* src/speaker-recognition.ipynb: Junyper Notebook with Neural Network model able to recognize the speaker of English digits (Jackson, Nicolas or Theo)
* src/spoken-digits-recognition.ipynb: Junyper Notebook with Neural Network model able to recognize English spoken digits
* src/spoken-digits-recognition-RodolfoAnkur.ipynb: Junyper Notebook with Neural Network model able to recognize English spoken digits. Also tests the digits spoken by Ankur and Rodolfo
* src/ankur.csv: Features of Ankur skpoken digits
* src/data.csv: Features of training data skpoken digits
* src/rodolfo.csv: Features of Rodolfo skpoken digits
* src/test.csv: Features of test data skpoken digits

## Recording Data
Training and Test data was downloaded from: 
* https://github.com/Jakobovski/free-spoken-digit-dataset
* https://github.com/moebg/spoken-digit-recognition

Rodolfo and Ankur provided the recordings stored in data/recordings/rodolfo and data/recordings/ankur


