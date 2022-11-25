# fibonacci-with-recursion
#how to print fibonacci-series with recursion
def fi(n):
    if n==0 or n==1:
        return n
    else:
        return (fi(n-1)+fi(n-2))
n=int(input("Enter any positive number:"))
for i in range(0,n+1):
    print(fi(i),end=" ")
