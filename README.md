# Write a program, with comments, to do the following: 
# Ask the user to enter a string with at least 10 characters assign it to variable inp.
# a. If inp has less that 10 characters, print “Invalid input!” and exit.
# b. Otherwise, if inp is an alphabetic string,
# i. print the las 4 characters of inp in uppercase.
# ii. check how many times the letter ‘e’ occurs in inp and print this value with
# a suitable message.
# c. Otherwise, print “You have entered a valid non-alphabetic string.”
# Some sample outputs for the 3 questions are given below.

###### Python code  
#Getting an input from user.

inp=input("Enter a string with at least 10 characters: ")

#if it is smaller than 10 characters

if len(inp)<10:

    print("Invalid input")

#if it is equal to 10 characters

else:

    len(inp)==10

#capitalising the last 4 characters 

    inp = inp[0:6].lower() + inp[6:10].upper()

    print(inp)

#counting the number of an alphabet in the string

    print(inp.count("e"))

else: inp!=str

    print("You have entered a valid non-alphabetic string")
