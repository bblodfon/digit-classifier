# Digit-Classification
A Machine Learning project

This project implements the Expectation Maximization algorithm using Bernoulli Mixes (we tested 1-32 Mixes) in order
to classify digits.

Firstly, a train + test dataset is given on the mnist_all.mat file.
By running bernoullimix3.m file you train the dataset for all benoulli mixes. If you run draw_digits.m after that
for different values of Kplot (number of Mixes), you will see what we have "learned" from the test dataset for each
Mix! Lastly, if you run the test_digits.m file you will get the final results (error percentage for every Mix and for
every digit/Mix) on the results.txt file.

The code was tested on Matlab (R2011a). 