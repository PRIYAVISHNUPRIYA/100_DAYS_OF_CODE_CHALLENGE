# JugsMugsPugsPlus Reverse
## JugsMugsPugsPlus and Reverse
```
Write a program that receives a number on the input.
It also should receive another value 'rev' (either 1 or 0) on the input. 

  - If the number is a multiple of 3, or it contains digit 3, it prints "Jugs". 
  - If the number is a multiple of 5, or it contains digit 5, it prints "Mugs".
  - If the number is a multiple of 7, or it contains digit 7, it prints "Pugs".

  - If the number is a multiple of both 3 and 5, it prints "JugsMugs".
        - also if number contains 3 and 5, it prints "JugsMugs"
  - If the number is a multiple of both 3 and 7, it prints "JugsPugs".
        - also if number contains 3 and 7, it prints "JugsPugs"
  - If the number is a multiple of 3, 5 and 7, it prints "JugsMugPugs".
        - also if number contains 3, 5 and 7, it prints "JugsMugsPugs"

Otherwise, it prints the number.
```
## REVERSE REQUIREMENT:
```
If the boolean 'rev' is True (or 1), then reverse the order of printing. 
  - "PugsJugsMugs" for multiples of 3, 5 and 7
  - "PugsMugs" for multiple of 5 and 7
  - "MugsJugs" for multiple of 3 and 5 
  - "PugsJugs" for multiple of 3 and 7
```
## INPUT 
```
73 
False  # contains 3 and 7
```
## OUTPUT
```
JugsPugs
```
## INPUT 
```
73 
True  # contains 7 and 3, print reverse order
```
## OUTPUT
```
PugsJugs
```
## INPUT 
```
51  # multiple of 3 and contains 5
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
rev=input()
g=rev
f=int(rev)
d=""
e=["","",""]
if((c%3==0)|('3' in a)):
  e[0]="Jugs"
if((c%5==0)|('5' in a)):
  e[1]="Mugs"
if((c%7==0)|('7' in a)):
  e[2]="Pugs"
if(f==1):
  e.reverse()
for i in e:
  d=d+i
print(d or c)  
```





