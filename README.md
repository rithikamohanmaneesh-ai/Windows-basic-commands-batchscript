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
<img width="378" height="41" alt="image" src="https://github.com/user-attachments/assets/4fafb503-61a8-45d8-8846-b62585c1c6b9" />
Remove the directory "my-folder"


## COMMAND AND OUTPUT
<img width="399" height="34" alt="image" src="https://github.com/user-attachments/assets/c29bd637-e2ff-4e39-9e53-504a0155ce6b" />

Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="704" height="386" alt="image" src="https://github.com/user-attachments/assets/39275937-db85-489e-add3-af315b9b3c17" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="504" height="171" alt="image" src="https://github.com/user-attachments/assets/184e2608-ad4e-443a-b03b-50dcd5822352" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="594" height="121" alt="image" src="https://github.com/user-attachments/assets/8d783a18-7dcb-46a6-9417-08eedd0ae89d" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="450" height="156" alt="image" src="https://github.com/user-attachments/assets/e2335f9f-67b1-47e4-9b50-97d0dd6057d8" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="450" height="156" alt="image" src="https://github.com/user-attachments/assets/dc13ba64-7537-4e27-9562-6dce1556856f" />

List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="578" height="342" alt="image" src="https://github.com/user-attachments/assets/645cd300-ccc8-4f28-8cee-285aac3c4799" />

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="581" height="221" alt="image" src="https://github.com/user-attachments/assets/f445f2a5-f366-4a4e-b635-523bce6b5d93" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="465" height="239" alt="image" src="https://github.com/user-attachments/assets/642e5bbc-59fd-4f7a-94f9-49b833cf5c37" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="817" height="376" alt="image" src="https://github.com/user-attachments/assets/d80de3d7-4d15-494f-aba2-fede592660fb" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="449" height="220" alt="image" src="https://github.com/user-attachments/assets/b973a5d1-320b-4da1-9bf0-ce342e1206fb" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="666" height="234" alt="image" src="https://github.com/user-attachments/assets/2869a348-499a-40d0-85e5-ac0a1745e7a8" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="764" height="449" alt="image" src="https://github.com/user-attachments/assets/b6c3081c-053d-487f-af1a-c24874e49a3e" />



# RESULT:
The commands/batch files are executed successfully.

