#Task1

My first coding task with R coding language. To visualize the path of a running boy, I created 
a linear line on a 100x100 plot.

![](Basic_Running_Boy_Plot.png)

```
x <- 1:10
y <- 10:1

plot(x,y)

plot(x, y, type = "l")
plot(x, y, type = "o")

plot(x, y, type = "o",
     main = "The Path of a Running Boy",
     sub = "units of distance = meters",
     xlab = "longitude", 
     ylab = "latitude")

plot(x, y, type = "b", main = "The Path of a Running Boy", 
     sub = "units of distance = meters", 
     xlab = "longitude", 
     ylab = "latitude",
     lty = 2,
     lwd = .75,
     col = "blue",
     pch = 0,
     cex = 1.5)
```


