# Python Time
# A simple calculator written in Python

print("The Simple Calculator")
print('''To set the calculator function, \nType either of the following functions: \nadd for Addition:\nsub for Subtraction:\nmul for Multiplication:\ndiv for Division''')

#create the functions for each 

def add(x,y):
	return x + y
	
def sub(x,y):
	return x - y

def mul(x,y):
	return x * y
	
def div(x,y):
	return x / y
	
user = input("Enter the required function: ")
x = int(input("Enter the first number: "))
y = int(input("Enter the second number: "))	

if user == "add":
	print(add(x,y))
	
else: 
	if user == "sub":
		print(sub(x,y))

	else:
		if user == "mul":
		print(mul(x,y))
		
#another way to write this, for the last function, could be as follows.

		else:
			if user == "div":
				print(div(x,y))