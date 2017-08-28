# Self-Driving Car Engineer Nanodegree
# Computer Vision
## Project: Semantic Segmentation applied on road dataset

### Introduction
In this project, I implemented a Fully Convolutional Network (FCN) to label the pixels of a road 

### Results
Here are 2 different images on which the trained FCN has been applied. You can found all the result images in the [runs](https://github.com/Mornor/CarND-Semantic-Segmentation/tree/master/runs/1503860319.698257) folder. <br>
  * Example 1<br>
![output_1](./runs/1503860319.698257/um_000024.png)
  * Example 2<br>
![output_2](./runs/1503860319.698257/um_000054.png)


### FCN architecture


### Discussion 
Talk about parameters to tune, AWS training and kernel_initializer


### Setup
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)
##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training and test images.

### Start
##### Implement
Implement the code in the `main.py` module indicated by the "TODO" comments.
The comments indicated with "OPTIONAL" tag are not required to complete.
##### Run
Run the following command to run the project:
```
python main.py
```
**Note** If running this in Jupyter Notebook system messages, such as those regarding test status, may appear in the terminal rather than the notebook.

### Submission
1. Ensure you've passed all the unit tests.
2. Ensure you pass all points on [the rubric](https://review.udacity.com/#!/rubrics/989/view).
3. Submit the following in a zip file.
 - `helper.py`
 - `main.py`
 - `project_tests.py`
 - Newest inference images from `runs` folder
