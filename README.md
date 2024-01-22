# Unet-Cardiac-Segmentation

The following model contains all the files associated with my U-Net cardiac segmentation project that uses tensorflow and keras. The model segments heart from X-Ray images. See the data section below for more informatoin regarding the dataset.


Data

The original dataset is from kaggle (https://www.kaggle.com/datasets/c7934597/cardiac-catheterization), and I've downloaded it and done the pre-processing.

You can also find it in folder data/membrane.

Data augmentation

The data for training contains 30 512*512 images, which are far not enough to feed a deep learning neural network. I applied data augmentation techniques such as crop, blur, rotate which you can explore further in the preparedata.ipynb file.
