# Conditional_Statement-By-Python
 # Simple if

# 1
ver=10
if(ver==10):
    print("Enter of vaiable is 10")

print("Bye")

# 2
a =25
if(a>=30):
    print("Value of Varible is 25")

print("bye")


# If_ Else

#1 

a= int(input("Enter the value of A :- "))
b = int(input("Enter the value of B :- "))

if a<b:
    print("B is greater")
else:
    print("A is greater")

    # 2

a=30
b=50
if a<b:
    print("B is greater")
else:
    print("A is greater")



# If Else Ladder

# Question
"""
(1) Percentange greater than 70 == Dist
(2) Percentange greater or equal to 65 and less than 70 == 1st Class
(3) Percentange greater or equal to 60 and less than 65 == 2st Class
(4) Percentange greater or equal to 55 and less than 60 == 3st Class
(5) Percentange less then 55 == fail
"""


p = int(input("Enter your percentange :- "))
if p>=70:
    print("Dist")
elif p>=65 and p<70:
    print("1st Class")

elif p>=60 and p<65:
    print("2nd Class")
          
elif p>=55 and P<60:
    print("3rd class")


else:
    print("Fail")



#  Nested if

# Question

"""
age>=18
weight>=50
if both age and weight match with certeria then the user can donate the blood
if age is less than 18 show one msg under age 
if weight is less than 50 show one msg under weight
ig age doesnot match then it should ask for weight

"""
age= int(input("Enter your age :- "))


if age>=18:
    weg = int(input("Enter your weight :- "))
    if weg>=50:
        print("Blood Donate")

    else:
         print("under weight")
else:
    print("Under age")
               
