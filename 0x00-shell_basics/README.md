0
import os

cwd = os.getcwd()
print("Current working directory:", cwd)
this script will display the absolute path name of the current working directory.


1
import os

files = os.listdir()
for file in files:
    print(file)
This script will display the list of files and directories in current directory.

2
import os

home_dir = os.path.expanduser("~")
os.chdir(home_dir)
print("Changed working directory to:", home_dir)
will change the working directory to the user's home directory and display the new working directory

3

