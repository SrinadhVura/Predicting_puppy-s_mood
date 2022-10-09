This document provides a walkthrough the files of this repository:

1.images --> This is the directory containing three sub directories Happy, Relaxed, Sad each containing corresponding images.

2.Dog_Emotions_DL.ipynb --> This is a jupyter source file containing the code regading the data framing, Neural Network training, Neural Network testing, Insights

3.cnmod.pth --> This is the pretrained model which can be loaded and run to skip the general training process which takes around 5 days on a general CPU based machine and around 15 hours on a GPU powered CPU
NOTE::: The pretrained model works well on CUDA framework (NVIDIA graphics card) and general CPU. But doesn't work on a MPS framework GPU powered systems (APPLE MAC) 
