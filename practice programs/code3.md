# print the pattern
```
1 

2 2 

3 3 3 

4 4 4 4 
```
```
def pattern1(n):
    for i in range(1,n):
        for j in range(1,i+1):
            print(i,end=' ')
        print("\n")
pattern1(5)
```

- define a function called pattern1 with parameter as n
- initialise a for lopp with range from 1 to n fro rows
- initialise another for loop with range 1 to i+1 for coloumns
- print symbol I with new line
- call the function pattern1
- 
**note: to get same pattern in reverse order then**

- modify line 3 as range as *1 to n
- after line 4 write n-=1
