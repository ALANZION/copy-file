# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
use open function to open the file in which we want to copy from and access it in read
mode
### Step 2:
read the file and store it in a variable
### Step 3:
now create a file in which we want topaste the content using write acces mode
### Step 4: 
use write function to copy the read file that has been stotred in the varible
### Step 5:
The content in the original file will be copied in the new file
### Step 6: 
End the program

## PROGRAM:
with open("Files.txt","r") as f1: with open("copy.txt","w") as f2: line = f1.read() f2.write(line)

### OUTPUT:
![Screenshot 2023-12-29 222508](https://github.com/ALANZION/copy-file/assets/145743064/47be9331-5ee0-4b16-9d2b-e4ab5a515cbd)

![Screenshot 2023-12-29 222527](https://github.com/ALANZION/copy-file/assets/145743064/aa4c4a8b-5495-4b1c-a4f9-1d652ce5977f)

![Screenshot 2023-12-29 222543](https://github.com/ALANZION/copy-file/assets/145743064/a0838702-5bed-4931-bc72-361a94dd13f9)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
