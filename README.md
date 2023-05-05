# Yun-solutions-assignment
this repository contains my solution for task-1 for round-2 assignment. 

The program uses speech processing techniques to get the pitch and few spectral quantities like spectral centriod, spectral rolloff and spectral flux or intensity. these spectral quantities can be used to fine the tone of the speaker. This program does not use machine learning or deep learning techniques because the input is a single file, whereas the input for the machine learning program should be a big dataset. 

# Requirements
the program uses ffmpeg library for the pydub library which has to be installed

In ubuntu, It can by the following command
`sudo apt-get install ffmpeg libavcodec-extra`
In mac and windows, kindly follow the commands given in the original [source](https://github.com/jiaaro/pydub#installation) of the pydub library. 

Then pydub and aubio library has to be installed using the following commands
`pip install pydub`
`pip install aubio`

These are the requirements for this program and please use **Python 3.8.10** to run the ipynb file.

# Examples
The program uses speech processing techniques as mentioned, in the question. Since, Machine Learning can't used given that only one file is the input for this program. So, I had to get few testcases on which I had tuned the classifier. there are 4 mp3 files for each of the emotions: happy, sad, angry. (Credits:[kaggle](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio?resource=download)) Each of these are in the folders happy, sad, angry respectively. 

To run the examples, please download the entire repository and instead of filename please use filepath

# How to run the program
The way to run the program is given in the file itself.
