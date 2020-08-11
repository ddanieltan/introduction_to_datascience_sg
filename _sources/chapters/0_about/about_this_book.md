# About this book
**Introduction to Data Science SG** is a free, online textbook that covers introductory topics under Data Science and Machine Learning. What makes this book special is our usage of uniquely Singaporean datasets. 

In this book, you'll learn:

## About me
Hello, my name is Daniel and I'm a Data Scientist based in Singapore. 

## How use this book
The best way to use this book is to code alongside the examples and have a go at completing the exercises.

There are 2 options to access the code.

### Option A: Binder link
On every notebook, you'll notice a binder link like so.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ddanieltan/introduction_to_datascience_sg/master?urlpath=lab)

Clicking on the link will open a new tab in your browser that after a short startup time, give you access to a cloud-hosted instance of jupyterlab.
From there, you can access and run the code directly from your browser.

Option A is nice, fuss-free way of running the code without installing additional software in your computer. This option is particularly useful when conducting a 1-off workshop for a larger group of students as we can begin coding without spending time to setup.
However, the drawback of this option is that you won't be able to save a local copy of the code.

### Option B: Local coding environment
If you have some coding experience or are willing to spend slightly more time to set up, Option B is for you. Option B has the added benefit of allowing you to save a local copy of your all notes and exercises.

As a pre-requisite, you will need Python 3 and a few Python libraries installed on your system. A very convenient way to install these software is to use the Anaconda distribution. Visit [the Ananconda Installation page](https://docs.anaconda.com/anaconda/install/) for instructions specific to your OS.

Next, you can create a local copy of the entire code base on your computer with the following terminal command.
```bash
git clone http://ddanieltan.github.io/introduction_to_datascience_sg/

```
If you've installed the Anaconda distribution, you will have all the neccesary libraries for our lessons. Otherwise, if you chose not to use the Anaconda distribution, you can install the required libraries manually using the following command.
```
pip install -r requirements.txt
```
Finally, you can start a `jupyter lab` or `jupyter notebook` session to begin using this book.

## License
The contents of this book are licensed for free consumption under the following license:  
[Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/).