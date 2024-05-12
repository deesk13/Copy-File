# Copy-File
## NAME: DEVA DHARSHINI I

## REGISTER NO: 212223240026
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Load the CSV into a DataFrame.

### Step 2: 
 Print the number of contents to be displayed using df.head().

### Step 3: 
The number of rows returned is defined in Pandas option settings.
### Step 4:  
Check your system's maximum column with the pd.options.display.max_column statement.

### Step 5: 
Increase the maximum number of rows to display the entire DataFrame

### Step 6: 
End the program.
## PROGRAM:
```
Developed by: DEVA DHARSHINI I
Register no: 212223240026
with open("text.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![Screenshot 2024-05-12 141744](https://github.com/deesk13/Copy-File/assets/150927063/50403b54-0f14-46dc-9136-e7bd78a7638c)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
