# Basic Python

# Welcome statement
print('Hello World')

#Variables
a=10
b=20.2
c=a+b
print(c)
print(type(a))
print(type(b))
print(type(c))

# Taking input 
x=input('Enter value for x: ')
y=input('Enter value for y: ')
z=int(x) + int(y)                   # default input datatype is str in python so we need to specify here
print(z)
print(int(x)*int(y))
print(int(x)/int(y))

# Conditional statements
if x>y:                             #if else  
    print('x is greater')           # Unlike other languages,indentation matters in python. 4 spaces are taken as default indentation for conditional text.
else:
    print('y is greater')


p=0                                 
if p<2:                             # elif    
    print('small')
elif p<10:
    print('medium')  
else:
    print('large')       


if p>2:                              # no else
    print('not small')
elif p>5:
    print('not medium')

print('small')    

# The try/except structure --> to eliminate or catch a traceback
 # Used to surround a dangerous section of code
 # If the code in try works, the except is skipped otherwise it jumps to except

astr='Hello Bob'
try:
    istr=int(astr)                 # danger -> converting str to int
except:
    istr=-1
     
print('First', istr)   




