# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
# Step 1:
Create a file using Notepad with the file1.txt .

# Step 2:
Open Google Colab and mount the drive for using the created file in the Colab.

# Step 3:
Now open the text file in read mode.

# Step 4:
Then read the content in the file and store the data in a variable.

# Step 5:
Now open the new uncreated or an empty file using a different file object, by "w+" mode and write the content derived from first file using write().

# Step 6:
End the program 

## PROGRAM:
```python
#Developed by: Gurumurthy S
#Register number: 212223230066
f=open("file1.txt","r")
content=f.read()
f1=open("myfile.txt","w+")
f1.write(content)
print("The content that is been copied to the new file is:",content)
```
### OUTPUT:
![out1](copy_text(1).png)
![out2](copy_text(2).png)
![out3](copy_text(3).png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.