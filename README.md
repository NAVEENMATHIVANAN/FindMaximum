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
def max_marks(marks):
    # write your code here
    marks.sort()
    large = marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    # write your code here
    large = max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    # write your code here
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 
![image](https://github.com/NAVEENMATHIVANAN/FindMaximum/assets/119394582/3105f313-2a55-4741-ae3c-ef00db520bde)
![image](https://github.com/NAVEENMATHIVANAN/FindMaximum/assets/119394582/a7598afc-6a14-4488-838a-30530f90828d)
![image](https://github.com/NAVEENMATHIVANAN/FindMaximum/assets/119394582/ee7664f2-5211-46db-b817-e398b6be33a0)

## Output:

![image](https://github.com/NAVEENMATHIVANAN/FindMaximum/assets/119394582/02c310fb-3508-4fc8-af90-d3778bd0e652)
![image](https://github.com/NAVEENMATHIVANAN/FindMaximum/assets/119394582/adbeeedb-e4d5-4810-9d87-8935d9c66e6d)
![image](https://github.com/NAVEENMATHIVANAN/FindMaximum/assets/119394582/5e1f5f0b-37ed-481a-9bd4-caf86b748d44)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
