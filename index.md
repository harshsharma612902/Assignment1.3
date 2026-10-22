1. Terminal Commands LogBelow is the complete sequence of terminal commands used to construct the project structure, perform basic file/folder management, and open the workspace in VS Code.Step 1: Create Main Project Directory & Navigate# Create the root project folder
mkdir web-development-practice

# Navigate into the project directory
cd web-development-practice
Step 2: Create Subdirectories# Create weekly folders in a single command (or individually)
mkdir week-1 week-2 week-3
Step 3: Create index.html Inside Each Subdirectory# macOS/Linux/Git Bash
touch week-1/index.html week-2/index.html week-3/index.html

# Windows Command Prompt (Alternative)
# type nul > week-1\index.html
# type nul > week-2\index.html
# type nul > week-3\index.html
Step 4: Practice Navigation, Renaming & Deletion# Practice navigating into a folder
cd week-1
pwd      # Print working directory (or 'cd' on Windows CMD)

# Return to parent directory
cd ..

# Practice renaming a folder (e.g., test rename and change back)
mv week-3 week-03
mv week-03 week-3

# Practice creating and deleting a temporary directory/file
mkdir temp-folder
rmdir temp-folder  # or 'rm -r temp-folder'
Step 5: Launch VS Code from Terminal# Open the current directory in VS Code
code .
2. Terminal Commands Cheat SheetActionmacOS / Linux / Git BashWindows CMDWindows PowerShellMake Directorymkdir folder_namemkdir folder_namemkdir folder_nameChange Directorycd folder_namecd folder_namecd folder_nameGo Back One Levelcd ..cd ..cd ..Create Filetouch file.txttype nul > file.txtNew-Item file.txtList Directory Contentsls or ls -ldirls or dirRename File/Foldermv old_name new_nameren old_name new_nameRename-Item old_name new_nameDelete Folderrm -r folder_namermdir /s folder_nameRemove-Item -Recurse folder_nameOpen in VS Codecode .code .code .3. Final Directory Tree Structureweb-development-practice/
├── week-1/
│   └── index.html
├── week-2/
│   └── index.html
└── week-3/
    └── index.html
4. Required Screenshot Instructions for SubmissionTo complete your submission, attach the following screenshot(s):Terminal Log Screenshot:Open your terminal window showing the executed commands (mkdir, cd, touch, and code .).VS Code Folder Structure Screenshot:Capture VS Code with the Explorer sidebar open, displaying web-development-practice expanded to reveal week-1, week-2, and week-3, each containing an index.html file.