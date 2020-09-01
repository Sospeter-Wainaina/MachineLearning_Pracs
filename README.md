# MachineLearning_Pracs
So Basically this repository will be updated on a daily basis with different projects Lets Learn by Doing 
# Day 1
## Classificaton Problem
we want to predict one of several
options (the species of iris). This is an example of a classification problem. The possi‐
ble outputs (different species of irises) are called classes. Every iris in the dataset
belongs to one of three classes, so this problem is a three-class classification problem.
The desired output for a single data point (an iris) is the species of this flower. For a
particular data point, the species it belongs to is called its label.
So basically the model I mad got an accuracy of 97% which is fairly good 

# Day 2
## Classification Problem
So basically in this simple machine learning project I took a Wiscounsin Breast Cancer dataset
which ispublicly available inkaggle, the data did not need that much data cleaning and if so was very little
just changing somethings here and there , so in this I used the KNeighbors Classifier which is the simplest machine learning algorithm and it was fun as i did it and learnt some few things here and there . in this model my best accuracy was at 95% which is not at all bad, hoping to do some more practice on this before i move to complex machine learning projects. 

# NB (Something to note about KNN algorithm, drawbacks) ref : Introduction to machine learning book by O'REILLY
Strengths, weaknesses, and parameters
In principle, there are two important parameters to the KNeighbors classifier: the
number of neighbors and how you measure distance between data points. In practice,
using a small number of neighbors like three or five often works well, but you should
certainly adjust this parameter. By default, Euclidean distance is used, which works
well in many settings.
One of the strengths of k-NN is that the model is very easy to understand, and often
gives reasonable performance without a lot of adjustments. Using this algorithm is a
good baseline method to try before considering more advanced techniques. Building
the nearest neighbors model is usually very fast, but when your training set is very
large (either in number of features or in number of samples) prediction can be slow.
When using the k-NN algorithm, it’s important to preprocess your data (see Chap‐
ter 3). This approach often does not perform well on datasets with many features
(hundreds or more), and it does particularly badly with datasets where most features
are 0 most of the time (so-called sparse datasets).
So, while the nearest k-neighbors algorithm is easy to understand, it is not often used
in practice, due to prediction being slow and its inability to handle many features
# Day 3 DECISION TREE CLASSIFIER
Decision trees are widely used models for classification and regression tasks. Essen‐
tially, they learn a hierarchy of if/else questions, leading to a decision.
These questions are similar to the questions you might ask in a game of 20 Questions.
Imagine you want to distinguish between the following four animals: bears, hawks,
penguins, and dolphins. Your goal is to get to the right answer by asking as few if/else
questions as possible. You might start off by asking whether the animal has feathers, a
question that narrows down your possible animals to just two. If the answer is “yes,”
you can ask another question that could help you distinguish between hawks and
penguins. For example, you could ask whether the animal can fly. If the animal
doesn’t have feathers, your possible animal choices are dolphins and bears, and you
will need to ask a question to distinguish between these two animals—for example,
asking whether the animal has fins. Thats what we did today with our iphone purchase records. Open the notebook for more detailed info.

# Day 4 Predicting customer churn
PLease open the notebook to find more detailed info, i explained every step in detail