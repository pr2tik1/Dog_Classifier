# Image Classification using Transfer Learning

Used pretrained CNNs and custom CNNs to classify dog images in project 1 and dog breeds in project 2. Transfer learning is a popular method in computer vision because it allows us to build accurate models in a timesaving way. These projects were in my Udacity's Nanodegree courses.

## Transfer Learning Notebook
Notebook exploring torchvision pretrained models for image classification.
View [here](https://github.com/pr2tik1/dog-classifier/blob/master/model-exploration.ipynb)

## [Project 1](https://github.com/pr2tik1/dog-classifier/tree/master/project-1)

CNNs used :
  - VGG16
  - AlexNet
  - ResNet
  
### Usage
Run following scripts:
1. First change the directory and add image in the uploaded_images folder if you want,
2. Run the following script
```
./run_models_batch_uploaded.sh
```

If the permission denied error shows up run the following before step 2

```
chmod u+r+x run_models_batch_uploaded.sh
```

### Images
<p align = "center">
<img src = "https://github.com/pr2tik1/dog-classifier/blob/master/project-1/pet_images/Basenji_00974.jpg">
</p> 


## [Project 2](https://github.com/pr2tik1/dog-classifier/blob/master/project-2) 
In this prohect objective is to classify dog breeds using pretrained network such as ResNet and custom network architecture for comparable study. Also a exploration using HarCascade from OpenCV for face detection is performed. 
 
<p align = 'center'>
<img src = https://github.com/pr2tik1/dog-classifier/blob/master/uploaded_images/dog.jpg>
</p>

## Dependencies:
 - Python 3.6+
 - Pytorch (version 0.4+)
 - OpenCV
 - Numpy

## Future Works:
   - Increasing Accuracy
   - Using more networks

## References: 
Udacity Deep Learning Nano Degree 