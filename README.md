# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

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
## Developed by : Arikatla Hari Veera Prasad
## Reg No.      : 212223240014
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.

## COMMAND AND OUTPUT
```
Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
mkdir %userprofile%\Desktop\MyLab
```
![image](https://github.com/Hariveeraprasad-2006/Windows-basic-commands-batchscript/assets/145049988/f90fc61a-1882-4880-85f9-71308ffd05b4)

## COMMAND AND OUTPUT
```
List the contents of the "MyLab" directory.
cd %userprofile%\Desktop\MyLab
```
![image](https://github.com/Hariveeraprasad-2006/Windows-basic-commands-batchscript/assets/145049988/93965c80-ff16-4084-b0e1-9443eaba7d7f)
![image](https://github.com/Hariveeraprasad-2006/Windows-basic-commands-batchscript/assets/145049988/859ec11a-1f3c-49fb-92e5-765f7aeb98be)


## COMMAND AND OUTPUT
```
Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
dir %userprofile%\Desktop\MyLab
```
![image](https://github.com/Jeevithaelumalai/Windows-basic-commands-batchscript/assets/118708245/40de307a-60ec-44ed-a9d2-94ed73c8d346)

## COMMAND AND OUTPUT
```
Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup
mkdir %userprofile%\Desktop\Backup
```
![image](https://github.com/Jeevithaelumalai/Windows-basic-commands-batchscript/assets/118708245/47278c6b-2a0d-45f3-bdb9-2f0cc267fbc3)
![image](https://github.com/Jeevithaelumalai/Windows-basic-commands-batchscript/assets/118708245/364ae2ec-b6ff-4583-b92f-bbc9533b06d0)

## COMMAND AND OUTPUT

mv Myfile.txt %userprofile%\Documents

![Uploading image.png…]()

## Exercise 2: Advanced Batch Scripting
```
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```
## OUTPUT

![image](https://github.com/Hariveeraprasad-2006/Windows-basic-commands-batchscript/assets/145049988/25710538-0b35-4f19-b8cf-d1dc07c94c41)

# RESULT:
The commands/batch files are executed successfully.




# RESULT:
The commands/batch files are executed successfully.

