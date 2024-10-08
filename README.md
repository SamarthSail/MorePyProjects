# Automatic Folder Backup Script

This Python script automatically backs up files from a specified source directory to a destination directory daily at a user-defined time.

## Features

- Copies all contents of a source folder to a destination folder.
- Organizes backups by date, creating a new folder for each backup.
- Checks for existing backup folders to avoid overwriting.

## Prerequisites

- Python 3.x
- Required libraries: `os`, `shutil`, `datetime`, `schedule`, `time`

## Installation

1. Clone this repository or download the script.
2. Ensure you have Python installed on your machine.
3. Install the `schedule` library if it's not already installed:
   ``` pip install schedule ```

### Configuration
Before running the script, you need to configure the following variables in the code:
- source_dir: The path to the folder you want to back up.
- destination_dir: The path to the folder where backups will be stored.
- Update the time in schedule.every().day.at("INSERT TIME HERE") to the desired backup time (e.g., "14:00" for 2 PM).

### Usage

Run the script from your terminal:
``` python backup_script.py ```

 
