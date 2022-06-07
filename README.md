# Pytorch-SSD-lite-in-Custom-Dataset
Fine tune a pretrained object detection model applying in Jetson Nano
## How to use
- Make a copy of this colab notebook.
- Firstly, make a dataset in format of COCO. For example, in this Data create tab of the notebook, i provided a script to create a dataset from COCOdataset with pedestrian and ground vehicle category.
- After that let's begin training by setting up everything we need that i have provied in Training tab of this notebook such as install tensorflow, modify the model, config the param of batch_size, worker and learning rate.
- Finally, i'm not yet write a script for evaluate the model so you can try training for a number of epochs first to test it.
