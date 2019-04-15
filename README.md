# Red wine quality dataset exploration and summary
In this project, i will use R and apply exploratory data analysis techniques in a selected dataset to discover relationships among multiple variables, and create explanatory visualizations illuminating distributions, outliers, and anomalies.

# Red Wine dataset
This tidy data set contains 1,599 red wines with 11 variables on the chemical properties of the wine. At least 3 wine experts rated the quality of each wine, providing a rating between 0 (very bad) and 10 (very excellent).
The classes are ordered and not balanced (e.g. there are munch more normal wines than excellent or poor ones). Outlier detection algorithms could be used to detect the few excellent or poor wines. Also, we are not sure if all input variables are relevant. So it could be interesting to test feature selection methods.  
Number of Instances: 1599.  
Number of Attributes: 11 + output attribute


## Dependencies 

>install.packages("ggplot2", dependencies = T)  
install.packages("knitr", dependencies = T)  
install.packages("dplyr", dependencies = T)  
install.packages("GridExtra", dependencies = T)  
install.packages("PerformanceAnalytics", dependencies = T)

## References
http://www.sthda.com/english/wiki/correlation-matrix-a-quick-start-guide-to-analyze-format-and-visualize-a-correlation-matrix-using-r-software
