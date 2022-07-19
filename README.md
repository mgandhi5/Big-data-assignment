# Big-data
In each case, write a program implemented using Spark (either on AWS or your Databricks),  to:

  Find the 5 most frequent and 5 least frequent (but present)  bi-grams for your dataset (only letters, not the various other characters).  A bi-gram is 2 successive digits/letters/etc within a word.  For example, the string stevens has 6 (st, te, ev, ve, en, ns).  Assume that the data set is large enough so that bi-grams at the boundaries of nodes are not significant (most likely you will have only 1 mapper in any case since this is a very small data set, so it won’t be an issue.

Your submission should be copied into MSWord or pdf, and should include (in one file):

    Your Spark Program

   Minimum (5 least occurring bi-gram)

    Maximum (5 most commonly occurring bi-gram)
# spark
# bi-gram
# 2)
Using the environmental data for each of the provinces in Canada, and weighting each piece of data by the number of cities in the province, calculate the mean temperature and mean precipitation for all of Canada for annual and each month.

In the Analytics - Recommenders and Ensembles Module on Canvas.

In each case, write a program using Python libraries of PySpark.  It would make sense to treat the data as manipulation of matrices.  Do not assume that the input data is all on the same node.

Your submission should include the Spark program, and the answers (probably in a matrix of the same form as the input matrices, but without Rows for High, Low Temperatures, and columns for # of cities, and years).
