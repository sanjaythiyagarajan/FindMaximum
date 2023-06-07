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
Developed by: SANJAY T
RegisterNumber: 212222110039
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: SANJAY T
RegisterNumber: 212222110039
'''
def max_marks(marks):
    large=max(marks)
    return max(marks)



```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: SANJAY T 
RegisterNumber: 212222110039
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max



```
## Sample Input and Output
 

## Output:
![3a python](https://github.com/sanjaythiyagarajan/FindMaximum/assets/119409242/be4ee428-48d3-48db-b145-cb56d08d31de)

![3b python](https://github.com/sanjaythiyagarajan/FindMaximum/assets/119409242/3918d5be-5426-4e1c-987d-b0cdadc9b77c)

![3c python](https://github.com/sanjaythiyagarajan/FindMaximum/assets/119409242/12f8ccc7-3c23-41c4-bb6a-7c6a0152d05f)

## Result:

Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
