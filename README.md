#### 03603112 Programming Fundamentals II (256402) 
#### Lab03: Arrays and Collections
#### Student ID: <YOUR-STUDENT-ID>
#### Student Name: <YOUR-NAME>

## Homework 3-2
Rewrite the following Python program in a Java programming language by using the class `ArrayList`.
* Create a class, named `RemoveThirds`.
* Rewrite the following Python code in the `main` method.
 
```
 lst = [1, 2, 3, 2, 5, 3, 1, 3, 9]
 i = 0
 while i < len(lst):
    if lst[i] % 3 == 0:
        lst.pop(i)
    else:
        i = i + 1
 print lst
```
* Your program **must** display exactly the following output:

```
$ java RemoveThirds
1 2 2 5 1
```
