# Assignment

name = "Isaac Davis"
age = 20
height = 6.3

my_sentence = "Hey Hey, my name is {}, I am {} years old, and {}." .format(name, age, height)
print (my_sentence)

num1 = 12
num2 = 9
a = num1 + num2
# I'm adding the value of num1 & num2
b = num1 - num2
# I'm subtracting the value of num2 from num1
c = num1 * num2
# I'm multiplying the value of num1 & num2
d = num1 / num2
# I'm dividing the value of num2 from num1

print ("The sum of 12 & 9 is ", a)
print ("The difference of 12 & 9 is ", b)
print ("The product of 12 & 9 is ", c)
print ("The quotient of 12 & 9 is ", d)

number = float(input("Give me a number, any number-> "))

if number > 0:
    print("Your number is positive. Nice;)")
    
elif number < 0:
    print("Your number is negative. You like negative numbers?")
    
elif number == 0:
    print("Your number is 0, isn't it.")# Exploring-Python-Concepts
