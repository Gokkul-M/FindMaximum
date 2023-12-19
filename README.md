# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: 
RegisterNumber: 
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]

```

ii)	# To find the maximum marks using the list method max().
```

''' 
Program to find the maximum marks using the list method max().
Developed by: 
RegisterNumber: 
'''
def max_marks(marks):
    max_marks=max(marks)
    return max_marks
    

```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: 
RegisterNumber: 
'''
def max_marks(numbers):
    maximum_num=numbers[0]
    for num in numbers:
        if num>maximum_num:
            maximum_num=num
    return maximum_num

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
### 1:
![image](https://github.com/Gokkul-M/FindMaximum/assets/144870543/84e31af9-e171-4b3b-9f7b-ccc310ee534a)
### 2,
![image](https://github.com/Gokkul-M/FindMaximum/assets/144870543/0b433c2d-e3c5-4acf-bdae-d887023c3605)
### 3,
![image](https://github.com/Gokkul-M/FindMaximum/assets/144870543/5e336f73-b4f8-4b36-a8be-cdc4b09c4d00)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
