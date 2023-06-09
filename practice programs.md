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
