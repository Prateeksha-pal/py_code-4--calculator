# py_code-4--calculator
print("Welcome to python calculator")
while True:
	print("Enter the first number")
	n1=int(input())
	print("Enter the second number")
	n2=int(input())
	print("choose according to your need ,for>>\naddition:1\nsubstraction:2\nmultiplication:3\ndivision:4")
	ch=int(input())
	if ch==1:
		print("you choosed addition to perform!")
		print("the ans is:",n1+n2)
	elif ch == 2:
			print(" you choosed substraction to perform!")
			print("the ans is:",n1-n2)
	elif ch==3:
        	print("you choosed multiplication to perform!")
        	print("the ans is:",n1*n2)
	elif ch==4:
	 	print("you choosed division to perform!")
	 	print("the ans is:",n1/n2)
	else:
			print("your choice is invalid!")
	print("Thanks for using python calculator.") 
