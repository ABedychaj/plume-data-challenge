# plume-data-challenge

# Data Challenge Description
1. This assignment should take no more than 4 hours.
2. Download the dataset 
   * Go to this [website](https://archive.ics.uci.edu/ml/datasets/User+Identification+From+Walking+Activity) and download the [data](https://archive.ics.uci.edu/ml/machine-learning-databases/00286/User%20Identification%20From%20Walking%20Activity.zip)
   * After you unzip the file, you will see 22 csv files and README.
3. Explore the datasets and summarize your findings
4. From each participant data, identify the periods the participants are walking
   * Since there are no labels, treat this as an unsupervised learning exercise
   * You can use any algorithm you want - rule based approach, signal processing, ML, etc
   * Summarize and justify your approach
5. For each participant for each walking period, separate them into 2 second-long segments
   * You can clean up data here. For example, if there are not enough data points in a segment, you can remove them.
   * Each participant should have 5~150 2-second segments
6. Build a ML model to identify participants from their 2-second walking segments
7. Evaluate your model performance
   * Show confusion matrix
   * Calculate the [balanced accuracy score](https://scikit-learn.org/stable/modules/model_evaluation.html#balanced-accuracy-score)
8. Describe what kind of improvements you would make if you have more time.

