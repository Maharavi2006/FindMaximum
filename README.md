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
```
Developed by: Mahalakshmi.R
Register no: 212223230117
i)	# To find the maximum of marks using the list method sort.
```
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```
ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    large = max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(marks):
    maximum=marks[0]
    for i in marks:
        if(i>maximum):
            maximum=i
    return maximum
```
## Output:

1.Using the list method sort
![Screenshot 2024-03-24 185810](https://github.com/Maharavi2006/FindMaximum/assets/154535981/e1b53d59-81c7-4e08-818d-fc58a890a16f)

2.Using the list method max()
![Screenshot 2024-03-24 185950](https://github.com/Maharavi2006/FindMaximum/assets/154535981/3a82cfba-a250-484f-aab6-1a54240523be)

3.Using the builtin functions
![image](https://github.com/Maharavi2006/FindMaximum/assets/154535981/23c94c2b-5040-4502-afdf-7f205c80d1fa)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
