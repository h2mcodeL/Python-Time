# Python Time
# A simple calculator written in Python

print("The Simple Calculator")
print('''To set the calculator function, \nType either of the following functions: \nadd for Addition:\nsub for Subtraction:\nmul for Multiplication:\ndiv for Division''')

#create the functions for each 

def add(x,y):
	ans = x + y
	print(ans)
	
def sub(x,y):
	ans = x - y
	print(ans)

def mul(x,y):
	ans = x * y
	print(ans)
	
	
#this could be written in a different way using the return function, as per the div function

def div(x,y):
	return x / y
	
a = input("Enter the required function: ")
x = int(input("Enter the first number: "))
y = int(input("Enter the second number: "))	

if a == "add":
	sum = add(x,y)
	
else: 
	if a == "sub":
		sum = sub(x,y)

	else:
		if a == "mul":
		sum = mul(x,y)
		
#another way to write this, for the last function, could be as follows.

		else:
			if a == "div":
				print(div(x,y))