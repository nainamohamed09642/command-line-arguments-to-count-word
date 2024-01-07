# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
to write a program
### Step 2: 
import the file
### Step 3: 
open the file
### Step 4:  
write the function to count the count
### Step 5: 
print the result
### Step 6: 
end the program

## PROGRAM:
```
#This program developed by: naina mohamed
#number:23010605

import sys
f1=open(sys.argv[0])
data=f1.read()
word=data.split()
print("The word count is",len(word))
f1.close
OUTPUT:
```

### OUTPUT:
![292681325-bba4fd93-25a6-4d3a-a7f3-64e5ac2956dc](https://github.com/nainamohamed09642/command-line-arguments-to-count-word/assets/151916360/7907d3ca-129b-4cff-a203-532fbcd87624)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
