### Practice Questions:-

1. Write an assert statement that triggers an AssertionError if the variable spam is an integer less than 10.

**Answer**

```
assert spam >= 10, 'spam variable is less than 10.'
```

2. Write an assert statement that triggers an AssertionError if the variables eggs and bacon 
contain strings that are the same as each other, even if their cases are different (that is, 'hello' and 'hello' are considered the same, and 'goodbye' and 'GOODbye' are also considered the same).

**Answer**

```
assert eggs.lower() != bacon.lower(), 'eggs and bacon variables are same.'
```

3. Write an assert statement that always triggers an AssertionError.

**Answer**

```
assert false
```


4. What are the two lines that your program must have in order to be able to call logging.debug()?

**Answer**

```

import logging
logging.basicConfig(level=logging.DEBUG, format=' %(asctime)s -
%(levelname)s -  %(message)s')

```

5. What are the two lines that your program must have in order to have logging.debug() send a logging message to a file named programLog.txt?

**Answer**

```

import logging
logging.basicConfig(filename='programLog.txt', level=logging.DEBUG,
format=' %(asctime)s -  %(levelname)s -  %(message)s')

```

6. What are the five logging levels?

**Answer**
```
Warning
Critical
Error
Info
Debug
```
7. What line of code can you add to disable all logging messages in your program?

**Answer**
```
logging.disable(logging.CRITICAL)
```
8. Why is using logging messages better than using print() to display the same message?

**Answer**
```
It must be done manually and that takes time.
```
9. What are the differences between the Step Over, Step In, and Step Out buttons in the debugger?

**Answer**
```
Step Over - execute the function call without stepping.
Step In - moves the debugger into function.
Step Out - execute the rest of the code until it steps out of the function.
```
10. After you click Continue, when will the debugger stop?

**Answer**
```
When it reaches the end of the program.
```
11. What is a breakpoint?

**Answer**
```
break point is allows us to cause the debugger to pause the line that contains break point.
```
