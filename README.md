# **Automated File Sorter**

An easy-to-use Python script that automatically keeps your directories clean and organized by sorting files into dedicated folders based on their file extensions.


_**Overview**_

If your Downloads or Documents folder is constantly cluttered with misplaced files, this script helps automate the cleanup process. It scans a specified folder, checks the file types, creates designated category folders (such as Word documents, PDFs, or PowerPoint presentations) if they don't exist, and moves each file to its corresponding directory.


_**Features**_

- **Automated Categorization**: Sorts `.docx`, `.pdf`, and `.pptx` files into organized folders automatically.
- **Dynamic Folder Creation**: Automatically creates destination folders if they haven't been created yet.
- **Zero External Dependencies**: Built entirely using Python's native standard library—no extra installation steps required.
- **Conflict Prevention**: Skips moving files if a file with the same name already exists in the target folder to prevent accidental overwrites.


_**Project Structure**_

```text
automated-file-sorter/
│
├── .gitignore                          # Prevents temporary and cache files from being tracked
├── LICENSE                             # MIT License
├── README.md                           # Project documentation
├── requirements.txt                    # Project dependency documentation
└── Automatic File Sorter.ipynb         # Main Python / Jupyter Notebook script
