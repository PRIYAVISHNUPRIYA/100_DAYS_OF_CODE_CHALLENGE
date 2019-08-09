# Days in month
## Statement
```
Given a month - an integer from 1 to 12, print the number of days in it in the year 2017.
```
## Example input #1
```
1
(January)
```
## Example output #1
```
31
```
## Example input #2
```
2
(February)
```
## Example output #2
```
28
```
```
a = int(input())
if((a==1)|(a==3)|(a==5)|(a==7)|(a==8)|(a==10)|(a==12)):
  print("31")
elif((a==4)|(a==6)|(a==9)|(a==11)):
  print("30")
else:
  print("28")
```
