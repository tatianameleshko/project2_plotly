Project 2
========================================================
author: Tatiana Meleshko
date: 04 December, 2016
autosize: true


========================================================


```r
library(plotly)
library(datasets)
library(webshot)
 p<-plot_ly(mtcars,x=~mpg,y=~wt,z=~hp,type="scatter3d", mode="markers",color=~cyl)
 htmlwidgets::saveWidget(as.widget(p), file = "demo.html")
```
<iframe src="demo.html" style="position:absolute;height:100%;width:100%"></iframe>

