# FIND THE MAXIMUM OF A LIST OF NUMBERS :

## AIM :

To write a program to find the maximum of a list of numbers.

## EQUIPMENTS REQUIRED :
-	Hardware – PCs  
-	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHIM :

1.	Get the list of marks as input 
2.	Use the sort() function or max() function or use the for loop to find the maximum mark  
3.	Return the maximum value .

## PROGRAM :


### To find the maximum of marks using the list method sort.
```python
Program to mark the maximum of marks using the list method sort
Developed by: MIDHUN AZHAHU RAJA P
RegisterNumber: 22008311

def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large

```

### To find the maximum marks using the list method max().
```python
Program to mark the maximum of marks using the list method sort
Developed by: MIDHUN AZHAHU RAJA P
RegisterNumber: 22008311

def max_marks(marks):
    large = max(marks)
    return large


```

### To find the maximum marks without using builtin functions.
```python
Program to mark the maximum of marks using the list method sort
Developed by: MIDHUN AZHAHU RAJA P
RegisterNumber: 22008311

def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max

```
## SAMPLE INPUT AND OUTPUT :

![output](./img/max_marks1.jpg) 

## OUTPUT :

![max_marks2](https://user-images.githubusercontent.com/118054670/213929657-7505615c-9d08-403d-8e8f-6a337b62f4da.jpg)


## RESULT :

Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
