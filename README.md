# Classification-and-Regression-with-SVM-Logistic-regression

The project focuses on classifying handwritten digits data. We use Binary, Multi-class logistic regression and Support Vector Machines to classify the data and compare their performances.

Since logistic regression is traditionally a binary classifier, we can't classify the handwritten digits directly. So we use one vs all strategy to classify one digit against the others. Thus we need 10 binary classifiers to do multi classification.

However, a Multi-class logistic regression could be used to classify all the digits at the same time. Thus, we don't need 10 binary classifiers like before.

Support Vector Machines with Linear Kernel, Radial Basis function-RBF can also be used to classify the data. Changing gamma setting in RBF yields different results. With a default gamma setting, we also vary the penalty factor C to observe changes in the performance.

 

