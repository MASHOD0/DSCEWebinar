# DSCEWebinar
this repository has the distribution code to Deeplearning Webinar
# 1. Banknotes 
This is an example of a Artificial Neural Network where you train a neural network to differentiate between originial and counterfeit banknotes.
## Contents
1. banknotes.csv (file containing our dataset)
2. banknotes.py (the python script which generates and tests the model)
3. requirements.txt (the file containing all the libraries to be installed)
## Instructions to run the program
1. make a virtual environment (assuming that you have already installed python on your system) by running this command in your terminal.
```
python -m venv venv
```
3. Activate your virtual environment by running this comand in your terminal
```
source venv/Scripts/activate
```
3. Install the required packages by running this command in your terminal.
```
pip3 install -r requirements.txt
```
4. run the program by executing this command in your terminal.
```
python banknotes.py
```
 # 2. Convolution 
 This is a program which takes .png format picture and returns a convoluted image.
 ## Contents
 1. convolution.py (this file has the program which convolutes the image)
 2. bridge.png (this file has a picture to test the program)
 3. requirements.txt (the file containing all the libraries to be installed)
 
## Instructions to run the program
1. make a virtual environment (assuming that you have already installed python on your system) by running this command in your terminal.
```
python -m venv venv
```
3. Activate your virtual environment by running this comand in your terminal
```
source venv/Scripts/activate
```
3. Install the required packages by running this command in your terminal.
```
pip3 install -r requirements.txt
```
4. run the program by executing this command in your terminal.(you can convolute any other png image you like by saving the image in same directory as ```convolution.py``` and entering the name of the image instead of ```bridge.png``` in your terminal)
```
python convolution.py bridge.png
```
3. Numbers
This is a classic example of a Convolutional Neural Network (CNN) wherein we predict the number drawn on the screen .
## Contents
1. /assets (this directory has the fonts required for the pygame interface)
2. handwriting.py (This is a python script which generates a model)
3. recognition..py (This is a python script which generates a pygame GUI it takes a model as a command line argument based on which it predicts the number drawn)
4. model.h5 (This is a model which can be used to evalute the number drawn, you can pass this as a command line argument in ```recognition.py```)
5. requirements.txt (the file containing all the libraries to be installed)
## Instructions to run the program
1. make a virtual environment (assuming that you have already installed python on your system) by running this command in your terminal.
```
python -m venv venv
```
3. Activate your virtual environment by running this comand in your terminal
```
source venv/Scripts/activate
```
3. Install the required packages by running this command in your terminal.
```
pip3 install -r requirements.txt
```
4. you can create a model (This repository has a ready model which can be used instead) by running this command
```
python handwriting.py (filename)
```
where you are expected to enter name of the model you want to create (file name must end with ```.h5```) 
Note: this might take sometime
5. run the recognition script to get a GUI .
```
python recognition.py model.h5
```
if you have followed step four and created a model enter the name of that model instead of ``` model.h5```
# Contributors 
[Ataa](github.com/ataago) ,
[Mashhood](github.com/MASHOD0)

