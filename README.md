# Fibonacci
x = int(input("Enter limit for Fibonacci Series : "))
a = 0
b = 1
i = 1

print(a,b,sep=", ",end=" ")

for i in range(x):
    c = a + b
    print(",",c,end=" ")
    a,b=b,c
    i+=1;
