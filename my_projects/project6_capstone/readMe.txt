--------------------------------------
Environment used to run the model
---------------------------------------
 - Floydhud cloud is used to run the code with gpu
 - Dependency packages
	- kera (latest)
	- tensorflow (latest)




-----------------------------------
Links to dataset and model:
-----------------------------------


Original json input data:

https://drive.google.com/open?id=0B9YR5U1BP28MQ1NoZU9fNGJUSWs
https://drive.google.com/open?id=0B9YR5U1BP28MLTRmYUFET3QtUkk

Processed input data to train model:

https://drive.google.com/open?id=0B9YR5U1BP28MSkI1QXQwZGJTZkk
https://drive.google.com/open?id=0B9YR5U1BP28MOE1ReUdHeURsS00

Glove model:

https://drive.google.com/open?id=0B9YR5U1BP28MVHE3Nm5TeUtHSHc

Trained model:

https://drive.google.com/open?id=0B9YR5U1BP28MUEEwXzF5dld2cHc

----------------------------------
How to run the model
----------------------------------

a. answer_selection_cosine.ipynb contains complete code to train and test model after data processing
b. Load processed data
c. load glove model
d. Run through the code in above file
e. Instead of training model, load model using load_model('path')
f. Check the accuracy 

