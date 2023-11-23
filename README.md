print ("I'm Muhammed Navar","Graphic designer and co-founder of Komanga")#name, #description

if 5 > 2:
    print ("five is greater than two")
else:
    print ("two is greater than five")
#if function
    
x = 5; y = "five" #variable

"""
this is a fake comment
multi line test
"""
#multi line comment idea

print (x); print (y)
a = str (3); b = float (3) #specify type
print (a); print (b)
print (type(y)); print (type(b)) #print type

A= "Me" #doesn't overwrite a, because case sensitive

print (a,b,x,y) #multiple variable seperated by comma

print (x+b) #operator
print (y+a) #out multiple variables

def myfn(): #function
    print ("5 is " + y)
    global my_name #global fn inside a function
    my_name = 'Muhammed navar'

myfn()
print ('My name is ' + my_name)

names = ['Muhammed','Ahmed','Sayyid']
n1,n2,n3 = names #unpacking
print (n1,n2,n3)

new = frozenset ({"apple","banana","cherry"})
f1,f2,f3 = new #frozenset datatype
memview =memoryview(bytes(5)) #memoryview datatype

z = 2j
print (type(z))
#complex datatype

#type conversion
z2 = str(z)
print (type(z2))

#random number
import random
print (random.randrange (1,10))

#type casting
c = float(30)
print (c)

#multiline string
d = """ Hello everybody,
be brave and human."""
print (d)

#array
print (d[1])

#looping through a string
for x in f2:
    print (x)

#length
print (len(d))

#check
print ("human" in d)
#or
if "human" in d:
    print ("yes, 'human' is present.")
print ("brave" not in d)

#input
MyName=input ('Enter your belowed name')
print ('Hey,',MyName)

#slicing string
sl= "slice this into two"
print (sl[0:6])

#uppercase and lower
upcase= 'you are wrong'
print (upcase.upper())

#whitespace
wspacedel= ' whitespace removed '
print (wspacedel)
print (wspacedel.strip())

#replace string
restring="try more"
print (restring.replace ('t','c'))

#split string
splitstr='this is your example'
print (splitstr.split(' '))

#concatenation
print (restring+' '+splitstr)

#adding numbers and strings together
ag1,ag2,ag3=17,22,31
dscrpn="I'm Muhammed Navar, and I'm {} old, my brother is {} and sister is {}."
print(dscrpn.format(ag1,ag2,ag3))

#escape character
escchar="we are known as \"Anonymous\" & we are strong"
print (escchar)

#boolean
print (10>100)

this=3
that=5
this is not that
that is this
