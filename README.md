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
##Program Developed by:J.Nethraa

  Reference no.:22006789
  
 
i)	# To find the maximum of marks using the list method sort.
```Python
def max_marks(marks):
    marks.sort()
    return marks[-1]


```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    return max(marks)             



```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max=list1[0]
    for x in list1:
        if x>max:
            max=x
    return max


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://user-images.githubusercontent.com/121215786/214889417-37632c5a-6d79-4eb8-bf12-6b2e7c6a9019.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
