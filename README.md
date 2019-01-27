# Cybersecurity Documents Classification
Code used to support my bachelor thesis

## Explanation of files, order of execution

- crawler.ipynb - Crawler for the EU website. First extract the files from the website.
- word_counter.ipynb - Data analyser that adds information to the files, for instance which words occurred the most.

After executing above two files, a test and training set have to be created manually.

- classifier.ipynb - Classifier that takes the training set to learn and can use a test set to determine its accuracy.

Other files:

- test_set_updater.ipynb - Utility to update the test and training sets when adding more info with word_counter
- data_set_analysis.ipynb - Utility to see values of the whole data set
- feature_selection.ipynb - Utility to analyse the training set, to determine features.
