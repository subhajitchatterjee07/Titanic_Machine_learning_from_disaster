# Titanic_Machine_learning_from_disaster
Using machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

The target is to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

## NOTE : 
- In this project I have used feature engineering to convert categorisation data to trainable values.
- Also the algorithm used for the Logistic Regression is lbfgs which stands for: "Limited-memory Broyden–Fletcher–Goldfarb–Shanno Algorithm".  As such, it can deal with a wide range of different training data and is therefore the default solver. Its performance, however, suffers on poorly scaled datasets.So we have increased the max iterations to a 1000.
