# ML4developers

This repository collects Python notebooks complementary to the course "Applied Machine Learning" (4DV117) at Linnaeus University, Sweden.

* 1–Data_and_learning.ipynb loads the Iris dataset, transforms it into a dataframe and produces boxplots of its features. Then it trains a logistic regression classifier and evaluates its performance with the AUC evaluation metric.
* 2-Naive_Bayes_algorithm loads the Iris dataset, transforms it into a dataframe and produces boxplots of its features. Then it trains a Naive Bayesian  classifier based on only one feature and all features, resp. Then it evaluates performances of the classifiers using the accuracy metric and a confusion matrix.
* 3-Numerical_Regression.ipynb loads the Boston dataset, trains two numerical regression models (linear and KNN), evaluates their performances and visualizes the models. Additionally it demonstrates variants of feature selection.
* 4_Decision_Support.ipynb uses decision trees for claasification and regression. Therefore, it loads the Iris and the Boston dataset, resp., trains two decision tree models (classification of Iris and refression of Bosten), and visualizes the models. 
* 5_Kernel_Methods_and_SVMs.ipynb loads the Iris dataset, normalizes the data and applies SVM classification. It demonstrates the effects of cross validation on accuracy assessment and parameter selection.
* 6_Neural_Networks.ipynb applies a one layer artificial neural network (ANN) for classification on the Iris dataset and regression on the Boston dataset. The former uses a softmax activation for the neurons and a cross-entropy cost function. The latter uses a linear activation (no activation) and a mean squared error cost function. Hence, it is actually just a linear regression. Finally, to train even a non-linear regression model, we add a second layer with a non-linear activation to the regression ANN.
* 6_Deep_learning.ipynb under construction.

## Instructions

1. Open a notebook "*.ipynb" (click on the link when you hoover over it).
2. Open the notebook in colab (click on the "Open in Colab" link on to of the document. Run anway if you get a warning, it works and is safe.).
3. Step through the document top down, read the documentation and run the code as it is (click on the play symbols that show up in the code boxes when you hoover over them).
4. Optionally, modify code and documentation as you like; it does not get stored back to the repository. 
5. If you want to keep your changes, download the modified notebook (File -> Download -> .ipynb).
