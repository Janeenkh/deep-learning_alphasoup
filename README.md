# Deep learning alphasoup

Overview of the analysis: To predict if charity funded by Alphabet Soup is successful or not using deep learning

Results: 

## Data Preprocessing
**Target variables:**
Variables was "is successful". 
**Features**
APPLICATION_TYPE            
AFFILIATION                 
CLASSIFICATION              
USE_CASE                    
ORGANIZATION                
STATUS                      
INCOME_AMT                  
SPECIAL_CONSIDERATIONS       
ASK_AMT  

**Removed variables**
EIN and NAME variables were removed


## Compiling, Training, and Evaluating the Model

**How many neurons, layers, and activation functions :**
In the base line there are 2 hidden layers and 80 nodes in the first layer and 30 nodes in the second layer

Attempt#1
Removed "USE CASE" column, changed the threshholds for binning the APPLICATION_TYPE and the CLASSIFICATION columns. 

Attempt#2
In the attempt #2 there are 3 hidden layers and 100 nodes in the first layer and 50 nodes in the second layer and 15 in the third layer

Attempt#3
In the attempt #3 sigmoid was applied to each layer and the epochs was increased from 100 to 200

**Module performance:**
Base line = 72.9%

Attempt# 1 = 72.4%
Attempt# 2 = 72.2%
Attempt# 3 = 72.1%


