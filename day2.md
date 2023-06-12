# variables
- variables are nothing but a container which holds the value 
- variable stores the value and address to the memory location
- variable is a name which is used to refer memory location of thatvalue

ex: x=10
- python reads from RHS to LHS
- python decides the type of value
- then it loads the binary vaklue of the value to a memory location which refered by variable

# data types and data structures
**data types**--numbers---.int,float,complex
               --boolean
               --string
**data structures**--lists,tuples,set,dictionary

# reference count
- ex: x=19    =. the reference count of 10 is 1
- ex: x=10
      y=10     =. reference count of 10 is 2
 - when reference count of a value becomes **0** then it is garbage collected
 - e: x=10
      x=20 
        here a single variabke cant refer a two values so the previous value of that varible will be garbage collected

# variable assignment
- a=10   =. it is single value assignment varible **a** is refering to the memory location of 10
- a=b=10  =. it is single value multiple variable variable **a and b** refering to the same memory location of 10 i.e. **a and b** have same address
- a,b=10,20   =. it is multiple value multiple variable i.e. **a and be** refreing different memory location for different values
