# Pytorch-SSD-lite-in-Custom-Dataset
Fine tune a pretrained object detection model applying in Jetson Nano
## How to use
Make a copy of this colab notebook.
- Firstly, make a dataset in the format of COCO. For example, in this data create tab of the notebook, I provided a script to create a dataset from COCOdataset with pedestrian and ground vehicle categories.
- After that, let's begin training by setting up everything we need that i have provided in the Training tab of this notebook, such as installing tensorflow, modifying the model, configuring the parameters of batch_size, worker, and learning rate.
- Finally, I have not yet written a script to evaluate the model, so you can try training for a number of epochs first to test it.
