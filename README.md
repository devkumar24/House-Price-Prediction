### Introduction
This repo contains the code for house Price prediction task, I have take the dataset from kaggle, but in my repo push the dataset as well as the submission file which
the output of the test dataset. 

### Step That have been done.
- Step 1 : 
    - The very first step to start any task in Machine Learning is to visualize the data, so first we have load the dataset from the csv files, and start with the visualization of the dataset.

        ```python 
        train_dataset = pd.read_csv('train.csv') # train dataset
        test_dataset = pd.read_csv('test.csv') # test dataset
        sample_submission = pd.read_csv('sample_submission.csv') # sample file submission
        ```
    - Next we will move forward will some of the visualization part, like we plot some various types of plots using matplotlib and seaborn. These 2 libraries are mostly used in the data visualization task. 
    
        So, will start off with plotting the normal distribution curve of our target variable.
        