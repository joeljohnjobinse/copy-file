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
Copy the content of text1.txt to to copy.txt using write function
## PROGRAM:
#Program to copy a file
#Developed by: Joel John Jobinse
#Register Number: 212223240062
with open("text1.txt","r") as fp:
    msg1=fp.read()
with open("copy.txt","w") as fp1:
    fp1.write(msg1)
### OUTPUT:
![py5c1](https://github.com/joeljohnjobinse/copy-file/assets/138955488/e7347b75-1fd4-463b-bbb0-12a43f5d1c9d)
![py5c2](https://github.com/joeljohnjobinse/copy-file/assets/138955488/feaca361-5383-44ae-ba9a-42594790d7a3)
![py5c3](https://github.com/joeljohnjobinse/copy-file/assets/138955488/5c7bcf2e-25c4-4b8d-95e8-9a8614f29172)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
