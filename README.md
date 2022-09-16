# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
```
## Program:
```
Program to mark the maximum of marks using the list method sort
Developed by: JANANI.V.S
RegisterNumber: 22003192
```
```

i)	# To find the maximum of marks using the list method sort.
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(list1):
    max1=list1
    for i in list1:
        if i>max1:
            max1=i
    return max1
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
### aximum of marks using the list method sort.
![output 1](https://user-images.githubusercontent.com/113497333/190679946-aa01a5f0-9fe0-45db-9c50-1e384a98592f.jpeg)

### the maximum marks using the list method max().
![output2](https://user-images.githubusercontent.com/113497333/190680038-2c03dd71-efc5-4571-b5e2-335c08b8e144.jpeg)

### the maximum marks without using builtin functions.
![Screenshot from 2022-09-16 21-32-43](https://user-images.githubusercontent.com/113497333/190681820-bf5e6386-8f6e-4185-9d15-16d5747687cc.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
