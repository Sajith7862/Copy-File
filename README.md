# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Get source file name and destination file name from the user.

### Step 2: Open the source file in read mode.
 
### Step 3: Read the contents from the source file.

### Step 4:  Open the destination file in write mode.

### Step 5:  Write the contents read from the source file into the destination file.

### Step 6: Print a message indicating successful completion.

## PROGRAM:
```
DEVELOPED BY:MOHAMED HAMEEM SAJITH J
REGISTER NUMBER :212223240090
def copy_file(source_file, destination_file):
    try:
        with open(source_file, 'r') as source:
            with open(destination_file, 'w') as destination:
                destination.write(source.read())
        print("Contents copied successfully.")
    except FileNotFoundError:
        print("File not found.")

def main():
    source_file = input("Enter the source file name: ")
    destination_file = input("Enter the destination file name: ")
    copy_file(source_file, destination_file)

if __name__ == "__main__":
    main()
```

### OUTPUT:

![image](https://github.com/Sajith7862/Copy-File/assets/145972360/68271977-142d-4c9e-8f90-9ff2ca148c71)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
