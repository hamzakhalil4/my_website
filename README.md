# my_website
This is a simple calculator program that supports addition, subtraction, multiplication, and division using basic Python functions.
======================================================================================================================================
print("hello this is hamza\'s calculator")
a=int(input("Enter the number:",))
if a==0:
  print(">The num is zero:\n>Please enter the number greater than 0:")
  exit()
b=int(input("Enter the second number:",))
c=input("Chose an operator:\n\"+\"\" \n\"-\" \n\"*\" \n\"/\"\nTO perform the operation:")
sum=a+b
sub=a-b
mul=a*b
div=a/b
if c=="+":
  print("The sum of two num is",sum)
if c=="-":
  print("The sub of two num is",sub)
if c=="*":
  print("The mul of two num is",mul)
if c=="/":
  print("The div of two num is",div)

