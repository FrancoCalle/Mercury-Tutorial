# Mercury Tutorial

Materials for the Tutorial on the Mercury Computing Cluster ([Repository Link](https://github.com/walterwzhang/Mercury-Tutorial))


## Install the Remote - SSH Extension in VSCode:

### Open Visual Studio Code.
Click on the Extensions view icon on the Sidebar (or press Ctrl+Shift+X).
Search for 'Remote - SSH'.
Click Install.

### Set Up an SSH Connection:
Once the extension is installed, click on the green bottom-left corner button in your status bar (it should say "Open a remote window").
Click on "Remote-SSH: Connect to Host...".
Click on "Add New SSH Host...".
Enter the SSH connection command like ssh user@hostname.
Select the SSH configuration file to update, usually it's ~/.ssh/config.
Click on "Remote-SSH: Connect to Host..." again and select the SSH host you just added.

### Opening a Folder or Workspace on the Server:
After you've connected, you can open any folder or workspace on the server by clicking on "File > Open..." (or Ctrl+K Ctrl+O).

### Select the Python Interpreter from the Virtual Environment:
Open the Command Palette by pressing F1 or Ctrl+Shift+P.
Type and select "Python: Select Interpreter".
Click on "Enter interpreter path" at the top of the list, then click "Find...".
Navigate to your virtual environment directory and select the Python interpreter located in the bin or Scripts directory (the path should look something like /path/to/your/virtualenv/bin/python on Unix/Linux/MacOS or \path\to\your\virtualenv\Scripts\python.exe on Windows).








