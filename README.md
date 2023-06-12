# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text1.txt with some content in it
### Step 2: 
 Open the text1.txt file in read mode
### Step 3: 
Create a copy.txt file using write mode
### Step 4:  
Copy the content of text1.txt file to copy.txt using write function

## PROGRAM:
''' 
Program for copying the contents from one file to another file
Programmed By: Naveen Raja N.R
RegisterNumber: 212222230093
'''
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)





### OUTPUT:
![244854809-e0c6061e-d4d4-403e-9edf-443aa3e0a229](https://github.com/naveenraja2004/copy-file/assets/118707204/e9ae8122-01fb-4be3-8fdc-01362f09b3be)

![244854865-e2a41eb7-3674-45a4-b7cc-45e95bed99b8](https://github.com/naveenraja2004/copy-file/assets/118707204/37807bc8-dacb-4d4c-b074-2dcb1ded030d)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
