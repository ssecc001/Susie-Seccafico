# Susie-Seccafico
import math 

print("Selection an operation")
print(" 1 to Add \n 2 to Subtract \n 3 to Multiply \n 4 to Divide \n 5 to square root \n 6 raised to a power \n")
print("\n")     

num1= float(input("Enter a Number"))
print (num1)
operation=int(input("Enter choice 1,2,3,4,5,6"))


if operation == 1:
    num2 = float(input("Enter a number"))
    sum = num1
    sum = sum + num2
    print (num2)
    print (str(num1) + " + " + str(num2) + " = " + str(sum))


elif operation == 2:
    num2 = float(input("Enter a number"))
    dif = num1
    dif = dif - num2
    print (num2) 
    print (str(num1) + " - " + str(num2) + " = " + str(dif))


elif operation == 3:
    num2 = float(input("Enter a number"))
    product = num1
    print (num2)
    product = product * num2
    print (str(num1) + " * " + str(num2) + " = " + str(product))
    
elif operation == 4:
    num2 = float(input("Enter a number"))
    if (num2 != 0):
        quotient = num1
        print (num2)
        quotient = quotient / num2 
        print (str(num1) + "/" + str(num2) + " = " + str(quotient))
    else:
        print("Error")
    
    
elif operation == 5:
    if (num1 > 0):
        print("square root " + str(num1))
        print (math.sqrt(num1))
    else:
        print("Error")
    
elif operation == 6:
    exp = int(input("Enter an exponent"))
    exp1 = (num1 ** exp)
    print(str(int(num1)) + " raised to the " + str(exp) + " power" + " = " + str(exp1)) 

