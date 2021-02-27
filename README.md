# LeNet-5-PyTorch-text-recognition
A PyTorch implementation of  Y. LeCun, L. Bottou, Y. Bengio, and P. Haffner. Gradient-based learning applied to document recognition

The model has 259.2kB and a 99.9% of precision on the given dataset (numbers 1 to 9, letters A to Z).

Really simple text was given to train (you can check it at the end of the notebook) in a total of 12.284 images, 9.796 for training, 2.486 for validating. 

Time to classify: ~1.05ms on cuda (tested and trained on 1050ti 4gb vram).
