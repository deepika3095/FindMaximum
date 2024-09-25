# DATE: 
# EX-06 Find the maximum of a list of numbers
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
DEVELOPED BY: DEEPIKA R
REGISTER NUMBER: 212223230038
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```
## Output:
![image](https://github.com/user-attachments/assets/0e81fba4-7a20-44ea-a2e1-af73ca17c1aa)

ii)	# To find the maximum marks using the list method max().
```
DEVELOPED BY: DEEPIKA R
REGISTER NUMBER: 212223230038
def max_marks(marks):
    large=marks[len(marks)-1]
    marks.sort(reverse=True)
    large=marks[0]
    return large
```
## Output:
![image](https://github.com/user-attachments/assets/51da0c5e-9002-42b7-b3bc-30196a289756)

iii) # To find the maximum marks without using builtin functions.
```
DEVELOPED BY: DEEPIKA R
REGISTER NUMBER: 212223230038
def max_marks(marks):
    maxmark=0
    for i in marks:
        if i>maxmark:
            maxmark=i
    return maxmark
```
## Output:
![image](https://github.com/user-attachments/assets/3257f6d9-39f3-4cf4-b583-7eab11d391c7)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
