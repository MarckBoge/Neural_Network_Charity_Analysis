# Neural_Network_Charity_Analysis


## Overview

Alphabet Soup is a nonprofit philanthropic foundation dedicated to helping organizations that protect the environment, and improving the lives of the less fortunate. They have tasked us with the assignment to analyze the impact of each donation and vet potential recipients. This will ensure that the foundation's money is being used effectively. But we do live in a inperfect world and not every donation the foundation makes is used in the correct way. In some cases, an organization will take the money and disappear. Alphabet Soup has ask us to predict which or organizations are worth donating to and which are too high risk.


In this analysis we learned and applied:

  •How to build a basic neural network
  
  •Preprocess/prepare the datasets
  
  •Create a training and testing set
  
  •Measure model accuracy
  
  •Add additional neurons and hidden layers to optimize the model
  
  •Select the best model to use for our dataset
  
  
## Results


### Data Preprocessing


  * What variable(s) are considered the target(s) for your model?
  
         IS_SUCCESSFUL-was the money used effectively
         
         
  * What variable(s) are considered to be the features for your model?

         APPLICATION_TYPE -Alphabet Soup application type
         AFFILIATION -Affiliated sector of industry
         CLASSIFICATION -Government organization classification
         USE_CASE -Use case for funding
         ORGANIZATION -Organization type
         STATUS—Active status
         INCOME_AMT—Income classification
         SPECIAL_CONSIDERATIONS—Special consideration for application
         ASK_AMT—Funding amount requested
         
   * What variable(s) are neither targets nor features, and should be removed from the input data?

         EIN and NAME—Identification columns


### Compiling, Training, and Evaluating the Model

    * How many neurons, layers, and activation functions did you select for your neural network model, and wh        

    * Were you able to achieve the target model performance?

    * What steps did you take to try and increase model performance?
    
    
 ## Summary
 
 
In summary, our model and various optimizations did not help to achieve the desired result of greater than 75%. With the variations of increasing the epochs, removing variables, increasing/decreasing the neurons, the changes were minimal and did not improve above 19 basis points. In reviewing other Machine Learning algorithms, the results did not prove to be any better. For example, we had a predictive accuracy rate of 71.90% which is a 0.56% decrease from the accuracy rate of the Deep Learning Neural Network model 72.46% with the last accuracy reading at 72.38%.
 
Overall Neural Networks are very complex and would require experience through trail and error or many iterations to discover the perfect configuration to setup the dataset.
    
    
    
