# Automatic-File-Sorter
Automatic file sorter for File Explorer using Python. This allows for the the automatic sorting of designated files without having to drag and drop files into folders.

✨ Features
Automatically sorts files based on their extension
Supports:
- .jpg → Images
- .txt → Text Files
- .csv → CSV Data Files

Reduces manual organization in File Explorer
Easy to customize for additional file types
Works on Windows, macOS, or Linux (with correct file paths)

🚀 How It Works
You specify a source folder (e.g., Downloads).
The script scans every file inside that folder.
Based on the file extension:
- JPG files move to the Images/ folder
- TXT files move to the Text/ folder
- CSV files move to the CSV/ folder

If the destination folders don’t exist, the script creates them automatically.
