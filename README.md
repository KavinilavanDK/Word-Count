## DATE:
# EX:9 - Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define the function for Word_Count
### Step 2: 
 Declare count = 0
### Step 3: 
Get the input from the user
### Step 4:  
Then next split the words by spaces.
### Step 5: 
Count the number of words.
### Step 6: 
Giving print statement for getting output.
## PROGRAM:
```
#Developed by: KAVI NILAVAN DK
#REGISTER NO : 212223230103
def word_count(text):
    words = text.split()
    return len(words)
user_input = input("Enter your text: ")
count = word_count(user_input)
print(f"Word count: {count}")

```
### OUTPUT:

![Screenshot (94)](https://github.com/user-attachments/assets/e53d7ea1-61f5-4298-ab2c-3d2d0e3cca24)


## RESULT:
Thus the program is written to find the word count from a text.
