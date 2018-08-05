## About

Included in this repository is a data science competition that I participated in in August 2018. The competition is still being hosted on [DrivenData](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/submissions/ "Driven Data"), a data science competition platform. 

The challenge was to predict the status of water wells throughout Tanzania: working, not working, or working but in need of repair. In what is obviously a classification problem, I was provided a mix of categorical and continuous features.

Due to the nature of the challenge and the dataset that was made available, exploratory data analysis was a significant priority. Exploring the various features revealed many of the problems common in our field: faulty data, null and missing values and irrelevant features. In order to create a good, working model, some features were repaired using various degrees of imputation, while others were discarded altogether. 

Ultimately, this resulted in a training set of features on which I trained a Random Forest classifier. Excellent classification scores were achieved, but the *functional needs repair* status remained difficult to predict. Testing on unseen data led to a best F1-score of 0.65 on that group of wells, with 0.88 and 0.90 as scores on broken and functional wells respectively.


___

![Score](https://github.com/YouriImm/DrivenData---Water-Pumps/blob/master/img/DD_results.PNG?raw=true)

___
