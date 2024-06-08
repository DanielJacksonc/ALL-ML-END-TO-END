# End to End REAL ESTATE PREDICTION PROJECT.

### PROBLEM STATEMENT:
    In recent times, many factors are affectiing the proces of houses, this consideration to deepdive into these factors is as a result of the 
    inlation rate plunging on individuals and business.
    in this article and project, we will be investigating the factors, and thereby making prediction that will make us ahead in the game.
## ARCHITECTURE OF OUR WORK:
    see link `this link` for architecture.

## TechStack:
    1. Programming = Python
    2. Data cleaning and manipulation = Pandas
    3. Data Visualization  = Matplotlib
    4. Model Building =Sklearn
    5. Backend = Python
    6. Website = Html/CSS/Javascript.




### This Projects will come in sections
    1. data finding or getting your data.
        1. Kaggle
    2. Data cleaning.
        1.removing columns with missing values.
        2. using lambda function to create a seperate column for values
        3. handling non uniformity of data using the is float function or Unnnecesary feature
    3. Feature Engineering and dimensional reduction techniques
        1. Transforming Features  = age_of_house = current_year - year_built
    4. Outlier Detection and removal .--- they are are either data errors, or they represent extreme representation.
       * there are many ways to remove them, like standard deviation or simple domain knowledge.
    5. Data Visualization
        1. Scattered plot - to see the distribution
        2. Hisogram to see the skewedness of the distribution and remove the outliers
    6. Model Building
        1. Change all categorical variable to numerical variables using ONE HOT ENCODING
        2. kfold cross validation
        3. gride search  
            1. splitting the data into x and y variables 
            2. training and testing the data
            3.applying the model
            4. evaluating the model
            5. finding the best model with grid search and hyper parameter tunning
            6. predicting using the best model
    7. Export model to pickle file so that it can be used by python flask server
    8. we export our columns information. We need them for their index in the list and their arragment. for accurate prediction
    9. Write python script that will serve as the SERVER to  http request from the UI. will serve as the backend for the UI.
       
### We wiil be building and deploying our model. 
#### There are three folders we need:
    1. Folder for our server
    2. Folder for our client
    3.Folder for our model
    4. nOW to continue, go to README for server in servy folder and follow instruction
    
