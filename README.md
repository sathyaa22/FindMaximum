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


'''
Program to find maximum marks using sort()

Developed by: SATHYAA R

Registration number: 212223100052
'''


```
def max_marks(array):
    array.sort()
    return array[-1]
```

ii)	# To find the maximum marks using the list method max().

'''
Program to find maximum marks using max()

Developed by: SATHYAA R

Registration number: 212223100052
'''


```
def max_marks(array):
    return max(array)
```

iii) # To find the maximum marks without using builtin functions.

'''
Program to find maximum marks using builtin functions

Developed by: SATHYAA R

Registration number: 212223100052
'''
```
def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1
```



## Output:
i)
![alt text](<Screenshot 2024-04-10 144328.png>)
![alt text](<Screenshot 2024-04-10 144336.png>)

ii)
![alt text](<Screenshot 2024-04-10 144400.png>)
![alt text](<Screenshot 2024-04-10 144406.png>)

iii)
![alt text](<Screenshot 2024-04-10 144419.png>)
![alt text](<Screenshot 2024-04-10 144424.png>)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
