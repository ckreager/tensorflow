Testing out "classify images" from https://www.tensorflow.org/beta/tutorials/keras/basic_classification

If you recieve the following error, it could be and incompleate dataset from failed download attempt.
  EOFError: Compressed file ended before the end-of-stream marker was reached
Resolution:
Remove incomplete downloads for the MNIST dataset directory.
Mac: Perform the following steps in the terminal (ctrl + alt + t):

  1. cd ~/.keras/datasets/
  2. rm -rf "dataset name" 