

# Python Build-in data Types
* STRING
* INTEGER,FLOAT
* LIST,TUPLE,RANGE
* DICT
* SET
* BOOLEN


help(print)

print('Fist lise in python')

str="This is a string enclosed with double quote"
print(str)

str='This is a string enclosed with singel quote'
print(str)

multilinestr='''
This is a string 
with multiple
liens
'''
print(multilinestr)

strmlt="This is a first line. \n Second line.\n Third ine"
print(strmlt)

type(strmlt)

name=10
print(type(name))
name='ten'
print(type(name))
name=True
print(type(name))
name=1.5
print(type(name))


str1="i am good in ADE"
str2='Working in 5 yers in same'

result = str1+"\n"+str2
print(result)
print(type(result))

a = 10
b = 20
x = a + b
print(x)
print(type(x)) 

input("Enter your name")

name=input("Enter your name")
print(name)

name=input("Enter your name:")
age=input("Enter your Age:")
message= "Hello "+name+". Lets celebrate your "+age+" britahday"
print(message)

----------------------------------------------
String Formatting:

name="raja"
age=42
message="Hello {0}. As you enterd you are {1} you old".format(name,age)
print(message)

----------------------------------------------
Length of string

message=" Kaizen placed multiple student in Multile cloud, devops and dataops"
print(len(message))

----------------------------------------------
Sting Replication

print("Hi there Hi there Hi there")

message="Hi" *4
print(message)

----------------------------------------------
Strip(),lStrip(),rStrip()


message ="    checking  the  strip concept    "
#lstrip removes white space to the left of the line
print(message.lstrip())
#rstrip removes white space to the right side of the line
print(message.rstrip())
#strip removes white space both of the side line
print(message.strip())
