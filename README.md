# Python
 Personal review of python coding language. These are my own notes, you can use them for personal study, but please give credit when due. Thank you! 

Notes

Python follows PEMDAS - parenthesis, exponents, multiplication, division, addition, subtraction.

Escaping in python
\n - new line
\t - tab
\' - print single
\" - print double

String manipulation - strings are immutable
lower() - lowercase
upper() - uppercase
list(var) - break string into individual characters
phrase(var) - break string into words based on blank space
reverse() - reverse
join(var) - join characters 
len(var) - determin length of var (number of characters incl letters, spaces)

string index - starts at 0
stringName = 'jenny'
print(strString[0]) - prints j
print(strString[2]) - prints n

substring - a string within a string
use find() to find a substring
if no substring is found, it will return a -1

stringName2 ='jennyjennyjenq'
print(stringName2.find('jenny')) - returns 0
print(stringName2.find('q')) - returns 13

replacing a substring
stringName2 ='jennyjennyjenq'
print(stringName2.replace('q','replace')) - returns jennyjennyjenreplace

slicing - cuts string into pieces
stringName2 ='jennyjennyjenq'
print(stringName2[0:5]) - returns jenny
print(stringName2[5:8]) - returns jen


python lists
do not need to be the same type, can contain strings, ints, char, other lists.
can be manipulated by several list methods

append() - adds new object to end of the list
MyPlanets = ['Mercury', 'Venus', 'Earth', 'Mars']
MyPlanets.append('Jupiter')
MyPlanets.append('Pluto')
print (MyPlanets) - prints ['Mercury', 'Venus', 'Earth', 'Mars', 'Jupiter', 'Pluto']

extend() - works with a list of objects, adds to the end of an existing list
