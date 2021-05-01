# capstone

This is the Capstone project code from my course DS785 for completion requirement for my DS MS degree. The code scripts for this project are broken into Exploratory Data Analysis (EDA) stage and Modeling. The EDA stage contains all the codes related to data cleaning, analysis and data preparation for the product recommendation models created for this project. The modeling stage contains the codes related to the product recommendation models done for the project, along with the code created to test the accuracy of the models. Each code script within the two stages will have a number in front of the name to indicate the order in which they were ran for this project. The first codes that should be used are the ones on the EDA stage, followed by the ones on the Modeling stage. Each stage will have its corresponding folder on this project. There will be one final folder called 'ResultsPrep' which contains the scripts and Tableau workbooks done for showcasing results.

The codes shown in this project were all done on python 3 with the exception of one of the modeling approaches which was the CF ALS model which was done on pySpark. The codes were all created on AWS SageMaker. Tableau software was also used on local machine to create dashboards for displaying the final results from the work. 

The dataset used for this project was gathered from the Kaggle website from the following link: https://drive.google.com/drive/folders/1Nan8X33H8xrXS5XhCKZmSpClFTCJsSpE
The main Kaggle page for the dataset is the following: https://www.kaggle.com/mkechinov/ecommerce-behavior-data-from-multi-category-store
The dataset in Kaggle originally comes from REES46 Marketing Platform : https://rees46.com/

In order to run the codes the data would have to be downloaded from the above mentioned kaggle source and the paths of the codes would have to be changed to point into the location where the files are stored. Given the big volume of data from the chosen dataset, the instances used in AWS SageMaker were of size 'ml.m5.4xlarge' for EDA stage and 'ml.p2.xlarge' for the modeling stage. 
