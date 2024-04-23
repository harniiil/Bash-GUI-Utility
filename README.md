# Bash-GUI-Utility

Bash GUI Utility Script
This script provides a graphical user interface (GUI) for performing various system-related tasks using Zenity. It features multiple utility functions that allow users to interact with their system in a user-friendly manner.

Features
Show Date and Time: Displays the current date and time in a GUI info box.
Show Calendar: This enables users to pick a date from a calendar and optionally add notes for that date which are saved to a text file.
Delete File: Allows users to select and delete a file from a directory using GUI prompts to ensure user confirmation before deletion.
System Configuration Information: Provides a submenu that displays detailed information about the system, such as operating system type, CPU information, memory usage, hard disk utilization, and mounted file systems.
Usage
The script utilizes a main menu loop where users can select an action from the list, which includes viewing the date/time, accessing the calendar, deleting files, viewing system configuration, and exiting the application. Each option invokes the corresponding function to perform the selected task.

This utility script simplifies system management tasks through an accessible GUI, making it suitable for users who prefer graphical interfaces over command-line interactions.

Requirements for Running the Bash GUI Utility Script
System Requirements:
A Linux operating system with a graphical environment installed (e.g., GNOME, KDE).
Required Packages:
Zenity: This is crucial as it provides the graphical interface elements used by the script. Install Zenity using your package manager. For example, on Ubuntu-based systems, you can use:

sudo apt-get install zenity

Additional Dependencies:
coreutils: For basic utilities like rm, ls, etc. (usually pre-installed).
util-linux: For system-related utilities.
procps or procps-ng: For commands like free.
lscpu (included in util-linux on most distributions): For CPU architecture information.
You can install these dependencies using your package manager. On Ubuntu, you can use:

sudo apt-get install coreutils util-linux procps

Installation Instructions:
Ensure all the required packages are installed as listed above.
Download the script to your preferred directory.
Give the script execute permissions:

chmod +x [script_name].sh

Run the script from a terminal in the GUI environment:

./[script_name].sh


Replace [script_name] with the actual name of your script file. This setup will ensure users know how to prepare their environment to run your script effectively.
