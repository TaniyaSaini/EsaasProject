## Synopsis

Equation Solver System is a platform where a student can enter a maths word problem, get an automatic answer and visual explanation generated of both the question and the answer.


## Motivation

A student begins to solve Word Problems in the second grade, and these problems continue till the end of high school. Most students are unable to visualise such problems, and rely on rote learning instead.Finally developing a hatered towards the subject.


## Installation

Download the "Revised Frontend" folder and extract it somewhere.

Install dependencies (assuming you have python3 installed)

sudo pip3 install numpy nltk spacy sklearn pandas flask tensorflow keras h5py

Download external files:

Download dependencies for Stanford POSTagger, and DependencyParser:

Go to the following link: Click Me!, and download & extract the "libs" folder to your "Revised Frontend" directory.

Download models for Spacy:

sudo python3 -m spacy download en

Download NLTK Data (all corpora and packages):

python3
>>> import nltk
>>> nltk.download()
Navigate to your "Revised Frontend" folder with your terminal, and start the Flask server with

python3 linking.py.

Open http://127.0.0.1:5000 in your browser.


## Contributors

Purvanshi Mehta - 101412029 
Taniya Saini - 101412041
Vishruty Mittal - 101412045



## License

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.
