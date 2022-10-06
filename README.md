# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: 
Use open function to open the file in which we want to copy from and access it in read mode.

### Step 2: 
Read the file and store in a variable.

 
### Step 3: 
Now create a new file in which we want to paste the content using write access mode.


### Step 4: 
Use write function to copy the read file that has been stored in the variable.


### Step 5: 
The content in the original file will be copied in the new file.

### Step 6:
End the program

## PROGRAM:
```python
Developed by: yuvabharathib
RegisterNumber: 22002787

with open('yuva.txt','r')as f1:
    with open('myfile.txt','a') as f2:
        for line in f1:
            f2.write(line)
 ```           

### OUTPUT:
![Screenshot from 2022-10-06 13-47-52](https://user-images.githubusercontent.com/113497404/194260407-355fba64-9a4c-40cc-aadf-120f115c323c.png)

Text file:
![Screenshot from 2022-10-06 13-50-02](https://user-images.githubusercontent.com/113497404/194261083-2b75c204-55f9-4aa2-8d0e-2c7fc88c08de.png)

Copy file:
![Screenshot from 2022-10-06 13-50-14](https://user-images.githubusercontent.com/113497404/194261193-7dc98f45-7031-462e-b40f-834b998ed0bb.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
