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
#Program Developed by: Tharun Sridhar
#Register No:212223230230

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```Python
#Program developed by: Tharun Sridhar
#Register No: 212223230230

def max_marks(marks):
    large=max(marks)
    return large



```

iii) # To find the maximum marks without using builtin functions.
```Python
#Program developed by: Tharun Sridhar
#Register No: 212223230230

def max_marks(marks):
    max_mark=0
    for i in marks:
        if i>max_mark:
            max_mark=i
    return max_mark


```



## Output:
![image](https://github.com/Tharun0707/FindMaximum/assets/145548496/359c209a-9c46-4103-852c-5c5fe3004516)

![image](https://github.com/Tharun0707/FindMaximum/assets/145548496/89cc0dbc-0ac9-491a-a290-e0dfdd69346e)

![image](https://github.com/Tharun0707/FindMaximum/assets/145548496/3eb3f9dd-353d-4e38-8e25-719ad25e26df)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
