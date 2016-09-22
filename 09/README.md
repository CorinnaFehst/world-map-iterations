# 09 ckmeans cluster min breaks

in this iteration, we use the [ckmeans](http://simplestatistics.org/docs/#ckmeans) algorithm from the [simple-statistics](http://simplestatistics.org/) package to cluster our data. we pick the **minimum** value of each cluster as a break.  we then use these breaks with a [quantile](https://github.com/d3/d3-scale/blob/master/README.md#quantile-scales) scale to map values in the data to colors on the choropleth map.

this is method is my current favorite way to create breaks, or color thresholds, for a choropleth map.

