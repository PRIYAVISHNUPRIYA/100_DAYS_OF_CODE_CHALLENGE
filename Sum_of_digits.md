# Numbers: Sum of digits
## Statement
```
Given a three-digit number. Find the sum of its digits.
```
## Example input
```
123
```
## Example output
```
6
```
```
a = int(input())
res=0
while(a>0):
  c=a%10
  res=res+c
  a=a//10
print(res)  
```
