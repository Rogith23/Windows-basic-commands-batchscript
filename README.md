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

<img width="953" height="76" alt="Screenshot 2025-11-24 085128" src="https://github.com/user-attachments/assets/0084cab5-b876-4b84-b0a2-5d63bb40c4d1" />


Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="952" height="62" alt="Screenshot 2025-11-24 085257" src="https://github.com/user-attachments/assets/41448afa-887c-4be7-b00e-c0895a725f8d" />



Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="944" height="382" alt="Screenshot 2025-11-24 085549" src="https://github.com/user-attachments/assets/abf2f46c-2644-448f-848d-4c95e02332b3" />



Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="952" height="111" alt="Screenshot 2025-11-24 085634" src="https://github.com/user-attachments/assets/2c5b0ec0-84c7-4fe3-88b3-d54079733c83" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="933" height="119" alt="Screenshot 2025-11-24 085732" src="https://github.com/user-attachments/assets/7f88a9f4-d4c4-43e0-8ef8-a8cf2bf2a2fe" />


Remove the file hello1.txt

## COMMAND AND OUTPUT

<img width="941" height="46" alt="Screenshot 2025-11-24 085803" src="https://github.com/user-attachments/assets/b0b2e991-b581-43e1-add6-ea2153ca7472" />


List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="931" height="230" alt="Screenshot 2025-11-24 085840" src="https://github.com/user-attachments/assets/ab66ba2e-0a14-4801-9781-32458e5f3245" />


List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="928" height="910" alt="Screenshot 2025-11-24 085919" src="https://github.com/user-attachments/assets/1454190f-6e42-49a9-8b42-d2b175ae3eaa" />



Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

<img width="935" height="222" alt="Screenshot 2025-11-24 090125" src="https://github.com/user-attachments/assets/5a7909d7-88a9-4f9f-936e-16fddbb305b7" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="954" height="106" alt="Screenshot 2025-11-24 091020" src="https://github.com/user-attachments/assets/6413d71d-1973-49ad-8f4f-be2f508fa977" />




Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="837" height="191" alt="Screenshot 2025-11-24 092039" src="https://github.com/user-attachments/assets/51d5754f-ea04-46f5-8ad4-eb1791e50729" />





Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="441" height="142" alt="Screenshot 2025-11-24 092249" src="https://github.com/user-attachments/assets/ec8fa1af-d0d6-46a4-ba11-9eac0d028bf6" />





Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="373" height="54" alt="Screenshot 2025-11-24 092259" src="https://github.com/user-attachments/assets/39f184c4-4ff8-4fb1-9241-46c9ff05fc46" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="513" height="383" alt="Screenshot 2025-11-24 092737" src="https://github.com/user-attachments/assets/11c6a249-7fdc-4b58-a1c2-5143812fede1" />




# RESULT:
The commands/batch files are executed successfully.

