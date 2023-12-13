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
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: 
RegisterNumber: 
'''
def max_marks(marks):
    marks.sort()
    return marks[len(marks)-1]

```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: 
RegisterNumber: 
'''
def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: 
RegisterNumber: 
'''
def max_marks(list1):
    list1.sort()
    return list1[len(list1)-1]
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
#### 1st Program:
<img width="612" alt="image" src="https://github.com/Nijeesh-bit/FindMaximum/assets/89188014/10c17172-af89-4ffc-8e6f-b5042959a3c9">

#### 2nd Program:
<img width="609" alt="image" src="https://github.com/Nijeesh-bit/FindMaximum/assets/89188014/66d8c195-42de-496e-849f-ee088637940c">

#### 3rd Program:
<img width="604" alt="image" src="https://github.com/Nijeesh-bit/FindMaximum/assets/89188014/5579400a-f9a9-4223-bc52-eca7562aec20">

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
