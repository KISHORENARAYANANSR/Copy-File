# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Load the CSV into a DataFrame.
### Step 2: 
Print the number of contents to be displayed using df.head()
### Step 3: 
The number of rows returned is defined in Pandas option settings
### Step 4:  
Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5: 
Increase the maximum number of rows to display the entire DataFrame
### Step 6: 
End the program.
## PROGRAM:
```
#To write a python program for reading content from a CSV file.
#Developed by: KISHORE NARAYANAN S R
#Register Number: 212223110023

with open("text1.txt","r") as fp:
    msg1=fp.read()
with open("copytxt","w") as fp1:
    fp1.write(msg1)

```
### OUTPUT:
![330494789-44f59c76-7b2f-405a-a9fc-95d5afeab2a2](https://github.com/KISHORENARAYANANSR/Copy-File/assets/148202102/501b4330-1c0f-405f-ac0b-7461bc6d81a3)

![330494736-d25ad1e7-5772-4432-ba1f-1a934a8b7aa3](https://github.com/KISHORENARAYANANSR/Copy-File/assets/148202102/d038fbed-54c8-4924-b05c-75ef4b9875e9)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
