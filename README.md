# Distracted_Driver_Detection
A CNN based Deep Learning Project to predict the behavior of the driver

## PROJECT OVERVIEW

According to the CDC motor vehicle safety division, one in five car accidents is caused by a distracted driver. Sadly, this translates to 425,000 people injured and 3,000 people killed by distracted driving every year.

State Farm hopes to improve these alarming statistics, and better insure their customers, by testing whether dashboard cameras can automatically detect drivers engaging in distracted behaviors.
This Project aims to implement a model which will help in predicting the behavior of the driver.

In this project, we will implement an algorithm that could be used to detect the behavior of the driver based on the images provided by the dashboard camera of the Car. At the end of this project, our code will accept the test-images provided by the State Farm and after analyzing the mage, it will predict the probability of various behaviors that driver in the image is engaged in. For example the program will predict that a driver in the image is engaged in safe driving with probability of 0.5, talking to passenger with a probability of 0.3 etc.

## PROJECT HIGHLIGHTS

For this Capstone project we will develop a Deep learning agent to address the challenge presented by the State Farm on the Kaggle to predict the behavior of the driver from the image provided by the dashboard camera of the car. 

Given a dataset of 2D dashboard camera images, our aim is to classify the behavior of the driver in the image and predict whether they are driving attentively, wearing their seatbelt,   taking a selfie with their friends in the backseat, or involved in any other distracted behavior. This program can be used to alert the drivers whenever they are getting engaged into any distraction while driving.

We will try to solve it using the Keras CNN with Tensorflow as the backend, since CNN works great in general for image classification problems. Depending on the performance of the CNN, we may need to fine tune the parameters and implement other techniques like transfer learning to improve the performance of the model and save on training time. After loading and splitting the data we will also need to create the 4D Tensor arrays of the images provided in the dataset as Keras CNN requires 4D arrays.

The final model is expected to achieve a score so that it is in top 50% of the Public Leaderboard submissions in Kaggle.

## PROJECT INSTRUCTIONS

1. Clone the repository and navigate to the downloaded folder.
```
git clone https://github.com/Akshat2127/Distracted_Driver_Detection.git
cd Distracted_Driver_Detection
```
2. Download the data

    Input files Datasets are provided by the State farm for this problem and can be found on Kaggle at the given link - https://www.kaggle.com/c/state-farm-distracted-driver-detection/data. Unzip the folder and place it in the repo, at location `path/to/Distracted_Driver_Detection/Data`.

    driver_imgs_list.csv.zip - A list of training images, their subject (driver) id, and class id - 

    imgs.zip - zipped folder of all (train/test) images 

    sample_submission.csv.zip - A sample submission file in the correct format

3. Take a look at the files in the directory to better understand the structure of the project.
    `Distracted_Driver_Detection.ipynb - this file contains the source code`
    
    `Proposal.pdf - Project proposal before working on the project`
    
    `Report.pdf - Project report created after the project completion`
    
    `Submissions/ - this folder contains the screenshots of the obtained scores for the Kaggle submissions`
    
    `Saved_models/ - this folder contains the models with best weights from different trainings of the model`
    `other helper files`
    
    This submission does not include the bottleneck features obtained during model refinement process as the size of those files exceeds the permissible size by a lot.

4. This project has been developed on windows machine using Keras and Tensorflow-GPU libraries along with other standard packages like numpy, pandas and few others. Create your runtime environment accordinglt before running the project.

5. Activate the enviornment created to run this project

6. Open the notebook.

    jupyter notebook Distracted_Driver_Detection.ipynb.ipynb
    
    Before running code, change the kernel to match the environment by using the drop-down menu (Kernel > Change kernel > <environment>). Then, follow the instructions in the notebook.
