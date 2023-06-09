# Read list elements from keyboard
```
a=[]
n=int(input("enter number of elements:"))
for i in range(n):
    a.append(int(input("enter the element:")))
for element in a:
    print(element)
print(a)
```
- take a empty list as **a**
- initialise **n** using input function to say how many elements are to be in list
- taking **for** loop with range **n**
- go on appending element in empty list by the user
- iterate each element in **a** list usung **for**
- print the elements 
- print the list **a**


**output**
```
enter number of elements:5
enter the element:2
enter the element:3
enter the element:5
enter the element:6
enter the element:4
2
3
5
6
4
[2, 3, 5, 6, 4]
```

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

- define a function called **pattern** with parameter as **n**
- initialise a **for** lopp with range from **0 to n** fro rows
- initialise another **for** loop with range **0 to i+1** for coloumns
- print symbol **#** hash *with **new line**
- call the function **pattern**

**note:** to get same pattern in reverse order then 
- modify **line 3** as range as **0 to n*
- after **line 4** write **n-=1**


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

- define a function called **pattern1** with parameter as **n**
- initialise a **for** lopp with range from **1 to n** fro rows
- initialise another **for** loop with range **1 to i+1** for coloumns
- print symbol **I**  with **new line**
- call the function **pattern1**

**note:** to get same pattern in reverse order then 
- modify **line 3** as range as **1 to n*
- after **line 4** write **n-=1**
