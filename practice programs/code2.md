# print the pattern
```
# 

# # 

# # # 

# # # # 

# # # # # 
```
```
def pattern(n):
    for i in range(0,n):
        for j in range(0,i+1):
            print("#",end=' ')
        print("\n")
pattern(5)
```

- define a function called pattern with parameter as n
- initialise a for lopp with range from 0 to n fro rows
- initialise another for loop with range 0 to i+1 for coloumns
- print symbol # hash *with new line
- call the function pattern

**note: to get same pattern in reverse order then**
- modify line 3 as range as *0 to n
- after line 4 write n-=1
 
