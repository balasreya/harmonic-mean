# harmonic-mean
x<-c(1,2,3)
n<-length(x)
k=0
for(i in 1:n)
{
  k=k+1/x[i]
}
hm=n/k
print(hm)

