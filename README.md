# keras-tensorflow
Musings with Keras &amp; Tensorflow

# Installing Anaconda & Jupyter Notebook (preferred method)
https://www.continuum.io/downloads#macos

https://jupyter.org/install.html

# Installing Keras & TensorFlow on Mac OS X (alternative method)
- Using Virtualenv setup & Python 3

1. $ sudo easy_install pip [br]
2. $ sudo pip install --upgrade virtualenv 
3. $ virtualenv --system-site-packages -p python3 <targetDirectory>
where <targetDirectory> identifies the top of the virtualenv tree. I'm assuming that targetDirectory is ~/keras_tf, but choose any directory.
4. $ source ~/keras_tf/bin/activate # Changes prompt to (keras_tf)$
5. $ pip3 install --upgrade tensorflow
6. $ pip install numpy scipy
7. $ pip install scikit-learn
8. $ pip install pillow
9. $ pip install h5py
10. $ pip install keras

### Activating virtualenv to run code
$ source ~/keras_tf/bin/activate

### Deactivating virtualenv
(tensorflow)$ deactivate 
