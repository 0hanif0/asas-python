# ASAS PYTHON

## Srings
```pyhton
print("Hello , world!")
print('Hello , world!')
print("""multiple lines!""")
print('\n') new line
#comment
```

## Math
```python
print(50+50) #add
print(50-50) #subtract
print(50*50) #multiply
print(50/50) #divide
print(50**2) #exponents
print(50%6) #modulus
print(50//6) #no leftovers
```

## Variables and Methods
```python
quote="Cinta itu buta" #variables
print(quote)
print(quote.upper()) #uppercase method
print(quote.lower()) #lowercase method
print(len(quote)) #length
name="Hanif"` #string
age=18 #int
gpa=3.7 #float
print(" My name is " + name + " and I am " + str(age) + " years old. ")
```

## Functions
```python
def who_am_i(): #function
  name="Hanif"
  age=24
  print
who_am_i() #calling function

def add_one_hundred(num): #parameter num
  print(num+100)
add_one_hundred(50) #50+100

def add(x,y): #multiple parameter
  print(x+y)

add(7,7) #7+7

def multiply(x,y):
  return x*y #store value
  
print(multiply(7,7)) #print the store value

def square_root(x):
  print(x**,5)
square_root(64) #square root 64
```

## Boolean Expressions (true or false)
```python
print("Boolean expressions")
bool1=True
bool2=3*3==9
bool3=False
bool4=3*3!=9
print(bool1,bool2,bool3,bool4) #True,True,False,False
print(type(bool1)) #type variable
```

## Relational and Boolean Operators
```python
greater_than=7>5
less_than=5<7
greater_than_equal_to=7>=7
less_than_equal_to=7<=7

test_and=(7>5) and (5<7) #True
test_or=(7>5) or (5<7) #True
test_not=not True #False
```

## Conditional statement
```python
def drink(money):
  if drink(money):
    return "yes"
  else:
    return "no"
print(drink(3)) #yes
print(drink(1)) #no

def alcohol(age,money): #multiple
  if (age>=21) and (money>=5):
    return "yes dapat alcohol"
  elif (age>=21) and (money<5):
    return "no money"
  elif (age<21) and (money>=5):
    return "too young"
  else
    return "no money and young haram"
    
print(alcohol(21,5)) #yes dapat alcohol
```

## Lists -brackets[] 0 is the first
```python
movies=["movie1","movie2","movie3"]
print(movies[1:4]) #movie1 and movie4
print(movie[-1]) #last movie
print(len(movies)) #how many movie
movies.append("new movie") #add movie at last
movies.pop() #delete movie at last
```

## Tuples -do not change()
```python
grades=("a","b","c","d")
print(grades[1])
```

## Looping
```python
# for loops - start to finish of an iterate
vegetables=["cucumber","spinach","cabbage"]
for x in vegestables:
  print(x)
  
# while loops - execute as long as true
i=1
while i<10:
  print(i)
  i+=1
```

## Importing Modules
```python
#!/bin/python3
import sys #system functions and parameter
import datetime #1
from datetime import datetime #2
print(datetime.now())
from datetime import datetime as dt #3
print(dt.now())
```

## Advanced Strings
```python
my_name="Hanif"
print(my_name[0]) #H
print(my_name[-1]) #f

sentence="This is a sentence."
print=(sentence[:4]) #This
print=(sentence.split()) #['This','is','a','sentence.']

sentence_split=sentence.split()
sentence_join=''.join(sentence_split)
print(sentences_join) #normal

quote="he said, \"give me all your money\""
print(quote) #print double quote ""

too_much_space="       hello       "
print(too_much_space.stripe()) #hello

print("a" in "Apple") #false
movie="The Hangover"
print("My fav movie is {}.".format(movie)) #My fav movie is The Hangover.
```

## Dictionaries -key/value pairs{}
```python
drinks={"sirap":2,"oren":3,"kosong":1} #air=key harga=value
print(drinks) #{"sirap":2,"oren":3,"kosong":1}
```
