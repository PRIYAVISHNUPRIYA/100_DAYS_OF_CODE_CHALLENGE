# Two timestamps
## Statement
```
Given two timestamps of the same day: a number of hours, minutes and seconds for both of the timestamps. The moment of the first timestamp happened before the moment of the second one. Calculate how many seconds passed between them.
```
## Example input
```
1
1
1
2
2
2
```
## Example output
```
3661
```
## Example input 
```
1
2
30
1
3
20
```
## Example output #2
```
50
```
```
h1=int(input())
m1=int(input())
s1=int(input())
h2=int(input())
m2=int(input())
s2=int(input())
t = m1 * 60 + h1 * 3600 + s1
t2 = m2 * 60 + h2 * 3600 + s2
print(t2 - t)
```

