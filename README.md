# puffer-data-analysis

All of our results are based on data analysis. We have imported all the data on [puffer-data-release backet](https://console.cloud.google.com/storage/browser/puffer-data-release;tab=objects?prefix=&forceOnObjectsSortingFiltering=false) from 2019-01-26 to 2023-03-06 to our directory on HPC. Please change the directory before running jupyter notebook cells.
```
data_dir = "/scratch/tn2208/puffer/puffer-data-release"
```

[puffer-plots.ipynb](puffer-plots.ipynb) contains analysis of
* 2020 Comparisons
* Streaming metrics throughout the day
* Stall Occurrences
* Startup Time Comparison

[puffer-corr.ipynb](puffer-corr.ipynb) contains analysis of
* Feature Correlations