# Overall.

K-Nereast Neighbor algorithm, also known as KNN or k-NN, is a supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point. In this kernel, we will implemet KNN to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.
I have referenced from this kernel(https://www.kaggle.com/code/shrutimechlearn/step-by-step-diabetes-classification-knn-detailed/notebook) by SHRUTI_IYYER. With SHRUTI_IYYER's kernel, he has directly used the KNN model from the Scikit Learn library, but my aim is to implement the KNN algorithm from scratch so I will use his kernel's outline and do it myself Implement the KNN algorithm. I also use the KNN model from the Scikit Learn library to compare the accuracy of my model.

Contents
1. Exploratory data analysis.
2. Implement pure KNN and make some comparisons.
3. Implement KNN with the weights of each K-neighbors.
4. F-Score.

# Adjust to run on your system.
Because I'm running this kernel on Google Colab and pushing it directly into GitHub. So if you want to run it locally or anywhere, you should download the dataset from https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database and make some adjustments at #Load dataset section to make it suitable for with path folder.
