# Rock-Vs-Mine-Prediction-Model
It is a Sonar data set.
In these data there are 61 column in which 1-60 column is data i.e numerical column and 61 column is label i.e categorical column.
While loading data set its show only 60 coulmn don't get confused because python start it indexing from 0.
In Categorical column there is R and M, R mean Rock and M means Mine.
Because our prediction(output) is categorical so we use Logistic Regression
Import Numpy, Pandas, Train_Test_Split, LogisticRegression, Accuracy Score.
We Import data set with help of pd.read function and after the path of dataset we mention Header = None because in our dataset there is no heading.
For looking and analysing data we will use head() , shape , describe() , value_counts() for categorical column.
We want to find mean for each column with respect to R and M. We will use groupby().mean() function.
Then we seperate data and label in X and Y.
Later on we split X and Y in training and testing.
We take model as LogisticRegression and then train the model with x data use fit method to train.
Then we Evaluate model with accuracy test.
Same process we do with test data.
We make predictive system in the end.
while taking input from data we convert out data from list to numpy array then we reshape our data and then predict our input data wheather it predictcorrectly or not.
