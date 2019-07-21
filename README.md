# OpenCV Python Tutorials

Hi! This project is using `Jupiter Notebook` implementing `OpenCV-python` to test the basic functions of `OpenCV` on Python 3.7.3 using official tutorials.


## Table of content

-   [Virtualenv installation](https://github.com/lalapupa/compvis/blob/master/README.md#virtualenv-installation)
-   [OpenCV-Python installation](https://github.com/rougier/numpy-tutorial#the-game-of-life)
-   [Tutorials](https://github.com/rougier/numpy-tutorial#exercises)
-   [Additional information](https://github.com/rougier/numpy-tutorial#quick-references)

Sources are available from  [github](https://github.com/lalapupa/compvis#opencv-python-tutorials).
Tutorials are implemented from the official [OpenCV website](https://docs.opencv.org/4.1.0/d6/d00/tutorial_py_root.html).

## Virtualenv installation

We need a virtual environment in order for each individual project to have its own “room” with its own versions of installed libraries, which will not depend on other projects and be confused with each other.

Packages will be installed using [pip.](https://pypi.org/project/pip/)  It comes with Python right away, but usually you need to update it with the command:
`python -m pip install --upgrade pip`  

To install virtual environment run:
`pip install virtualenv`  

Type `cd` and go to the folder where you want to place your virtual environment and run the command 
`mkdir opencvtutorial_env` — where ```opencvtutorial_env``` is a name of our environment.  
Let's activate it!
`.\opencvtutorial_env\Scripts\activate`

## OpenCV-Python installation

We need obviously ***OpenCV-Python*** and also ***Numpy*** and ***Matplotlib***, to go along the tutorials. 
The easiest way for me was to install OpenCV from not official [version](https://pypi.org/project/opencv-python/). Just run the command: 
`pip install opencv-python`  and you will get what you want + Numpy!
It remains only to install Matplotlib with the following command:
`pip install matplotlib`.

## Tutorials

I followed the tutorials and placed them to this repository sometimes with additional comments. The title of each tutorial is named accordingly and marked with numbers by the order. I hope this may help you. If any questions, don't hesitate to ask me!

## Additional information

This section is for the further updates.
