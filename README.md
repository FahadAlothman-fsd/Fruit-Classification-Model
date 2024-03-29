# Machine-Learning-Project-ICS-485
 

this project is for a machine learning course.

The task was to classify fruits based on anonymous features.
The dataset provided was stripped of the feature's name and replaced with X1, X2, etc. 

### First

we had to perform the following tasks before training the models.

The tasks were performed in the following order:
- perform data analysis on the data and provide essential statistics
- perform techniques to deal with missing values
- feature transformation
- perform correlation analysis 
- perform techniques to handle imbalanced data.

### After augmenting the dataset

we trained four models, which are:
- Adaboost
- Random Forest
- KNN 
- Logistic Regression 


The data was split into testing and training sets.

All models were tweaked to fit the dataset optimally.

### The tweaking process

perform the following on the training set in order:
- find all relevant paraments of the model
- use an iterator to produce all valid combinations of the relevant parameters
- loop through the combinations and find the paraments that produce the best performance measure


### Performance Measures
The following performance measures were used to compare across students' models:
- Matthew's correlation coefficient
- F1-score (macro average)
- F1-score (weighted average)
- Geometric mean

Once the optimal parameters were found, the models were tested on the testing set.


