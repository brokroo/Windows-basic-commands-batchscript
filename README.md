# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

#### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

#### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
#### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
### Exercise 1: Basic Directory and File Operations

Create a directory named "my-folder"
### COMMAND AND OUTPUT

<img width="606" height="223" alt="image" src="https://github.com/user-attachments/assets/4d207104-f6a9-497b-ad33-53a6bc26d9d3" />

Remove the directory "my-folder"
### COMMAND AND OUTPUT

<img width="842" height="371" alt="image" src="https://github.com/user-attachments/assets/36a07397-21ff-4219-bf0e-18afd72a958e" />

Create the file Rose.txt
### COMMAND AND OUTPUT

<img width="828" height="352" alt="image" src="https://github.com/user-attachments/assets/497c38db-e4e7-447d-919d-373d3f4f5d7b" />

Create the file hello.txt using echo and redirection
### COMMAND AND OUTPUT

<img width="960" height="121" alt="image" src="https://github.com/user-attachments/assets/a9b139bc-e5a7-4a4d-87e6-d81d99a1b839" />

Copy the file hello.txt into the file hello1.txt
### COMMAND AND OUTPUT

<img width="892" height="143" alt="image" src="https://github.com/user-attachments/assets/7d526037-0e10-4b4b-b245-6e33f17055dc" />

Remove the file hello1.txt
### COMMAND AND OUTPUT

<img width="782" height="221" alt="image" src="https://github.com/user-attachments/assets/e7ad3fd9-5667-4b23-ba7b-06db9b9d7515" />

List out the file hello1.txt in the current directory
### COMMAND AND OUTPUT

<img width="757" height="1059" alt="image" src="https://github.com/user-attachments/assets/0bf6042f-ee1e-4b72-8904-bcece34da7a8" />


List out all the associated file extensions 
### COMMAND AND OUTPUT

<img width="863" height="1106" alt="image" src="https://github.com/user-attachments/assets/9fd344ed-2263-4ac5-a08d-9cebb3b4ddc8" />

Compare the file hello.txt and rose.txt
### COMMAND AND OUTPUT

<img width="826" height="188" alt="image" src="https://github.com/user-attachments/assets/5f7a8a92-38dd-4269-aabe-2a40943737ff" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

### OUTPUT

<img width="697" height="89" alt="image" src="https://github.com/user-attachments/assets/c35c2baa-8344-4386-9596-c642f72b223a" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

### OUTPUT

<img width="693" height="260" alt="image" src="https://github.com/user-attachments/assets/168230af-f404-41de-8ac9-8eb06c4fe99c" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

### OUTPUT

<img width="715" height="209" alt="image" src="https://github.com/user-attachments/assets/d844bcd7-1bb1-4567-b992-2bb41755a3e3" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

### OUTPUT

<img width="696" height="111" alt="image" src="https://github.com/user-attachments/assets/f13611e7-7a31-4fbe-adc9-77a36551ea39" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


### OUTPUT

<img width="753" height="442" alt="image" src="https://github.com/user-attachments/assets/75081a98-ad94-43d9-a1d4-906b1454e5b6" />


# RESULT:
The commands/batch files are executed successfully.
