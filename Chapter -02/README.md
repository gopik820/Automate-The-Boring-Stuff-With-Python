

### Practice Questions:-

1. What are the two values of the Boolean data type? How do you write them?

**Answer:**

```
True and False
```
2. What are the three Boolean operators?

**Answer:**
```
and, or and not
```
3. Write out the truth tables of each Boolean operator (that is, every possible combination of Boolean values for the operator and what they evaluate to).

**Answer:**

<br>

**and**
| Expression     | Evaluation    |
| -------------  | ------------- |
| True and True  | True          |
| True and False | False         |
| False and True | False         |
| False and False| False         |

**or**
| Expression     | Evaluation    |
| -------------  | ------------- |
| True and True  | True          |
| True and False | True          |
| False and True | True          |
| False and False| False         |

**not**
| Expression     | Evaluates to..|
| -------------  | ------------- |
| not True       | False         |
| not False      | True          |

4. What do the following expressions evaluate to?
(5 > 4) and (3 == 5)
not (5 > 4) 
(5 > 4) or (3 == 5)
not ((5 > 4) or (3 == 5))
(True and True) and (True == False)
(not False) or (not True)

**Answer:**
```
- False
- False
- True
- False
- False
- True
```
5. What are the six comparison operators?

**Answer:**

| Operator       |       Meaning |
| -------------  | ------------- |
| ==  | Equal to                 |
| !=  | Not equal to             |
| <   | Less than                |
| >   | Greater than             |
| <=  | Less than or equal to    |
| >=  | Greater than or equal to |


6. What is the difference between the equal to operator and the assignment operator?

**Answer:**
```
Equal to operator is used to compare the expressions on either side and assignment operator is for assign a value.
```
7. Explain what a condition is and where you would use one.

**Answer:**
```
Boolean expressions are considered as conditions and they are generally used in the flow of control statements.
```

8. Identify the three blocks in this code:

**Answer:**

```
spam = 0
if spam == 10: #<--first block
    print('eggs')
    if spam > 5: #<--second block
        print('bacon')
    else: #<--third block
        print('ham')
    print('spam')
print('spam')
```

9. Write code that prints Hello if 1 is stored in spam, prints Howdy if 2 is stored in spam, and prints Greetings! if anything else is stored in spam.

**Answer:**

```
spam = int(input())
if spam == 1:
    print("Hello")
elif spam == 2:
    print("Howdy")
else:
    print("Greetings!")
```

10. What keys can you press if your program is stuck in an infinite loop?

**Answer:**
```
CTRL +  C 
```

11. What is the difference between break and continue?

**Answer:**

```
 The break statements are used to exit from a for or while conditional loop.
 
 The continue statement is used to skip code within a loop for that iteration of the loop and transfer flow of control back to the next iteration.
```
12. What is the difference between range(10), range(0, 10), and range(0, 10, 1) in a for loop?

**Answer:**

```
range(10) 
This gives range from 0 to 10 and has only one argument

range(0, 10)
This gives same as above one and has starting and ending value.

range(0, 10, 1)
This gives same as above one and has 3 arguments starting,ending and incrementation value

```

13. Write a short program that prints the numbers 1 to 10 using a for loop. Then write an equivalent program that prints the numbers 1 to 10 using a while loop.

**Answer:**


**for loop**
```
for i in range(1,11):
    print(i)

```
**while loop**
```
i = 1
while i < 11:
    print(i)
    i+=1
```

14. If you had a function named bacon() inside a module named spam, how would you call it after importing spam?

**Answer:**

```
spam.balcon()
```
