# class16Lab

<p align="center">
  <img width="320" height="200" src="https://github.com/mhc-stat340-f2019-sec02/class16Lab/blob/master/featured.png">
</p>

This lab explores a data set of [candy comparisons](https://fivethirtyeight.com/features/the-ultimate-halloween-candy-power-ranking/).

The 538 team created an experiment that collected over 250,000 data points.
The experiment presented two randomly chosen types of candy to participants and asked them to chose which they would prefer as a trick-or-treater.
The original experiment is [here](http://walthickey.com/2017/10/18/whats-the-best-halloween-candy/).

The dataset description can be found [here](https://github.com/fivethirtyeight/data/tree/master/candy-power-ranking).

The data collected characteristics of each type of candy presented to participants.
The goal of this lab is to pick your favorite candy characteristics and build a logistic model that predicts this characteristic.

Instructions:
	1. Fork the 538 repository
	    * Rep:https://github.com/fivethirtyeight/data/tree/master/candy-power-ranking
    2. Choose a candy characteristic and build a logistic regression model. Your model must include
	    * 3 covariates
		* Predict a different candy characteristic than the one we go over in class.
	3. Describe the coefficients corresponding to your covariates
		* Explain what the coefficients mean in terms of **log odds** 
		* Explain what the coefficients mean in terms of **odds**
		* Identify any covariates that are significant
	4. Report the Accuracy of your logistic regression model
