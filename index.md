Since terminal commands differ slightly depending on your operating system, choose the set of commands below that matches your computer (Windows PowerShell or macOS/Linux Terminal). You can use these exact commands as your "record of terminal commands" for your submission.

Step-by-Step Terminal Instructions
Step 1: Open your Terminal
Windows: Press the Windows key, type PowerShell or Command Prompt, and open it.

macOS: Press Cmd + Space, type Terminal, and press Enter.

Steps 2, 3, & 4: Create Folders and Files
Copy and paste the code block below corresponding to your operating system, then press Enter:

👉 For Windows (PowerShell)
PowerShell
# 1. Create and navigate into the main project folder
mkdir web-development-practice
cd web-development-practice

# 2. Create the week folders
mkdir week-1, week-2, week-3

# 3. Create an index.html file inside each folder
New-Item -Path "week-1/index.html", "week-2/index.html", "week-3/index.html" -ItemType File
👉 For macOS / Linux (Bash or Zsh)
Bash
# 1. Create and navigate into the main project folder
mkdir web-development-practice
cd web-development-practice

# 2. Create the week folders
mkdir week-1 week-2 week-3

# 3. Create an index.html file inside each folder
touch week-1/index.html week-2/index.html week-3/index.html
Step 5: Practice Navigation, Renaming, and Deleting (Optional practice for your learning)
Try out these commands to practice your terminal skills:

Navigate into a folder: cd week-1

Go back to the parent folder: cd ..

Rename a folder:

Windows: Rename-Item week-3 week-three

Mac/Linux: mv week-3 week-three

Delete a test folder:

Windows: Remove-Item folder-name

Mac/Linux: rm -r folder-name

Step 6: Open the Project Folder in VS Code from the Terminal
Make sure you are inside your main project folder (web-development-practice), then type:

Bash
code .
(Note: If code . gives an error on Windows, you may need to open VS Code, press Ctrl+Shift+P, type "Shell Command: Install 'code' command in PATH", and try again).

📝 What to Submit
Record of Terminal Commands: Copy the block of commands you used from Step 2–4 and Step 6 into a text file or document.

Screenshot: Take a screenshot of either:

Your terminal showing the folder creation commands, OR

VS Code showing the final folder structure (web-development-practice with week-1, week-2, week-3 containing index.html files).