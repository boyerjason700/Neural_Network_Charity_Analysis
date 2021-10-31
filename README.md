# Neural_Network_Charity_Analysis

# Overview
Alphabet Soup, a nonprofit philanthropic foundation dedicated to helping organizations that protect the environment, improve peoples well-being, and unify the world.  Alphabet Soup has raised and donated over 10 billion dollars in the past 20 years.  This money has been used to invest in lifesaving technologies and organize reforestation groups around the world.  
<br>
Our job is to analyze the impact of each donation and vet potential recipients.  This helps ensure that the foundation's money is being used effectively.  Unfortunatly, not every donation the company makes is impactful.  In some cases an organization will take the monay and disappear.  We have been asked to predict which organizations are worth donating to and which are too high risk. 
<br>

Using Machine Learning and Neural Networks, create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

# Results

## Data Preprocessing
- **What variable(s) are considered the target(s) for your model?**
    - IS_SUCCESSFUL-was the money used effectively 
    
- **What variable(s) are considered to be the features for your model?**
    - APPLICATION_TYPE -Alphabet Soup application type
    - AFFILIATION -Affiliated scetor of industry
    - CLASSIFICATION -Government organization classification
    - USE_CASE -Use case for funding
    - ORGANIZATION -Organitiation type
    - STATUS—Active status
    - INCOME_AMT—Income classification
    - SPECIAL_CONSIDERATIONS—Special consideration for application
    - ASK_AMT—Funding amount requested
    
- **What variable(s) are neither targets nor features, and should be removed from the input data?**
    - EIN and NAME—Identification columns
    

## Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
    - Attempt # 1
        - Used original model neurons, layers, and activation functions-changed bin sizes
    - Attempt # 2
        - Increased to 3 hidden layers
    - Attempt # 3
        - Changed activation functions to linear, relu, and tanh
    - Attempt # 4
        - Increased neurons from 8:5 to 10:8 and cnahged activation functions from relu:relu to relu:tanh
    
- Were you able to achieve the target model performance?

- Original Model

![NN_first_pass_accuracy](https://user-images.githubusercontent.com/74840026/139603908-bdde0b32-4310-40da-9a1f-20242c190a65.PNG)
<br>

- Attempt # 1-Target not achieved
        
![1](https://user-images.githubusercontent.com/74840026/139603796-8f4a45a1-6c40-4b6f-ab61-8833faa1ab79.PNG)
<br>

- Attempt # 2-Target not achieved

![2](https://user-images.githubusercontent.com/74840026/139603799-fa4f9d33-0612-4c10-be8d-2f2a99fb144a.PNG)
<br>

- Attempt # 3-Target not achieved
      
![3](https://user-images.githubusercontent.com/74840026/139603803-3d9157c6-54c0-461c-8d04-a210b219d48a.PNG)
<br>

- Attempt # 4-Target not achieved
       
![4](https://user-images.githubusercontent.com/74840026/139603804-db9b2e3c-a995-4ef7-89a0-5fb155375d3e.PNG)
<br>

- What steps did you take to try and increase model performance?
    - Attempt # 1
        - Changed bin sizes for APPLICATION_TYPE and CLASSIFICATION from original model
    - Attempt # 2
        - Added in third hidden layer from Attempt # 1
    - Attempt # 3
        - Changed activation functions from Attempt # 2
    - Attempt # 4
        - Changed number of neurons and activation functions from original model

# Summary
