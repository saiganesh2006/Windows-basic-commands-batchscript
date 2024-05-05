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
## PROGRAM:
```
DEVELOPED BY: D.B.V. SAI GANESH
REGISTER NUMBER: 212223240025
```
# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND 

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
```
mkdir %userprofile%\Desktop\MyLab
cd %userprofile%\Desktop\MyLab
type nul > MyFile.txt
```
## OUTPUT:
![image](https://github.com/saiganesh2006/Windows-basic-commands-batchscript/assets/145742342/a1c2721d-1001-427a-86d3-765ebd0f3f5f)

## COMMAND 

List the contents of the "MyLab" directory.
```
dir %userprofile%\Desktop\MyLab
```
## OUTPUT:
![image](https://github.com/saiganesh2006/Windows-basic-commands-batchscript/assets/145742342/c973234c-300b-4f1c-80cc-e1d24bf73810)

## COMMAND

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
Move the "MyLab" directory to the "Documents" folder.
```
mkdir %userprofile%\Desktop\Backup
copy MyFile.txt %userprofile%\Desktop\Backup

```
## OUTPUT:
![image](https://github.com/saiganesh2006/Windows-basic-commands-batchscript/assets/145742342/6979b7c2-1b36-46b5-be15-a3bd81ddb664)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup

```
## OUTPUT
![image](https://github.com/saiganesh2006/Windows-basic-commands-batchscript/assets/145742342/e4a6d656-0066-4561-8be2-2dca4559497d)

## COMMAND
```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx

```
## OUTPUT:
![image](https://github.com/saiganesh2006/Windows-basic-commands-batchscript/assets/145742342/2ce32f40-473f-4901-95cb-4ee2d7227ea4)



# RESULT:
The commands/batch files are executed successfully.

