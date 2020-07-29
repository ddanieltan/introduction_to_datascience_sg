# About this book
Hello, my name is Daniel and I'm a Data Scientist based in Singapore. 

## How to code along
The best way to learn the following lessons will be to code alongside the examples and have a go at completing the exercises.

There are 2 options to access the code.

### Option A: Clone the git repository
If you have some coding experience, this is the recommended option. You will need to have Python 3 installed on your system. From the terminal, run the following commands.
```bash
git clone http://ddanieltan.github.io/introduction_to_datascience_sg/

conda create -n myenv
conda activate myenv
conda install --file requirements.txt
```
This will clone this project's code into a local folder and install the project's dependencies.
Following which, you can interact the code by starting a local jupyter notebook or jupyterlab instance.

### Option B: Binder link
On every notebook, you'll notice a binder link like so.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ddanieltan/introduction_to_datascience_sg/master?urlpath=lab)

Clicking on the link will open a new tab in your browser that after a short startup time, give you access to a cloud-hosted instance of jupyterlab.
From there, you can access and run the code directly from your browser.
This is nice, fuss-free way of running the code without installing additional software in your computer making this option a useful way of conducting a workshop for a larger group of students. But the drawback is that you won't be able to save a local copy of the code.