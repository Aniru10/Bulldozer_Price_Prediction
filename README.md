# Bulldozer_Price_Prediction

![image](https://user-images.githubusercontent.com/81894324/140470711-448bc5bb-4826-49e5-b474-5046581ea441.png)



The data is split into three parts:<br>

* Train.csv is the training set, which contains data through the end of 2011.
* Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
* Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.<br>
The key fields are in train.csv are:

* SalesID: the uniue identifier of the sale<br>
* MachineID: the unique identifier of a machine.  A machine can be sold multiple times<br>
* saleprice: what the machine sold for at auction (only provided in train.csv)<br>
* saledate: the date of the sale<br>
