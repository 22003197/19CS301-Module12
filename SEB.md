# Exp.no: 60
## SEB

### AIM

To write a python program that after inserting few elements in stack, check and display whether the stack is full or not. 

### ALORITHM 

1. Start the program.

2. Import LifoQueue from the queue module.

3. Create a stack with a maximum size of 4.

4. Push elements 'a', 'b', and 'c' onto the stack using put().

5. Check if the stack is full using stack.full():
   If full, print "Stack is full".
   Else, print "Stack is not full".

6. Terminate the program.

### PROGRAM

```
from queue import LifoQueue
stack = LifoQueue(maxsize=4)
stack.put('a')
stack.put('b')
stack.put('c')
if stack.full():
    print("Stack is full")
else:
    print("Stack is not full")
```

### OUTPUT

![image](https://github.com/user-attachments/assets/ca829d43-475a-4ba9-9193-ed575015e971)

### RESULT

Thus the python program was successfully created.
