# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
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
num=0
with open("aravind.txt","r")as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
### OUTPUT:
![python output ](https://github.com/ARAVIND-23/Word-Count/assets/138970182/b367085b-c516-44c7-a5c0-6ae04504c0cd)



## RESULT:
Thus the program is written to find the word count from a text.
