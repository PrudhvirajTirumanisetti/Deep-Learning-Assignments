# Deep-Learning-Assignments
Class Assignments 
EE258HOMEWORK #2(ONLINE SUBMISSION ONLY –MAKE A PDF or DOC FILE INCLUDING ALL THE REQUIRED SUBMISSIONS)DUE: SEP 28th

1.Read and practicethe codes in Chapter 2 (pages 33-68) of textbook “Hands-On Machine Learning with Scikit-learn and tensorflow”  (NOT TO BE SUBMITTED)

2.Get the data: For this homework, use the iris dataset under Files-> Datasets  on Canvas.(submit the code)Hint: Pandas knows to treat rows with 'NA' as missing values

3.Take a look at the data structure: Write a brief paragraph about the  data set related to each of the following observations (submit the code, the result, and the paragraphs):
a.Look at the top five rows of the data setb.Get a quick description of the data: Notice if there are any missing valuesor categorical featuresc.Get a summary of the numerical featuresd.Plot the histogram of the numerical features

4.Discover and visualize the data to gain insights:(submit the plots, code, and your observations of each plot)a.Obtain scatter matrixb.Obtain the correlations among features and comment

5.Data Cleaning(submit the code, results and plots showing the changes in data)a.Drop the data points with NA in itb.Tidy up the data by renaming the “class” data point correctly. c.Remove the outliers: drop the 'Iris-setosa' rows with a sepal width less than 2.5 cm. 
d.One of the data collectors forgot to convert the sepal length for “Iris-versicolor” to cm, instead added the data as meters. Find those and convert them to cm.e.Handle the categorical variables f.Save the clean data into a new file.

6.Utilizing a perceptron learning algorithm to check if  a flower is “iris-setosa” or not ?(submit plots, results, code explainations)a.Modify the clean dataset such that you have class =+1: for “iris-setosa”, and class = -1 for others. b.Is the new data set linearly separable?  Will perceptron algorithm work? c.Explain what is the functionality of each line of code in the perceptron.pyfile.d.Separate the data into test and training datae.Use the below perceptron.pyto train your perceptronf.Does the algorithm converge? What is niter in the code?g.Obtain a plot of the training accuracy as a function of epocs (number of times you go over the entire training data)h.Obtain the test data accuracy i.Sketch the decision boundary (the line that separates the data; obtained via perceptron algorithm) and the scatter plot of data points. For “iris-setosa” use a different identifier  than the rest of the classes. As performance metric use accuracy:

                                       Number of data points predicted correctly
                        accuracy = _________________________________________________
h

                                           Total number of data points
