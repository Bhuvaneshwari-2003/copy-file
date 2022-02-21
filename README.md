# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM:
Step 1:
Get the file name and location from the user.

Step 2:
Give a new file name to create a copy of a file content.

Step 3:
Read the file and close the file.

Step 4:
Now write the content in the new file.

Step 5:
When done print "File copied successfully".

Step 6:
End of the program.



## PROGRAM:
print("Enter the Name of Source File: ")
sFile = input()
print("Enter the Name of Target File: ")
tFile = input()

fileHandle = open(sFile, "r")
texts = fileHandle.readlines()
fileHandle.close()

fileHandle = open(tFile, "w")
for s in texts:
    fileHandle.write(s)
fileHandle.close()

print("\nFile Copied Successfully!")
### OUTPUT:

![Screenshot (58)](https://user-images.githubusercontent.com/94828604/154994300-04feaf4a-8806-40b7-b1de-51a53bc01843.png)
![Screenshot (60)](https://user-images.githubusercontent.com/94828604/154994665-0865db4e-3e1d-4073-baf6-49df1fe43e5b.png)
![Screenshot (62)](https://user-images.githubusercontent.com/94828604/154995247-4b15bdef-c138-4721-b51d-2b9417522b1e.png)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
