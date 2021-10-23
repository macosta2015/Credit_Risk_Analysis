# Credit_Risk_Analysis
Challenge 17 


### Overview of the analysis:
We are going to use different types of machine learning models. We are going to use three different type of machine learning algorithms to see which one is better to predict risk. 

ONE AND TWO
1. Oversampling RandomOverSampler
2. SMOTE
3. Undersampling ClusterCentroids

THREE
1. We now are going to train and compare BalancedRandomForestClassifier and EasyEnsembleClassifier to predict credit risk, both models will then be evaluated.


It is important to note that we have been learning that we have supervised and unsupervised learning. 

### Important General information
#### Libraries: imbalanced-learn and scikit-learn libraries

With machine learning we are able to get a sample data to keep and compare it againts the model. We are going to use different models to check the predictions and aftwerwards check it with our data sample.

 Please note that before starting the work, we first need to read a CSV.file and then check what information is relevant. What data is actually valuable for the model. *As well, plenty of times, we need to transform the data type that we have and even convert it into a numerical form. This is so that the mode is able to read the information. 


### Results: 

#### Balanced Random Forest Classifier

<img width="726" alt="Screen Shot 2021-10-23 at 6 18 46 PM" src="https://user-images.githubusercontent.com/25726054/138573300-0e52d71e-7c4b-4040-855b-38c2fbba9ea1.png">

#### Balanced Random Forest Classifier
<img width="648" alt="Screen Shot 2021-10-23 at 6 19 01 PM" src="https://user-images.githubusercontent.com/25726054/138573306-8843cba6-40dc-4770-8621-7a4f2b394c95.png">


#### Naive Random Oversampling
<img width="644" alt="Screen Shot 2021-10-23 at 6 19 54 PM" src="https://user-images.githubusercontent.com/25726054/138573322-9df82648-ef58-4ec4-ba27-0e6afad39215.png">


#### SMOTE Oversampling
<img width="651" alt="Screen Shot 2021-10-23 at 6 20 16 PM" src="https://user-images.githubusercontent.com/25726054/138573327-461c202b-34a1-4b0b-9bac-03e7d7a82faf.png">

#### Undersampling imbalanced classification report
<img width="644" alt="Screen Shot 2021-10-23 at 6 20 36 PM" src="https://user-images.githubusercontent.com/25726054/138573336-ea33117c-c5a9-4f0f-be00-23c71d1982c0.png">

#### SMOTEEN
<img width="646" alt="Screen Shot 2021-10-23 at 6 20 59 PM" src="https://user-images.githubusercontent.com/25726054/138573343-152eaa6c-0e94-4c8e-b6fb-216ab20fb96d.png">


### Summary:
After testing our supervused machine learning models we are able to know which one was the best by having our traget columns closest to one. Please remember that the ratio needs to be between 0 and 1, (A .99 would be a high accuracy). Again, in order to know which was the best model we need to take a find the balanced accuracy from the different models. 

Our supervised training shows that the best module to use is the Easy Ensemble AdaBoost Classifier with an accuracy of 0.925427358175101
<img width="646" alt="Screen Shot 2021-10-23 at 6 24 10 PM" src="https://user-images.githubusercontent.com/25726054/138573400-c225e433-664b-4664-b52e-be681bfe470f.png">
