Save Windows SSH Backup by @Echo
Welcome to Save Windows SSH Backup! This script helps you create backups from your Windows machine and securely transfer them to a remote server using SSH.

What is it?
Save Windows SSH Backup is a Python script that allows you to create compressed backups of specific files or directories on your Windows system and then securely transfer them to a remote server using the SSH protocol.

How to Use
Run the Script: Simply run the script in your Python environment.

Provide Source and Destination Directories: Enter the directory path of the files you want to back up and the destination directory where you want to store the backups.

Enter SSH Connection Details: Input the necessary SSH connection details, including server port, server IP, username, and password.

Sit Back and Relax: The script will handle the rest, creating a compressed archive of your files and securely transferring them to the remote server.

Requirements
To use this script, you'll need:

Python 3.x
Paramiko library
Colorama library
Make sure you have these dependencies installed before running the script.

Usage Example
Copy code
python save_windows_ssh_backup.py
Important Note
Please ensure that the required dependencies (paramiko and colorama) are installed in your Python environment before running the script.
