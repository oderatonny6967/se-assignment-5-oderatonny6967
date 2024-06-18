[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15287200&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
            Answers

      . Visit the VS Code Website (https://code.visualstudio.com/)
      . Click on the download link for 64bit  Windows. This will download an  executable installer (.exe file).
      . Open the downloaded file and follow the installation wizzard to install.
      . Once installed you can launch the VSCode on startup menu .

          prerequisites that would be required ;
            windows 11.
            Internet to download.



2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
             Answers 

         . Explore  themes to match your style (ie.dark) File > Preferences > Color Theme.
         . Adjust settings like font size .

             Important Extensions 
             python 
             inteliscence 
             vscode icons 
             git 




3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
             Answers

         Activity Bar
            . Located on the far left in the VSCode 
            . it provides access to different views like; 
                        Explorer, 
                        Search,
                        Source Control, 
                        Run and Debug
                        Extensions.

         Side Bar
            . shows the Explorer view which lists your project files and folders.

         Editor Group
             . Area where you edit your files.
             . One can open multiple files in tabs and split the editor to view files side-by-side.


         Status Bar
             . Located at the bottom,
             . It shows information about the current things such as 
                       line number, 
                       encoding, 
                       Git branch. 
             . It also provides shortcuts to important settings.




4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
            Answers
      A command pallete is a tool where we can access all commands in VScode .
      it is accessed by pressing F1 or "Shift"+">" at the search bar.
             common tasks that can be performed;
               . Add gitignore
               . Change language mode 


5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
           Answers 
           Extensions are used to Extend the functionality within the  VS Code.
          
           Find Extensions:

               Click on the Extensions icon in the Activity Bar or press Ctrl+Shift+X.
           Install Extensions:

                Search for an extension and click "Install".
            Manage Extensions:

                Click on the installed extension to see its details and settings.
                Disable or uninstall extensions as needed.
             Examples of essential extensions for web development:

                Prettier
                python 
                path intellisence 

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
            Answers 
            To open an intergrated terminal 
               Go to View > Terminal
            Advantage of using Intergrated terminal
               . Integrated with the editor.
               . Supports multiple terminal instanceslike cmd ,gitbash .




7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
           Answers
               Create Files/Folders:

                 Right-click in the Explorer view and select "New File" or "New Folder".
                 Go to file then seect new file 
               Open Files/Folders:

                 Drag and drop files/folders into the VS Code window or use File > Open Folder.
                Navigating:

                 Use the Explorer view to browse files.
                 Use Ctrl+P to quickly open files by name.



8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
           Answers 
             To Open Settings:
                Go to File > Preferences > Settings 

                To Change color Theme:
                    File > Preferences > Color Theme.
                To change the font sie
                    in settings search for ,Editor: Font Size
                To change keybindings 
                   Go to File > Preferences > Keyboard Shortcuts

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
          Answers 
          Setting up and starting debugging:

               Open the Debug View:

                  . Click on the Run and Debug icon in the Activity Bar

                Configure Debugger:

                    . click the gear icon in the Debug view.
                    . Configure your debug settings for your specific language/runtime.
                Start Debugging:

                      Set breakpoints by clicking in the gutter next to the line numbers.
                      Click the green play button or press F5 to start debugging.
                 Key Debugging Features:

                      Breakpoints.
                      watching variables.


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
        Answers

        Initialize a Repository:
          . Open terminal change the command interface to the one you can easily manouver i would prefer git bash 
         . Type command <git init >

         Making Commits:

         . Stage changes by typing command <git add .> to changed files.
         . Write a commit message and click the checkmark to commit.
              <git commit -m "message">

          Pushing Changes to GitHub:

         . Set up a remote repository on GitHub.
         . Add the remote repository: git remote add origin <repository-url>.
         . Push changes: git push -u origin master.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

