# Rotational Rectification Network: Enabling Pedestrian Detection for Mobile Vision

This repository contains the official implementation of the paper titled "Rotational Rectification Network: Enabling Pedestrian Detection for Mobile Vision".

## Requirements

- Python 3.7+
- PyTorch 1.5.0+
- OpenCV 4.2.0+
- NumPy   
- Tensorflow  
- Matplotlib
- Numpy       
- Imaug      
- Datetime  
- Math      
- Pickle   
- Keras  
- Random
- Pandas
- Cv2
- Plotly
- Ipython
- Scipy
- Imutils

## Code Structure

- annotation_csv_files/: Contains the annotations.
- rotation_estimation_model.py: Script to perform Global polar pooling for pedestrian detection
- CNN_on_Rotated_MNIST.ipynb: CNN on rotated MNIST
- spatial_transformer.ipynb: STN+CNN on rotate MNIST
- CNN_on_mnist_caltech.ipynb: To get results of CNN on rotated Caltech
- GP_rotation_estimation_model: To obtain results for GP Pooling operator
- bounding_Box-warped-images.ipynb: To get Bounding Box on warped images
- rotated-image-annotation.ipynb: Bounding box on rotated caltech

## Link to the pedestrian dataset
[https://www.kaggle.com/datasets/kalvinquackenbush/caltechpedestriandataset](https://www.kaggle.com/datasets/kalvinquackenbush/caltechpedestriandataset)

## Other requirements to run the code

- All the files uploaded should be in the same directory.
- Atleast GPU P100 is required for the training of CNN on rotated Caltech 

## Contact
For any questions or inquiries, please contact cvgroup1@skiff.com.
