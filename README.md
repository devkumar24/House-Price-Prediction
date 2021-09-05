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
    
        - So, will start off with plotting the normal distribution curve of our target variable.

            We have created a barplot using seaborn, and finds that our target variable is not in normal distribution, and we have seen its QQplot, finds that our target variable is in positive skewed.


            ![normal distribution](/plots/normal_distribution_target_var.png) 
                
            This plot shows Normal Distribution of Sale Price


            ![skewness in target variable](/plots/skewness_target_var.png)
              
            It shows that our target variable has +ve skewness


            - Now, we will solve this problem using log transformation of the data, which result in the normal distribution of the data.

                ![log transformation of target variable](/plots/improve_normal_dist.png)
                
                We have normally distributed data using log transformation of data.


        - Next, we will see the co-relation of our data, as this is important part of the data, it will tell us which features are more important in the dataset.



                
        