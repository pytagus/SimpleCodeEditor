# SimpleCodeEditor
A lightweight, Python-based text editor tailored for coding and script execution. Developed using Tkinter, this editor integrates basic functionalities such as opening, editing, saving files, and version management, alongside syntax highlighting for Python, CSS, and JavaScript. Moreover, it features the unique capability to directly execute Python scripts within the editor, ensuring a streamlined workflow for Python developers.


markdown
Copy code
# Simple Code Editor

A simple code editor implemented in Python using Tkinter.

## Features

- **New**: Create a new file.
- **Open**: Open an existing file.
- **Save**: Save the current file.
- **Save As**: Save the current file with a new name/location.
- **Version**: Save a version of the current file with timestamp.
- **Move Left**: Move the selected text left by one indentation level.
- **Move Right**: Move the selected text right by one indentation level.
- **Run**: Execute the Python script.
- **Stop**: Stop the execution of the running script.
- **Python**: Change the Python interpreter path.
- **Search**: Search for text in the code.

![SimpleCodeEditorPicture](SimpleCodeEditor.png)

## Usage

1. **New**: Click on the "+" button to create a new file.
2. **Open**: Click on the "Open" button to open an existing file.
3. **Save**: Click on the "Save" button to save the current file.
4. **Save As**: Click on the "Save As" button to save the current file with a new name/location.
5. **Version**: Click on the "Version" button to save a version of the current file with timestamp.
6. **Move Left**: Select text and click on the "<-" button to move it left by one indentation level.
7. **Move Right**: Select text and click on the "->" button to move it right by one indentation level.
8. **Run**: Click on the "Run" button to execute the Python script.
9. **Stop**: Click on the "Stop" button to stop the execution of the running script.
10. **Python**: Click on the "Python" button to change the Python interpreter path.
11. **Search**: Enter text in the search box and click on the "Search" button to find text in the code.

## Requirements

- Python 3.x
- Tkinter
- Tkinterdnd2

## Compiling
The Simple Code Editor is not only user-friendly but also developer-friendly. Compiling it into a standalone executable is straightforward with PyInstaller, making distribution and deployment effortless. Simply run pyinstaller --onefile codeeditor.py from your terminal, and PyInstaller will generate a single executable file for your platform. This process encapsulates all the necessary dependencies, allowing the editor to be used on any compatible system without requiring Python to be installed. Additionally, for those who prefer working directly with the script, running the editor is as simple as executing python codeeditor.py in your command line. This flexibility ensures that whether you're looking to share your tool with others or just need a quick and lightweight code editor for personal use, the Simple Code Editor meets your needs with ease.

## License
This project is open-sourced under the MIT License. See the LICENSE file for more details.

## Contributions
Contributions are welcome! If you'd like to improve the Simple Code Editor, feel free to fork the repository and submit a pull request.
