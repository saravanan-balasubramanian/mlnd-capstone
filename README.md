# CNC Mill Tool Wear Predictive Analysis and Building Closed-Loop Control System
Capstone project for Udacity Machine Learning Nanodegree

### Dataset Link

* [CNC Mill Data from Kaggle](https://www.kaggle.com/shasun/tool-wear-detection-in-cnc-mill/home)

### Software Requirements

Python version: 3.6.2

The software requirements are mentioned in the `requirements.txt`
 file in top level directory. To install these dependencies, use 
 the command:-
 
```pip3 install -r requirements.txt```

<br>
The installation of SciPy would fail on Windows because of absence of
Numpy + MKL. To install dependencies on windows, follows the steps:-

1. Download NumPy + MKL for the mentioned python version from [here](http://www.lfd.uci.edu/~gohlke/pythonlibs/#numpy).
2. Remove the Numpy's entry from `requirements.txt`.
3. Run the command: ```pip3 install -r requirements.txt```.

### Running the software

To run the software, navigate to the top level directory and type

```jupyter notebook cnc_mill.ipynb```