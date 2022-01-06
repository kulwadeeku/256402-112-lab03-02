#### 03603112 Programming Fundamentals II (256402) 
#### Lab03: Arrays and Collections
#### Student ID: <YOUR-STUDENT-ID>
#### Student Name: <YOUR-NAME>

## Homework 3-1
Rewrite the following Python program in a Java programming language.
* Create a class, named `BinarySearch`
* Add a static method, named `binarySearch`
* In the `main` method of the `BinarySearch` class, 
  * declares an array `A` and initializes it with the following data:
    `1, 2, 4, 5, 7, 8, 11, 13`
  * display the result of calling the method `binarySearch` on array `A` for the value `5`, `13`, and `10` respectively.

```
def binary_search(lst, v):
    i, j = 0, len(lst)
    while i < j:
        mid = (i + j) // 2
        if v < lst[mid]:
            j = mid
        elif v > lst[mid]:
            i = mid + 1
        else:
            return mid
    return -1
```
* Your program **must** display exactly the following output:

```
$ java BinarySearch
'5' is at location 3
'13' is at location 7
'10' does not exist!
```
