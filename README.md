# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys
### Step 2: 
open file using open() 
### Step 3: 
Use for loop
### Step 4:  
Use len to count the number of words.
### Step 5: 
Give print statement.
### Step 6: 
Execute the program.
## PROGRAM:
```
'''
#Program to find the word count using command line arguments.
#Developed by:NISHA.D
#Register number:212223230143
'''
fname=input("Enter file name:")
num_words=0
with open (fname,'r') as f:
  for line in f:
     words=line.split()
     num_words+=len(words)
print('Number of words : ',num_words)
```
### OUTPUT:

![Alt text](<Screenshot 2024-01-02 180649.png>)

![Alt text](<Screenshot 2024-01-02 180733.png>)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
