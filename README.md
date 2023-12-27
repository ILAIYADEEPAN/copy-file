# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
use open function to open the file in which we want to copy from and access it in read mode
### Step 2: 
 read the file and store it in a variable
### Step 3: 
now create a file in which we want topaste the content using write acces mode
### Step 4:  
use write function to copy the read file that has been stotred in the varible
### Step 5: 
the content in the original file will be copied in the new file
### Step 6: 
End the program
## PROGRAM:
```

with open("Files.txt","r") as f1:
    with open("copy.txt","w") as f2:
        line = f1.read()
        f2.write(line)
```



### OUTPUT:
PROGRAM
![output1](https://github.com/ILAIYADEEPAN/copy-file/assets/147473334/39b431cf-6162-4500-8529-0f72292b4c9d)


File.txt:
![output2](https://github.com/ILAIYADEEPAN/copy-file/assets/147473334/8fc00094-807a-4a5e-b452-49b097cd7dfc)

Copy.txt:
![output3](https://github.com/ILAIYADEEPAN/copy-file/assets/147473334/a0fa2974-6c1b-4167-9f6f-05ee29db3dd5)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
