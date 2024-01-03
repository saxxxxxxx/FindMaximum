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
#Developed by:NITHISH MD
#Register No:23009587
'''Program to mark the maximum of marks using the list method sort
Developed by: Nthish D.M
RegisterNumber: 23009587'''
def max_marks(marks):
    marks.sort()
    max_mark =marks[-1]
    return max_mark

```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Nithish D.M
RegisterNumber: 23009687
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i>max:
            max = i
    return max
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Nithish D.M
RegisterNumber: 23009587
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i>max:
            max = i
    return max
```
## Sample Input and Output
## Output:
i)	# To find the maximum of marks using the list method sort.
![image](https://github.com/saxxxxxxx/FindMaximum/assets/154911090/e170f2a7-6614-45ec-a7f2-c11d3c473b03)

ii)	# To find the maximum marks using the list method max().
![image](https://github.com/saxxxxxxx/FindMaximum/assets/154911090/54c5944a-4e35-44d3-846f-e75791b5964e)

iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/saxxxxxxx/FindMaximum/assets/154911090/37d86d11-679b-47db-91a1-ec8cef9bd993)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
