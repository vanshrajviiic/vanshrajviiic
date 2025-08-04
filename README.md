# dict_name = input("Enter Name: ")
# dict_marks = int(input("Marks: "))
# min_marks = int(input("Enter Min Score: "))

# data = {dict_name: dict_marks}  # Avoid using 'dict' as a variable name

# def dict_low(data, name, marks, min_score):
#     if marks == min_score:
#         data.pop(name)
#     print(data)

# dict_low(data, dict_name, dict_marks, min_marks)
# coa=coi=cou=coo=cov=covv=cow=coe=0
# A=input("Enter A Para:")
# b=A.lower()
# for i in(b):
#     if(b==""):
#         cow+=1
#     elif(i=="i"):
#         coi+=1
#     elif(i=="a"):
#         coa+=1
#     elif(i=="o"):
#         coo+=1
#     elif(i=="u"):
#         cou+=1
#     elif(i=="v"):
#         cov+=1
#     elif(i=="e"):
#         coe+=1
#     elif(i=="a" or i=="e" or i=="i" or i=="u",i=="v"):
#         covv+=1
# print("A IN PARA IS",coa)
# print("Vovel in para is:",covv)
# print("I in para is",coi)
# print("E in para is",coe)
# print("O in para is",coo)
# print("V in para is",cov)
# print(" U in para is",cou)
# l1=[4,6,5,8,9,10]
# pro=1
# for i in(l1):
#     pro=pro*i
# print(pro)
# a=input("Enter ")
# while True:
#      try:
#       a==""
#      except KeyError:
#       print("You should not do this")
#      break
   
# an=[]
# even=[]
# odd=[]
# pro=1
# # for i in range(a):
#     # an.append(int(input("Enter Values:")))
# for j in(an):
#     if(j%2==0):
#         even.append(j)
#     else:
#         odd.append(j)
# print("Sum of List of even Number is",sum(even))
# for k in(odd):
#     pro=pro*k
# print(pro) 





# a=int(input("Enter"))
# rev=0

# while a>0:
#     digit=a%10
#     rev=10*rev+digit
#     a=a//10
# print(rev)
# prime=1
# if(rev<2):
#     prime = 0
# else: 
#     for i in range(2, rev // 2+1):  # Loop from 2 to a//2
#         if rev % i == 0:  # If 'a' is divisible by 'i', it's not a prime number
#             prime = 0
# if prime == 1:
#  
# print("prime")
a = input("Enter password: ")

has_int = False
has_str = False
has_spc = False
has_upp = False
has_low = False

special_chars = "/?.>,</*-+//+-(){}[]:'!@#$%^&*()_"

for char in a:
    if char.isupper():
        has_upp = True
    elif char.islower():
        has_low = True
    elif char.isdigit():
        has_int = True
    elif char in special_chars:
        has_spc = True

if len(a) < 8:
    print("Too short")
elif not has_upp:
    print("No uppercase letter")
elif not has_low:
    print("No lowercase letter")
elif not has_int:
    print("No number")
elif not has_spc:
    print("No special character")
else:
    print("Password is strong!")
ef find_median(numbers):
#     numbers.sort
#     n = len(numbers)
#     if n % 2==0:
#         median = (numbers[n//2] + numbers[n//2 - 1]) / 2
#     else:
#         median = numbers[n//2]
#     return median

# data = eval(input("Enter numbers separated by comma: "))
# data = [int(i) for i in data]

# print("The median is:", find_median(data))


# def find_hcf(x, y):
#     while(x != y):
#         if x > y:
#             x = x - y
#         if x == 0:
#          return y
#     if y == 0:
#         return x
#     else:
#             y = y - x
#     return x

# a = int(input("Enter first number: "))
# b = int(input("Enter second number: "))
# print("HCF is:", find_hcf(a, b))
# a=int(input("Enter thee value"))
# ori=a
# rev=0
# while a>0:
#     digit=a%10
#     rev=rev*10+digit
#     a=a//10
# print(rev)
# if(rev==ori):
#     print("Palindrom")
# else:
#     print("Non Palindrom")
a=int(input("Enter:"))
for i in range(1,a//2+1):
   print(f"{{{i},{a-i}}}", end=" ")
   
