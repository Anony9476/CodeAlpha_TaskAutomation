# CodeAlpha Internship Program
## Python Programming
# Task Automation Script

## Overview
This Python script automates file organization by sorting files in a specified directory based on their extensions. It creates folders for each file type and moves the corresponding files into them.

## Features
- Scans a specified directory for files
- Automatically creates folders based on file extensions
- Moves files into corresponding folders
- Simple and lightweight script with minimal dependencies

## How It Works
1. The script prompts the user to enter a directory path.
2. It scans all files in the specified directory.
3. It creates separate folders for different file types (extensions).
4. It moves files into their respective folders.

## Installation & Usage
### Prerequisites
Ensure you have Python installed (version 3.x recommended).

### Steps to Run the Script:
1. Clone the repository or download the script:
   ```sh
   git clone https://github.com/yourusername/task-automation.git
   cd task-automation
   ```
2. Run the script:
   ```sh
   python Task_04_TaskAutomation.py
   ```
3. Enter the directory path when prompted.

## Example
**Before Running the Script:**
```
📁 Documents
   ├── file1.pdf
   ├── file2.docx
   ├── image1.jpg
   ├── script.py
```
**After Running the Script:**
```
📁 Documents
   ├── 📁 pdf
   │   ├── file1.pdf
   ├── 📁 docx
   │   ├── file2.docx
   ├── 📁 jpg
   │   ├── image1.jpg
   ├── 📁 py
   │   ├── script.py
```

## Dependencies
This script uses Python's built-in libraries:
- `os` (for directory and file handling)
- `shutil` (for moving files)

## Future Improvements
- Add error handling for invalid paths
- Implement a GUI for easier directory selection
- Allow users to customize file sorting rules

## License
This project is open-source and available under the MIT License.

## Contribution
Feel free to fork the repository and submit pull requests to improve the script!

## Author
Abdul Haseeb - Python Developer


