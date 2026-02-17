# Write-a-python-program-to-find-the-sum-of-first-n-even-numbers.
n=int(input("enter the limit : "))
s=0
for i in range(0,n+1,2):
    s=s+i
    print("the sum is :" ,s)

 


OUTPUT
enter the limit : 3
the sum is : 0
the sum is : 2
