# Prime-Numbers
#To find the prime numbers in the given n numbers
n = int(input("Enter a number:"))
for i in range(2,n):
    if n%i == 0:
        print(" not Prime")
        break
else:
    print("prime")
