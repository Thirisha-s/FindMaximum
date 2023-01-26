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
Developed by: s.thirisha
RegisterNumber: 22001920
def max_marks(marks):
    marks.sort()
    return marks[-1]
```

ii)	# To find the maximum marks using the list method max().
```
Developed by: s.thirisha
RegisterNumber: 22001920
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
Developed by: s.thirisha
RegisterNumber: 22001920
def max_marks(list1):
    for i in list1:
        if i>=95:
            return i
        else:
            pass
```
## Sample Input and Output
![Screenshot_20230126_121112](https://user-images.githubusercontent.com/120380280/214773199-526e1213-f1d2-4c52-9f04-f8c90489dfea.png)

## Output:
![Screenshot_20230123_095127](https://user-images.githubusercontent.com/120380280/213975322-9ff2a5cd-3524-478f-a4d3-b2c215c1c735.png)

![Screenshot_20230123_095503](https://user-images.githubusercontent.com/120380280/213975339-14896664-fe98-4cda-9edb-5b7baa4c44a3.png)

![Screenshot_20230123_095516](https://user-images.githubusercontent.com/120380280/213975358-9a8d7a94-930b-480b-9f82-0652df13e305.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
