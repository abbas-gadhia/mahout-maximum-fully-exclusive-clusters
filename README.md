mahout-maximum-fully-exclusive-clusters
=======================================

Find maximum "k" ensuring that the items within each category are restricted to a single cluster.
So for example, if there are 4 categories and "k" is 2, then one of the possible orientations of such a setup, would be 2 categories
per cluster.

Each cluster would then be used as inputs to separate classification models.

Building such smaller models helps in keeping things smaller and faster when a large number of categories/items makes training/testing very difficult

For the motivation behind this project, [http://stackoverflow.com/questions/20950429/mahout-naive-bayes-model-very-slow]
(http://stackoverflow.com/questions/20950429/mahout-naive-bayes-model-very-slow)
