a = int (input("enter a first number "))
op = (input("enter any opration  " ))
b = int(input("enter a second number " ))

if op == "+":
    print ("answer is  ",a+b) #addition

elif op == "-":
    print ("answer is ", a-b) #substraction

elif op == "*":
    print ("answer is ", a*b) #multiplication

elif op == "/":
    print ("answer is ", a/b) #division 

elif op == "%":
    print ("answer is ", a%b) #modulas

elif op == "**":
    print("answer is ", a**b) #exponents

elif op == "//":
    print("answer is ", a//b) #floor division

elif op == ">":
    print ("answer is ", a>b) # a is greater

elif op == "<":
    print ("answer is " , a<b) #a less and b greater

elif op == ">=":
    print ("answe is ", a>=b) # greater or equal to

elif op == "<=":
    print ("answer is ", a<=b) # less than or equal to

elif op == "==":
    print ("answer is ", a==b) # both are qual to

elif op == "!=":
    print ("amswe is ", a!=b) # both are no equal to

else:
    print ("wrong number") # invalid syntax
