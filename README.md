# string
Program 1
str=input("enter a string\n")
str2=str[::-1]
if(str==str2):
	print("palindrome")
else:
	print("not a palindrome")


Program 2
n=input("Enter a string\n")
x=n.split(" ")
a=len(x)
for i in range(a):
	n=x[i]
	b=n[::-1]
	print(b)

Program 3
s=input("Enter\n")
b=s.split(" ")
a=len(b)
for i in range(a):
	s=b[i]
	print(s[0])

Questionaries:
1. What are the advantages of using slice of strings? Slicing is a technique in Python that allow you to specific element or a sub-set of elements from
a container object using their index values. Slicing saves you from having to write loop statements to go through the indexes of your string to find or access certain substrings.
 

2.Can you directly replace a character in string just by assigning? If not, state the reason. i Also give the solution
 
We can't modify a string. We can update a variable with a new string.
 For example to change s = "Hello" to s = "Hellp"
we can't do
>>>s="Hello"
>>> s[3] ="p"
We have to do
>>>s="Hello" 
>>>s=s[:4]+"n"

3. What is the use of negative index?
Negative index helps to read the string in the opposite direction.
If use of negative direction was not allowed then we had to use len (string) -1 as the index of the last element and the preceding elements accordingly. Use of negative index removes that hustle and makes writing of code  simpler.
