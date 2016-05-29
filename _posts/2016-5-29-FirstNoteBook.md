---
layout: post
title: My First R post!
---

```R
library(data.table)
library(ggplot2)
data(iris)
ggplot(iris,aes(x=Petal.Length,y=Petal.Width,col=Species))+geom_point()
```


