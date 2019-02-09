# Hands on machine learning with sick-it learn and tensorflow
## chapter 1
### What is machine learning?
Machine Learning is the field of study concerned with making computers learn from data, and generalize to unkown data without being explicitly programmed
Can you name four types of problems where it shines?

### What is a labeled training set?
A set of data with the target solution is marked. For example in a classification problem between cats and dogs, each example is associated with the desired classification.

### What are the two most common supervised tasks?
Calssification tasks. For example spam filtering.
Regression tasks. For example stock price prediction.

### Can you name four common unsupervised tasks?
Clustering  
Anamoly detection  
Dimentionality reduction  
Data visulaization  

What type of Machine Learning algorithm would you use to allow a robot to walk in various unknown terrains?

Reinforcement learning

What type of algorithm would you use to segment your customers into multiple groups?

CLustering via unsupervised learning

Would you frame the problem of spam detection as a supervised learning problem or an unsupervised learning problem?

Supervised learning

What is an online learning system?

A system that can improve with new data i.e. can learn incrementally

What is out-of-core learning?

Learning by segementing the data into smaller mini-batches to handle vast data quantities

What type of learning algorithm relies on a similarity measure to make predictions?

Instance based learning

What is the difference between a model parameter and a learning algorithm’s hyperparameter?

A model parameter is a number that controls how the model will generalize to new data, for example the slope of a line in a linear model. The hyperparameter controls the training process, for example learning rate.

What do model-based learning algorithms search for? What is the most common strategy they use to succeed? How do they make predictions?

Model based learning looks for the parameters that best describe training data given the model. Typically is done by minimizing a cost function, or maximizing a utility function.

Can you name four of the main challenges in Machine Learning?
- Lack of data
- Unrepresentatiove data
- Underfitting, or not describing the training data well. Usually a result of oversimplified model
- Overfitting, or inability to generalize to new data, usually a result of overcomplicated model.

If your model performs great on the training data but generalizes poorly to new instances, what is happening? Can you name three possible solutions?

Overfitting. Typical solution is to increase training data, simplify the model by reducing number of parameters or regularization.

What is a test set and why would you want to use it?

A test set is data used to estimate the performance of the model on data it has not been trained on.

What is the purpose of a validation set?

Validation set is used to select the model via tuning the hyperparameters.

What can go wrong if you tune hyperparameters using the test set?

Risk of overfitting the test data, therefore worse performance on general data.

What is cross-validation and why would you prefer it to a validation set?

Data segmentation into chuncks used for training/validation/testing. It works well in case of limited data.