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
![copy_text(1)](https://github.com/GURUMUR/copy-file/assets/144895197/d2392221-c147-417a-bef7-c46befb2a760)
![copy_text(2)](https://github.com/GURUMUR/copy-file/assets/144895197/08b81954-0536-485d-914a-fcd44e6844dd)
![copy_text(3)](https://github.com/GURUMUR/copy-file/assets/144895197/7c514caa-9548-4962-995d-37a7b4cf1942)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
