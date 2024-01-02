# Word-count
NAME: SAI VISHAL D<BR>
REF.NO: 23013576
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
Hardware - PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
To write a python program for getting the word count from a text file

### Step 2: 
Open the required file by using the function "with".

### Step 3: 
Then use the laptop to assign the i value in the file.

### Step 4:  
Using split function to spilt the words

### Step 5: 
Finding the given length of the words by using len() fuction.

### Step 6: 
Calling the function and Printing the number of words.
## PROGRAM:
```
DEVELOPED BY : SAI VISHAL D
REFERENCE NUMBER : 23013576

num=0
with open("sample.txt","r")as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
```

### OUTPUT:

![Alt text](<Screenshot 2024-01-02 134304.png>)

## RESULT:
Thus the program is written to find the word count from a text.
