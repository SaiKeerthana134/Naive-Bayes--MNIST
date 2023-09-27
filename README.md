# Naive-Bayes--MNIST 
-> Created a 10x10 grid to visualize 10 examples of each digit
-> Fitting a Naive Bayes classifier and report accuracy on the dev data. Remember that Naive Bayes estimates P(feature|label). While sklearn can handle real-valued features, let's start by mapping the pixel values to either 0 or 1. You can do this as a preprocessing step, or with the binarize argument. With binary-valued features, I used BernoulliNB. Mapped the pixel values to 0, 1, or 2, representing white, grey, or black. This mapping requires MultinomialNB. 
-> Trained thr model using GuassianNB, which is intended for real-valued features, and evaluated on the dev data. 
Results are discussed in the Jupyter notebook file
