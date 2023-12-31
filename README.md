# PCExpo---AxesReorder
Implementation of Research paper with extensions.
```
1. Support of Negative weights to all metrics.
2. When data dimensionality goes beyond 15, using data filtering and PCA it was reduced to 10 dimensions.
```
This research paper mainly focuses on reordering the axes(data columns) based on the 12 metrics and their overall result.
```
1. Clear Grouping                  7. Positive Variance
2. Density Change                  8. Negative Variance
3. Split Up                        9. Positive Skewness
4. Positive Correlation            10. Negative SKewness
5. Negative Correlation            11. Fan
6. Neighbourhood                   12. Outliers
```

The description of project algorithm, how each metric is claculated and its importances all are mentioned in PC-Expo.pdf file.

And how the code works by implementation of algorithm, extensions are mentioned in report.pdf.


Download the code and Use Cars.csv file or use some valid .csv file from Internet. And run the Pc-expo.ipynb file, then anaylse the relation between the data columns based on different weightage of each metric.
