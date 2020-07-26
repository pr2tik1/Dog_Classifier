# Image Classification using Transfer Learning

Used pretrained CNNs and custom CNNs to classify dog images in [project 1](https://github.com/pr2tik1/dog-classifier/blob/master/check_images.py) and dog breeds in [project 2](https://github.com/pr2tik1/dog-classifier/blob/master/dog_app.ipynb). Transfer learning is a popular method in computer vision because it allows us to build accurate models in a timesaving way. These projects were in my Udacity's Nanodegree courses. This can be referred for educational purposes.


Transfer learning is usually expressed through the use of pre-trained models. A pre-trained model is a model that was trained on a large benchmark dataset (ImageNet in this case) to solve a problem similar to the one that we solve. 

## Transfer Learning Notebook
Notebook exploring torchvision pretrained models for image classification.
View [here](https://github.com/pr2tik1/dog-classifier/blob/master/transfer-learning.ipynb)

## [Project 1](https://github.com/pr2tik1/dog-classifier/blob/master/project-1)

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
<img src = "https://github.com/pr2tik1/dog-classifier/project-1/blob/master/pet_images/Beagle_01141.jpg">
</p> 


## [Project 2](https://github.com/pr2tik1/dog-classifier/blob/master/project-2) 
In this prohect objective is to classify dog breeds using pretrained network such as ResNet and custom network architecture for comparable study. Also a exploration using HarCascade from OpenCV for face detection is performed. 
 
<p align = 'center'>
<img src = https://github.com/pr2tik1/pr2tik1.github.io/blob/master/assets/images/5.png>
</p>

## Dependencies:
 - Python 3.6+
 - Pytorch (version 0.4+)
 - OpenCV
 - Jupyter Lab

## Future Works:
   - Increasing Accuracy
   - Using more networks

## Author 
[<img src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white" />](https://twitter.com/Pratikpkb) [<img src="https://img.shields.io/badge/medium-%2312100E.svg?&style=for-the-badge&logo=medium&logoColor=white" />](https://medium.com/@pratikbaitha04)  [<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/pratik-kumar04/) [<img src = "https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white">](https://www.instagram.com/pratikkumar04/) [<img src = "https://img.shields.io/badge/facebook-%231877F2.svg?&style=for-the-badge&logo=facebook&logoColor=white">](https://www.facebook.com/pr2tik1) [<img src ="https://img.shields.io/badge/github.io-web-%23.svg?&style=for-the-badge&logo=&logoColor=white%22">](https://pr2tik1.github.io/)
## References: 
Udacity Deep Learning Nano Degree 

