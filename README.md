#Python program to print all Prime numbers in an Interval

# PrimeSeries
start=int(input("Enter the number 1:"))
end=int(input("Enter the number 2:"))
for i in range(start,end):
    for j in range(2,i):
        if (i%j==0):
            break
    else:
        print(i)
