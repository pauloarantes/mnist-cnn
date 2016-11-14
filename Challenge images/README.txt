Attached is a folder with black and white png images. The task is to predict the number etched in these images (You smell MNIST already?).
The intermediate steps we expect you to perform are:

1: Image pre-processing that takes in an image (plausibly of varying sizes) and finds the right bounding box around the number area in the image (see attached image - BB.png) and scales it down to a 28 x 28 image. You may use OpenCV or pillow or a self-written script.[50 POINTS for algorithm-shopping on OpenCV/Pillow and 75 POINTS for a self-written script]

2a: Feed the image into a pre-trained  MNIST-CNN with binary weights (from here: https://github.com/MatthieuCourbariaux/BinaryNet / https://arxiv.org/abs/1602.02830)
and extract the class-wise-probability-mass-function and the assigned class. [50 points]

2b: In case, you use a standard pre-trained  MNIST-CNN with non-binary weights, the weightage of task-2 is halved (25 points).

You may use the deepnet platform of your choice (Keras/Theano/Caffe/Chainer/TFlow/Torch7). Keras is preferred, but no extra-points or deductions for using the platform of your choice.

The deliverable is a jupyter notebook that showcases your solution along with the pre-trained deep-net model file (hdf5/t7/json) . 
You may use the GLFS (https://git-lfs.github.com/) for uploading the model files. Share the solution on github and e-mail us the link.

The deadline is as mentioned in the e-mail.

Good luck!