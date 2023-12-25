# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a variable and enter the input.
### Step 2: 
Then open the text file. 
### Step 3: 
Use len() function to count the words. 
### Step 4:  
Print the words in the text.

## PROGRAM:
```
'''
DEVELOPED BY:S.Sanjay Balaji
REGISTER NUMBER: 23005804

'''
num_words=0
with open('data.txt','r') as f1:
    for i in f1:
        word=i.split()
        num_words += len(word)
print("number of words in the file = {}".format(num_words))
```
### OUTPUT:

![image](https://github.com/SanjayBalaji0/Word-count/assets/145533553/af2948c2-10cf-4f0b-aa32-03fa9e472424)


## RESULT:
Thus the program is written to find the word count from a text.
