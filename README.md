# Introduction

This Project is a Simple Language Translator Application that translates Sentences from French to English with a Decent Accuracy


# How to Use

All Of the Work (i.e - Training and Testing of the Data) regarding this Project is done in Kaggle Notebook

There are two files provided here :-
1) neural-machine-translator.ipynb
2) application-of-model.ipynb

STEP 1 :- Initially we have to RUN the "neural-machine-translator.ipynb" 		    file where we have to provide the PATH to the "fra.txt" file in the variable "filename", then run the file.

STEP 2 :- After the Model is created we will get Two Important Files. One is "english-french.pkl" where the Text data is convert to Byte Stream and saved and another "english-french-both.pkl" which contains a fraction of the data from "english-french.pkl" and is used for Training.

STEP 3 :- After the Training of the Model is completed then the Architecture of the Neural network will be save in the "model.json" file and the Training Parameters will be saved in the "model.h5" file.

STEP 4:- To Check the Model against User Input we need to use the "application-of-model.ipynb" file, this file requires "model.json", "model.h5" and "english-french-both.pkl" in order to generate translation for User Input.

STEP 5 :- We need to provide the FILE PATH of the above mentioned files in STEP 4 to the variables accordingly, then RUN it.

STEP 6 :- To Check against User Input, we have to provide a sentence in French to the frnch_eng(), which will render the corresponding English Translation
