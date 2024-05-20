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
def max_marks(array):
    array.sort()
    return array[-1]
```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(array):
    return max(array)

```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1

```


## Output:

![image](https://github.com/bala23005271/FindMaximum/assets/155039753/dc18f5c9-ed3b-4f11-a7a8-1dd8e79c865b)
![image](https://github.com/bala23005271/FindMaximum/assets/155039753/5608ef48-f335-41a4-92f0-377a427ea53f)
![image](https://github.com/bala23005271/FindMaximum/assets/155039753/2591070f-af1c-4b1e-b71b-ebe36f2bd73c)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
