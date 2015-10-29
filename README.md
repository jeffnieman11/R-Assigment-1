# R-Assigment-1
homework assignment for CUNY Bridge R class

Question 1:
> y=12
> fac=1
> y<-12
> fac<-1
> for (i in 0:11)
+ {fac<-fac*(y-i)}
> fac
[1] 479001600

Question 2:
> vec<-c(4:10)
> vec1<-vec*5
> vec1
[1] 20 25 30 35 40 45 50

Question 3:
> a=1
> b=7
> c=6
> quad1 <- (b*(-1) + sqrt(b^2-(4*a*c)))/(2*a)
> quad1
[1] -1
> quad2 <- (b*(-1) - sqrt(b^2-(4*a*c)))/(2*a)
> quad2
[1] -6
> x<- c(quad1, quad2)
> x
[1] -1 -6
