# Sum of cubes
## Statement
```
For the given integer N calculate the following sum:

1³ + 2³ + ... + N³
```
## Example input
```
3
```
## Example output
```
36
```
```
a = int(input())
sum=0
for i in range(1,a+1):
  sum=sum+(i**3)
  i+=1
print(sum)  
```
