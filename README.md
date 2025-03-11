# Backup System

This backup management program allows the user to create, delete, list, and search for specific files in backups. It provides a simple command-line interface.

## Requirements

- Bash
- unzip (for the "Search for specific file in backup" feature)

## Instructions

1. Run the script in your Bash environment.
2. The script will guide you through a menu with various options for managing backups.
3. Select one of the available options by entering the corresponding number.
4. Follow the instructions for each option.

## Features

1. **Create Backup**: Creates a backup of a specified directory.
2. **Delete Backup**: Deletes an existing backup from the backup directory.
3. **List Backups**: Lists all existing backups in the backup directory.
4. **Search for Specific File in Backup**: Searches for a specific file in existing backups and shows in which backup it was found.
5. **Show Help**: Displays help with an overview of the available options.
6. **Exit Program**: Exits the backup management program.

## Notes

- The backup directory is created in the user's home directory by default if it doesn't already exist.
- When a file is found in a backup, only the backup in which it was found will be shown. No files will be extracted.
