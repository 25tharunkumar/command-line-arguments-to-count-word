# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module

### Step 2:
Open the file with sys.argv[1]

### Step 3:
Use the for loop to select the content in file

### Step 4:
Use split function to to separate the file content into words or strings

### Step 5:
Count the length of the words using len

### Step 6:
Print the number of words

### PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments
Developed by: Tharun Kumar.M
RegisterNumber: 212222100056

import sys
fp=open(sys.argv[1], 'r')
count=0
for line in fp:
    list1=line.split()
    count+=len(list1)
print("No of words in a file",count)
```
### OUTPUT:
![image](https://github.com/25tharunkumar/command-line-arguments-to-count-word/assets/123470785/2f0acd2c-7e47-4528-a2ff-a51c0e2538e4)
![image](https://github.com/25tharunkumar/command-line-arguments-to-count-word/assets/123470785/ffcffd7f-21db-4008-9f26-5abac8e85ecb)
![image](https://github.com/25tharunkumar/command-line-arguments-to-count-word/assets/123470785/b8031672-735c-4e3c-b9d6-ce73addd269c)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
