
# GUI Utilities Bash Script

This Bash script provides a simple command-line interface (CLI) with a graphical user interface (GUI) built using the `zenity` command. It offers various functionalities such as displaying the current date and time, showing a calendar, deleting files, and displaying system configuration information.

## Features

1. **Show Date and Time**: Displays the current date and time in a GUI info box.
2. **Show Calendar**: Allows the user to select a date from a GUI calendar. The selected date can be associated with additional information, which is saved in a file named `calendar_notes.txt`.
3. **Delete File**: Prompts the user to select a directory and then choose a file from that directory to delete. Confirmation is required before deleting the selected file.
4. **System Configuration Information**: Displays a submenu with options to view various system configuration details, including operating system type, CPU information, memory information, hard disk information, and mounted file systems.

## Prerequisites

To run this script, you need to have the following installed on your system:

- Bash shell
- `zenity` command (usually included in most Linux distributions)

## Usage

1. Save the script to a file, e.g., `gui_utilities.sh`.
2. Make the script executable: `chmod +x gui_utilities.sh`
3. Run the script: `./gui_utilities.sh`
4. A graphical menu will appear, allowing you to select the desired action.

## File Structure

- `show_datetime()`: Function to display the current date and time in a GUI info box.
- `show_calendar()`: Function to display a GUI calendar and allow the user to select a date. Selected date and associated information are saved in `calendar_notes.txt`.
- `delete_file()`: Function to prompt the user to select a directory and file, and then delete the selected file after confirmation.
- `system_config_info_submenu()`: Function to display a submenu with options to view system configuration information.
- `Main menu`: Loop that displays the main menu and executes the corresponding function based on the user's choice.

## Notes

- The script uses the `zenity` command to create GUI dialogs and prompts.
- The `calendar_notes.txt` file is created in the current working directory to store the selected dates and associated information from the "Show Calendar" option.
- User confirmation is required before deleting a file.

## Contributing

Contributions to improve or extend the functionality of this script are welcome. If you find any issues or have suggestions for enhancement, please open an issue or submit a pull request.
