# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in text mode
### Step 2: 
 Read the text using read() function.
### Step 3: 
Read the text using read() function.
### Step 4:  
Read the text using read() function.
### Step 5: 
You can refine the count by clearing the string prior t splitting or validatting the words after splitting
### Step 6: 

## PROGRAM:
```python
import sys
count= 0
with open(sys.argv[1],'r') as f1:
    for line in f1:
        word= line.split()
        count += len(word)
print("word count in file = ",count)
```

### OUTPUT:
![word count](https://user-images.githubusercontent.com/121418418/215333475-616f75e4-c791-43de-80cc-c22aef4b9c68.png)



## RESULT:
Thus the program is written to find the word count from a text.
