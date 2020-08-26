# Creating and Plotting Objects

08/21/2020: I created my first script in RStudio by following the steps given in Professor Frazier's "Getting Started with R & RStudio!" It was very fun to create a line plot in R and I look forward to learning how to create some of my own with differnet data. Some of the steps were a bit difficult to follow at first, but I think I mostly understand the basics now.

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
