# Head CT hemorrhage detection

This dataset contains 100 normal head CT slices and 100 other with hemorrhage. No distinction between kinds of hemorrhage. Labels are on a CSV file. Each slice comes from a different person. The main idea of such a small dataset is to develop ways to predict imaging findings even in a context of little data. In this notebook, I present a simple data augmentation capable of achieving 90% accuracy in the test set.

Dataset Link: https://www.kaggle.com/felipekitamura/head-ct-hemorrhage

## Project information

* Loss: Cross Entropy Loss
* Test Accuracy: 90%
