# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT
<img width="371" height="51" alt="image" src="https://github.com/user-attachments/assets/a9c59495-661d-443c-9ee8-ea7988bcc4c5" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="417" height="53" alt="image" src="https://github.com/user-attachments/assets/78f2d9d0-2a73-4205-aa6d-f8c11ecc18ff" />



Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="611" height="272" alt="image" src="https://github.com/user-attachments/assets/3ad9b0ce-d067-431e-b55e-b52488d26a46" />



Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="687" height="207" alt="image" src="https://github.com/user-attachments/assets/a9194f25-b033-4b0d-b04e-db33668fae15" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="687" height="207" alt="image" src="https://github.com/user-attachments/assets/a2546494-89ad-4b81-9823-67fd19927ada" />


Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="821" height="312" alt="image" src="https://github.com/user-attachments/assets/a3f76d35-b48b-4eae-8a17-9820baa4af32" />


List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="821" height="312" alt="image" src="https://github.com/user-attachments/assets/cf353021-1f1b-45f4-83ea-3397ac681d9c" />


List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="778" height="501" alt="image" src="https://github.com/user-attachments/assets/c04faa7a-65a2-4bed-9be4-097736208e97" />



Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

<img width="705" height="247" alt="image" src="https://github.com/user-attachments/assets/a2f540cf-9159-48bc-9db2-6a57e9f46465" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="403" height="87" alt="image" src="https://github.com/user-attachments/assets/3e60df95-0260-4fff-8dfe-ca6d55225fde" />




Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="715" height="238" alt="image" src="https://github.com/user-attachments/assets/aee9ed71-ed94-4d5d-bb33-fd2be1fd09f7" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="488" height="187" alt="image" src="https://github.com/user-attachments/assets/c1c584e3-8c24-4e89-a513-b77c7c6a6154" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="615" height="127" alt="image" src="https://github.com/user-attachments/assets/91d0eabf-af65-4489-8d59-6121b838bf98" />



Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="741" height="410" alt="image" src="https://github.com/user-attachments/assets/8d4e4ed2-f1a2-4eac-bf69-2cecd370dbe4" />


# RESULT:
The commands/batch files are executed successfully.

