# Ex08-Windows-basic-commands-batchscript

## AIM:
To execute Windows basic commands and batch scripting

## DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




## WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
### Create a directory named "MyLab" on the desktop.

### COMMAND AND OUTPUT
![1](1creatmylab.png)

### Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

### COMMAND AND OUTPUT
![2](2change_and_create_myfile.png)

### List the contents of the "MyLab" directory.

### COMMAND AND OUTPUT

![3](3list_mylab.png)

### Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

### COMMAND AND OUTPUT

![4](4copy_myfile_to_backup.png)

### Move the "MyLab" directory to the "Documents" folder.

### COMMAND AND OUTPUT

![alt text](5move_mylab_to_Documents.png)

## Exercise 2: Advanced Batch Scripting
### Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

### BatchScript.bat
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\DocBackup\*.docx
echo Backup and deletion completed successfully!s
```

## OUTPUT

![Bacth_script_output](BatchscriptOutput.png)


# RESULT:
The commands/batch files are executed successfully.

