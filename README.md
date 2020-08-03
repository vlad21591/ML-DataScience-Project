# Machine learning and data science project

Machine Learning Algorithms

Introduction:

The sinking of the Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew. While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

Purpose:

Build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc). machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

[The data came from Kaggle -- Titanic: Machine Learning from Disaster]

Results(from the ML results.py):

LR(Logistic regression) -- Accuracy: 0.852, Precision: 0.9, Recall:0.818, Latency: 0.01558065414428711ms

SVM(Support Vector Machines) -- Accuracy: 0.885, Precision: 0.933, Recall:0.848, Latency: 0.0ms

MLP(Multilayer perception) -- Accuracy: 0.869, Precision: 0.931, Recall:0.818, Latency: 0.0ms

RF(Random forest) -- Accuracy: 0.885, Precision: 0.933, Recall:0.848, Latency: 0.0ms

GB(Gradient boosted trees) -- Accuracy: 0.852, Precision: 0.9, Recall:0.818, Latency: 0.0ms

Conclusion:

We can see that from the 5 ML models the Random-Forest (learning_rate=0.01,max_depth=2, n_estimators=500) is the best fit.

Random Forest(with test_data) -- Accuracy: 0.81, Precision: 0.875, Recall:0.645, Latency: 0.01566004753112793ms

Thank you.

