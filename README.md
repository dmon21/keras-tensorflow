# keras-tensorflow
Musings with Keras &amp; Tensorflow

# Installing Keras & TensorFlow on Mac OS X
- Using Virtualenv setup & Python 3

$ sudo easy_install pip
$ sudo pip install --upgrade virtualenv 
$ virtualenv --system-site-packages -p python3 <targetDirectory>
where <targetDirectory> identifies the top of the virtualenv tree. I'm assuming that targetDirectory is ~/keras_tf, but choose any directory.
$ source ~/keras_tf/bin/activate # Changes prompt to (keras_tf)$
$ pip3 install --upgrade tensorflow
$ pip install numpy scipy
$ pip install scikit-learn
$ pip install pillow
$ pip install h5py
$ pip install keras

# Activating virtualenv to run code
$ source ~/keras_tf/bin/activate

# Deactivating virtualenv
(tensorflow)$ deactivate 
