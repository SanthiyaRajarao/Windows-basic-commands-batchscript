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
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
%userprofile%\Desktop\MyLab
![image](https://github.com/user-attachments/assets/27cab69a-8541-4880-81a5-9ec662c16aca)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
%userprofile%\Desktop\MyLab
![image](https://github.com/user-attachments/assets/dd0a1d1a-9cc0-49bc-a8b4-c81ba9d7638f)
![image](https://github.com/user-attachments/assets/64b08262-0474-456c-9983-0c11474ce853)



## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
%userprofile%\Desktop\MyLab

![image](https://github.com/user-attachments/assets/0071d528-c0ad-4055-93f3-dc381008125b)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
![image](https://github.com/user-attachments/assets/be1b64f6-b45c-455c-9596-b320d30587f5)
![image](https://github.com/user-attachments/assets/2d553a51-23f3-48d0-be5f-8638d1418832)


## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/bf3c20ec-7b93-4bfe-9de8-2a1be17718d4)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.


@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!




## OUTPUT

![image](https://github.com/user-attachments/assets/e3fa5270-d959-4f52-b25a-79adbbadc519)




# RESULT:
The commands/batch files are executed successfully.

