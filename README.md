# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys
### Step 2: 
 initially make count = 0
### Step 3: 
initially make count = 0
### Step 4:  
by using for loop name the function as "line"
### Step 5: 
split the line using .split
### Step 6: 
split the line using .split
## PROGRAM:
#program to find commaa=nd-line-arguments-to-count-word
#developed by:vidhyasri.k

#register number:22008468

import sys

count = {}

with open(sys.argv[1], 'r') as f:

    for line in f:

        for word in line.split():

            if word not in count:

                count[word] = 1

            else:

                count[word] += 1
print(count)
d
f.close()


### OUTPUT:
![command.png](./command.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
