# unsupervised-machine-learning
Used unsupervised machine learning to analyze data, with the goal of finding better ways to predict myopia.

## Process
 * Imported data into pandas
 * Separated data into target and features, standardized features using StandardScaler
 * Performed dimensionality reduciton on data using PCA, and then again with tSNE
 * Plotted tSNE output to identify potential data clusters
 * Performed cluster analysis with k-means, plotted the elbow curve to identify cluster amounts

## Conclusions
 * From the analysis done, the patients can be clustered together.
 * When plotting the tSNE output, the plots that appear appear to branch out into five directions.
 * Also, according to the plot of k-means, 5 clusters is the optimal amount of clusters.