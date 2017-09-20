# ENGS108 - Applied Machine Learning
A repository for course materials of [Thayer ENGS108: Applied Machine Learning](https://engineering.dartmouth.edu/academics/courses/engs108)

## Vagrant VM
For this course, we have prepared a virtual machine with [Vagrant](https://www.vagrantup.com/) for your homeworks and projects. The VM has all the necessary python packages installed and should be ready to use once spun up. See the [vagrant page](vagrant/README.md) for instructions on how to set up.   

## Manual Set Up
It has come to our notice that for some Windows machines, the CPUs are unable to support virtualization by our vagrant configuration. In such cases, you should install the packages manually. Three main python packages are essential:
1. [Scikit-Learn](http://scikit-learn.org/stable/)
2. [Tensorflow](https://www.tensorflow.org/)
3. [Keras](https://keras.io/)

[Anaconda](https://www.anaconda.com) will be the best way to install these and many other packages. Follow the following steps to install:

1. Download anaconda for your platform [here](https://www.anaconda.com/download/) and install. Note: for Windows, Tensorflow works for only python3 so be sure to download Python 3.6 version
2. After installation, navigate to Anaconda in start menu and run the *Anaconda Prompt*
3. In the prompt, install Tensorflow with this command: `conda install -c conda-forge tensorflow`
4. Next, install Keras with this command: `pip install keras`
5. All set! You should be able to open iPython in the start menu and run the following:
```python
import tensorflow
import keras
import pandas
import sklearn
```

## Homework Solutions
We will provide iPython notebooks of homework solutions in the [hmw](hwm) directory. Note that these will render right in github and you don't need to download them. However, to run them yourself, you'll have to download and move the `.ipynb` file to `vagrant/notebooks/`.
