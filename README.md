# Conditional_Statement-By-Python

#                                                  Simple If
var = 10

if(var==10): # your condition is getting True
    print("Value of variable is 10")
    
print("Bye")
a = 25

if(a>=30): # Condition is getting False
    print("Value of variable is 25")
    
print("bye")
# If_Else
a = int(input("Enter the value of A : "))
b = int(input("Enter the value of B : "))

if a<b: # Condition is getting True
    print("B is greater")
else: # Else part call
    print("A is greater")
x = 25
y = 30

if x<y: # Condition True
    print("Y is greater")
else:
    print("X is greater")
    
# If Else Ladder
# 1) Percentange greater than 70 == Dist
# 2) Percentage greater or equalto 65 and Less than 70 == 1st Class
# 3) Percentage greater or equalto 60 and Less than 65 == 2st Class
# 4) Percentage greater or equalto 55 and Less than 60 == 3st Class
# 5) Percentange less than 55 == Fail

p = int(input("Enter your percentange : "))

if p>=70:
    print("Dist")
elif p>=65 and p<70:
    print("1st Class")
elif p>=60 and p<65:
    print("2nd Class")
elif p>=55 and p<60:
    print("3rd class")
else:
    print("Fail")
    
    
# Nested If
# 1) Age>=18
# 2) Weight>=50
# 3) If both age and weight match with certeria then the user can donate the blood
# 4) if age is less than 18 show one msg under age
# 5) if weight is less than 50 show one msg under weight
# 6) if age doesnot match then it should ask for weight

age = int(input("Enter your Age : "))


if age>=18:
    weg = int(input("Enter your Weight : "))
    if weg>=50:
        print("Blood Donate")
    else:
        print("Under Weight")
else:
    print("Under Age")
        
