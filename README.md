a = int(input("Enter number:- "))  # Store the input in 'a'
y=0
prime = 1 
PG="" # Assume the number is prime initially

# Loop to check divisibility
for i in range(2, a // 2, 1):  # Loop from 2 to a//2
    if a % i == 0:  # If 'a' is divisible by 'i', it's not a prime number
        prime = 0
if prime == 1:
    PG="True"
    while i>0:
        b=i%10
        x=i//10
        y=y*10+b
    print(i)
if(i==y):
    print("it is not a palindrome")
else:
    print("it is a palindrome")
if prime == 0:
    print("Num is Prime")
else:
    print("Num is Non-Prime")
