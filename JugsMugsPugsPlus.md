# JugsMugsPugsPlus
## JugsMugsPugs Plus
```
Write a program that receives a number on the input.

  - If the number is a multiple of 3, or it contains digit 3, it prints "Jugs". 
  - If the number is a multiple of 5, or it contains digit 5, it prints "Mugs".
  - If the number is a multiple of 7, or it contains digit 7, it prints "Pugs".

Otherwise, it prints the number.
```
## SPECIAL REQUIREMENT: 
```
Try and limit the number of conditional statements to not more than 4. 
And use only one print statement.
```
## INPUT
```
73
```
## OUTPUT
```
JugsPugs
```
## INPUT
```
51  
```
## OUTPUT
```
JugsMugs
```
## INPUT 
```
105
```
## OUTPUT
```
JugsMugsPugs
```
```
a=input()
b=a
c=int(a)
if((c%3==0)|(c%5==0)|(c%7==0)|('3' in a)|('5' in a)|('7' in a)):
  b=""
  if((c%3==0)|('3' in a)):
    b="jugs"
  if((c%5==0)|('5' in a)):
    b=b+"Mugs"
  if((c%7==0)|('7' in a)):
    b=b+"Pugs"
print(b)  
```
  
    

  
    
