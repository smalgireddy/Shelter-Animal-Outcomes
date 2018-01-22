# Shelter-Animal-Outcomes
Using a dataset of intake information including breed, color, sex, and age from the Austin Animal Center, we should predict the outcome for each animal.
The objective of this project is to predict the outcome of animals placed in shelters given features such as the animal’s age, breed, and color.  There are 5 possible outcomes for each animal (shown in figure #) with euthanasia being the worst outcome.  From the predictions, the shelter hopes to be able to determine which animals are likely to be euthanized as well as find trends into what features increases the chance for adoption.  This provides a chance for shelters to make an effort to aid animals with a low chance of adoption.  The overall goal is to decrease the yearly number of animals euthanized.

This project has 3 phases, they are preprocessing, feature engineering and building the models, finally evaluation of models. I built Multinomial regression, Support Vector Machines, Random Forest,  Neural Network and XGboost classifiers on the data,  after fine tuning with grid-based approach, the Random Forest model performed quite well with AUC of 0.82 and OOB error was about 35% for this model.
The performance of above models are as below with the features:
![target variables](amo.JPG?raw=true "Target classes")
![metric comparison](asometric.PNG?raw=true "performance evaluation")
![Confusion matices](cmt.JPG?raw=true "confusion matrix")
