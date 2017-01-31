## Objective

Investigate a dataset to find patterns using visualizations and statistics.

###Skills applied

    -R Studio
    -R Studio Packages:
      -ggplot2
      -ggthemes
      -gridExtra
      -dplyr
      -plotly
      -corrplot

## Summary

A dataset containing nearly 5,000 white wines and their ingedients was analyzed. A quality rating out of 10 was given for each wine, and the ingredients were used to find connections to quality.

The ingredients are:
  
    -Fixed acidity
    -Volatile acidity
    -Citric acid
    -Residual sugar
    -Chlorides
    -Free sulfur oxide
    -Total sulfur oxide
    -Density
    -pH
    -Sulphates
    -Alcohol
    -Quality
    
    
The distribution of each ingredient was plotted and analyzed for outliers or patterns. 

Once each ingredient was analyzed, bivariate and multivariate analysis was performed to find connections between two or more ingredients to overall quality.

## Findings

My report concludes with three main findings:

    1)  There is no relatonship between quality and pH or alcohol
    2)  There is a relationship between higher quality and lower density
    3)  There is a relationship between higher quality and high alcohol/low residual sugar

## Resources

    1) http://docs.ggplot2.org/0.9.2.1/scale_gradientn.html
    2) https://github.com/jrnold/ggthemes#examples
    3) http://stackoverflow.com/questions/1249548/side-by-side-plots-with-ggplot2
    4) http://docs.ggplot2.org/current/geom_hex.html
    5) http://docs.ggplot2.org/current/geom_jitter.html
    6) http://docs.ggplot2.org/current/geom_point.html
    7) https://cran.r-project.org/web/packages/corrplot/vignettes/corrplot-intro.html
