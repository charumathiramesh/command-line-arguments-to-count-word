# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Step 1:
Import the sys module.

## Step 2:
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]

## Step 3:
Read the file using read() method.

## Step 4:
Use split() method to split the file content into words.

## Step 5:
Use len() to find the total words.

## Step 6:
Use len() to find the total words. 

## PROGRAM:
```
#Program for getting word count from the contents of a file using command line arguments.
#Developed by: Charumathi R
#RegisterNumber: 22006878

import sys
with open(sys.argv[1],'r') as f:
    num_of_words =0
    for i in f:
        word =i.split()
        num_of_words += len(word)
print("Number of words={}".format(num_of_words))
```

### OUTPUT:
![OUTPUT](./commandline.jpeg)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
