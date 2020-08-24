# practice1.md

setwd("~/Downloads/DATA 100/RStudio/First Project/Storing Data Subdirectory")
x <- 1:10
y <- 10:1
plot(x, y, type = "b", main = "The Path of a Running Boy", 
     sub = "units of distance = meters", 
     xlab = "longitude", 
     ylab = "latitude",
     lty = 2,
     lwd = .75,
     col = "blue",
     pch = 0,
     cex = 1.5)
