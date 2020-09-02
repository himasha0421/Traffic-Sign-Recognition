# **Traffic Sign Recognition** 


### Below is the depth review of my traffic sign recognition project based on german traffic sign data set .

---

**Build a Traffic Sign Recognition Project**

The goals / steps of this project are the following:
* Load the data set (see below for links to the project data set)
* Explore, summarize and visualize the data set
* Design, train and test a model architecture
* Use the model to make predictions on new images
* Analyze the softmax probabilities of the new images
* Summarize the results with a written report


[//]: # (Image References)

[image1]: ./examples/visualization.jpg "Visualization"
[image2]: ./examples/grayscale.jpg "Grayscaling"
[image3]: ./examples/random_noise.jpg "Random Noise"
[image4]: ./examples/placeholder.png "Traffic Sign 1"
[image5]: ./examples/placeholder.png "Traffic Sign 2"
[image6]: ./examples/placeholder.png "Traffic Sign 3"
[image7]: ./examples/placeholder.png "Traffic Sign 4"
[image8]: ./examples/placeholder.png "Traffic Sign 5"


---


### Data Set Summary & Exploration

#### 1. Provide a basic summary of the data set. In the code, the analysis should be done using python, numpy and/or pandas methods rather than hardcoding results manually.

I used the pandas library to calculate summary statistics of the traffic
signs data set:

* The size of training set is  34799
* The size of the validation set is 4410
* The size of test set is 12630
* The shape of a traffic sign image is  32, 32, 3
* The number of unique classes/labels in the data set is 43

#### 2. Include an exploratory visualization of the dataset.

Here is an exploratory visualization of the data set. It is a bar chart showing how the data distribution is ...

![alt text](https://miro.medium.com/max/798/1*V3H5q1gdemCeMSR19Yto9A.png)

### Design and Test a Model Architecture


#### 3. LeNet5 Model Architecture .

![](https://miro.medium.com/max/4348/1*PXworfAP2IombUzBsDMg7Q.png)
 


#### 4. Model Training Results

![](examples/train.png)
 

### Test a Model on New Images

#### 1. Test out the model with some challenging  images to Handel even with human eyes .

![ ](https://media.springernature.com/lw685/springer-static/image/art%3A10.1007%2Fs10489-013-0425-9/MediaObjects/10489_2013_425_Fig1_HTML.gif)

### Run the notebook your self

1. Download the data set [German Traffic Sign Dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset) . This is a pickled dataset in which we've already resized the images to 32x32. It contains a training, validation and test set.
2. Clone the project, which contains the Ipython notebook and the writeup template.
```sh
git clone https://github.com/udacity/CarND-Traffic-Sign-Classifier-Project
cd CarND-Traffic-Sign-Classifier-Project
jupyter notebook Traffic_Sign_Classifier.ipynb
```
3. Try out with the trained model inside the results folder