Deep Learning
===============

1) Run all the cells in load_data.ipynb to download the data and
generate the pickle file with data structured suitably for training.

2) Successful run of the above specified notebook will result in a file
SVHN_multi_48.pickle in the current directory.

3) Run svhn_multi.py to train the model.

4) The model reports training and validation accuracy for every 10 steps
and finally the test accuracy.

5) Also, training summary are generated in a directory ./logs which can be visualized
by running 'tensorboard --logdir=./logs' and pointing the browser at http://localhost:6006/

Software requirements:
========================
Python 2.7
Jupyter
numpy
scipy
pandas
matplotlib
tensorflow
