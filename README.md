# Distracted_Driver_Detection
A CNN based Deep Learning Project to predict the behavior of the driver

Input files Datasets are provided by the State farm for this problem and can be found on Kaggle at the given link - https://www.kaggle.com/c/state-farm-distracted-driver-detection/data 

driver_imgs_list.csv.zip - A list of training images, their subject (driver) id, and class id - 
imgs.zip - zipped folder of all (train/test) images 

sample_submission.csv.zip - A sample submission file in the correct format

Keras and Tensorflow-GPU libraries have been used to for the most par of this project along with other standard packages like numpy, pandas and few others.

Submission includes the saved models from the training under the folder saved_models.

Submissions folder includes the .csv files obtained after the prediction and submitted to kaggle.

Same folder also contains the screenshot of the obtained scored from the submissions.

This submission does not include the bottleneck features obtained during model refinement process as the size of those files exceeds the prmissible size by a lot.
