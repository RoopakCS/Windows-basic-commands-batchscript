# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# Name: Roopak C S
# Register Number: 212223220088

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
![image](https://github.com/RoopakCS/Windows-basic-commands-batchscript/assets/139228922/f4eae015-a533-4f43-b5a3-c8ccfcef35b8)



## COMMAND AND OUTPUT

![image](https://github.com/RoopakCS/Windows-basic-commands-batchscript/assets/139228922/2a956f62-c8dc-44e8-b174-c7774eeb85f9)



## COMMAND AND OUTPUT

![image](https://github.com/RoopakCS/Windows-basic-commands-batchscript/assets/139228922/2e19d58e-1a89-4bed-b353-2cfcbe8909b7)



## COMMAND AND OUTPUT

![image](https://github.com/RoopakCS/Windows-basic-commands-batchscript/assets/139228922/36f48526-7a52-4527-b670-8f9b572f40a5)


## COMMAND AND OUTPUT

![image](https://github.com/RoopakCS/Windows-basic-commands-batchscript/assets/139228922/79c703eb-ed07-4584-952a-9a9b8f28a0df)



## COMMAND AND OUTPUT


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

````batch
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
````

## OUTPUT

![image](https://github.com/RoopakCS/Windows-basic-commands-batchscript/assets/139228922/d1db2016-37fc-4b77-89db-d06f4916659d)




# RESULT:
The commands/batch files are executed successfully.

