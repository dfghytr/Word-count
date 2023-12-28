
### Step 4: # Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
```
PC
Anaconda - Python 3.7
```
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in text mode

### Step 2: 
Read the text using read() function.
 
### Step 3: 
Split the text using space separator .we assume that words in a sentence are separated by a space character.

The length of the split list should equal the numbe of words in the text file. 

### Step 5:
You can refine the count by clearing the string prior t splitting or validatting the words after splitting 

### Step 6:
 End the program

## PROGRAM:

```
##program to find the wword count.
##developed by:Abdul kalaam k m
## register number:23005114

num_words =0
with open('text.txt','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))
```


### OUTPUT:
![image](https://github.com/23004205/Word-count/assets/138971114/ae8074bb-45bf-4712-bc98-cd5da1ab4049)

## RESULT:
Thus the program is written to find the word count from a text.
