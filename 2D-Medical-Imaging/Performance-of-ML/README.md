### Perfomance of ML

In this exercise, you'll take a look at how well a radiologist can accurately label a set of medical images as either "cancer" or "benign", and how well a machine learning algorithm can do the same task. You will be given a dataframe with three columns:<br>

- Image labels created by a "perfect labeler"
- Image labels created by an expert radiologist
- Image labels created by a machine learning algorithm

You'll notice that the algorithm's labels are not 'cancer' or 'benign,' but rather probability values between 0 - 1 that indicate how likely the algorithm believes the image contains cancer (score of 1 indicates 100% likelihood that cancer is in the image).

The goal of this exercise is to assess the performance of the expert radiologist compared to the "perfect labeler," compare the algorithm to the "perfect labeler," and finally to compare the algorithm to the radiologist. You will do this by generating confusion matrices for each pair of labels and assessing true positive and false positive rates.