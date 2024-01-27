# E Bay Shill Bidding Clustering

In our quest to find the best classification algorithm to identify suspicious auction bids we will try 
to Support Victor Machine and neural network. Support Victor Machine purpose is to increase the 
dimensionality of data to fit a support victor classifier. 
A Support Victor Classifier uses a soft margin to fit the data. A margin in machine 
learning means the distance between the classifier and two points of the same distance from 
the classifier. That distance is the margin. But to understand a soft margin first we must 
understand maximum margin. To clarify how maximum margin classifier works, we will 
consider having two clusters. In a maximum margin we find the closest two points between 
the clusters and taking the maximum margin between the two points. In case there is no 
misclassification the maximum margin allows for the biggest size between the two clusters. 
This allows for high accuracy and shows the distinction between the two classes. But in 
case of misclassification, maximum margin accuracy will drastically decrease. This is 
because maximum margin is very sensitive to misclassification. That’s why soft margin 
was created. Soft margin allows the classifier to ignore data points if it will increase 
accuracy. The number of datapoints ignored is usually determined by cross validation. 
The reason why SVC isn’t used alone is because it can’t fit some data formats. For example, a 
one-dimensional data of medicine dosage where low amount of dosage doesn’t cure the sick, the 
right amount cures while a big amount doesn’t cure. A SVC can’t fit this data set. Thus, we need 
to increase the dimensionality of data. We can do this by for example maxing a y axis that equals 
x axis squared. This is what SVM does. The part in SVM responsible for this the SVM kernel. But 
kernels don’t increase he dimensionality of the data they just calculate the high dimensional 
relationship between datapoints without doing the transformation from low dimensionality to high 
dimensionality. There are multiple types of kernels that can be used and each of them calculates 
the high dimensional relationship between datapoints differently
