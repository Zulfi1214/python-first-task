# python-first-task
# Ek program banao jo user ka naam aur age input le aur is format me print kare
name =input('enter the name ')
age=input('enter the age ')
print(f"MY NAME IS {name} ")
print(f"I AM {age} YEAR OLD")

#Performing arithmetic operations (addition, subtraction, multiplication, division)
Fnum=int(input("enter the first number "))
Snum=int(input("enetr the seconf number "))
print("the two number sum is =",Fnum+Snum)
print("the two number substration is =",Fnum-Snum)
print("the two number Multiplication is =",Fnum*Snum)
print("the two number divison is =",Fnum/Snum)

#Using if-elif-else statements for grading system
num=int(input("Eneter the any Number"))

if num>0:
  print("\n the number is Positive")
elif num<0:
    print("\n the number is Negative")
else:
 print("\n the number is Zero")

 #Checking whether aa grade
 
 num=int(input("Enter the your number"))
if num >90:
  print("\nyour gradde is A+")
elif num > 80:
    print("\n your gradde is A")
elif num > 70:
    print("\n your gradde is B")
elif num > 60:
    print("\n your gradde is c")
else:
  print(" beata tum fail hwa ha RE-TRY")

  #creat a program an number table
  
  num=int(input("enter the number "))
for i in range(1,11)
  print(num,"*",i,"=",num*i)

  #print a number 0 to n and also print even number
  n = int(input("Enter a number: "))

print(f"Even numbers from 0 to {n} are:")

i = 0
while i <= n:
    if i % 2 == 0:
        print(i)
    i += 1

    #task 4
    n=int(input("enter the number"))

sum = 0
i = 1
while i <= n:
  sum +=i
  i +=1
  print(f"The sum of numbers from 1 to {n} is: {sum}")
  
  #task 5
  
  n = int(input("enter the number"))
for i in range(0,n+1):
 if i%2==0:
  print(i)

  #List ka first aur last element print karo.
List ke andar loop chala ke har fruit print karo.
User se ek fruit ka naam input lo aur check karo ke wo list me hai ya nahi.

fruits = ["apple", "banana", "mango", "orange", "grapes"]
print(fruits[0])
print(fruits[4])
for fruit in fruits:
  print(fruit)
  
  user_fruit =input("enter the fruits name")
  if  user_fruit in fruits:
    print( "is in the list ✅")
  else:
   print("is not in the list ❌")
  
