# Assignment-4
Programming structure in R
> Frequency <- c(0.6, 0.3, 0.4, 0.4, 0.2, 0.6, 0.3, 0.4, 0.9, 0.2)
> BP <- c(103, 87, 32, 42, 59, 109, 78, 205, 135, 176)
> First <- c(1, 1, 1, 1, 0, 0, 0, 0, NA, 1)
> Second <- c(0, 0, 1, 1, 0, 0, 1, 1, 1, 1)
> FinalDecision <- c(0, 1, 0, 1, 0, 1, 0, 1, 1, 1)
> data <- data.frame(Frequency, BP, First, Second, FinalDecision)
> par(mfrow=c(1,2))
> boxplot(BP ~ First, data=data, main="Boxplot of BP by First Assessment", xlab="First Assessment", ylab="Blood Pressure")
> boxplot(BP ~ Second, data=data, main="Boxplot of BP by Second Assessment", xlab="Second Assessment", ylab="Blood Pressure")
> hist(BP, main="Histogram of Blood Pressure", xlab="Blood Pressure", col="skyblue", border="black")
