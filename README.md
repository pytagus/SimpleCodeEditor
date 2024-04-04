# SimpleCodeEditor
A lightweight, Python-based text editor tailored for coding and script execution. Developed using Tkinter, this editor integrates basic functionalities such as opening, editing, saving files, and version management, alongside syntax highlighting for Python, CSS, and JavaScript. Moreover, it features the unique capability to directly execute Python scripts within the editor, ensuring a streamlined workflow for Python developers.

## Features
File Operations: Open, edit, and seamlessly save text files. The editor supports a variety of file types, ensuring a broad compatibility for your coding needs.

Syntax Highlighting: Offers basic syntax highlighting for Python, CSS, and JavaScript. This feature enhances code readability and efficiency, making it easier to work on your projects.

Script Execution: Directly execute Python scripts from within the editor. This functionality includes the flexibility to specify or change the Python interpreter path, accommodating different Python environments or versions.

Version Management: Easily save timestamped versions of your work. This allows you to track changes over time or revert to earlier versions, providing a simple version control mechanism.

Customizable Python Path: Update the path to the Python interpreter according to your development environment. This ensures compatibility and flexibility, allowing you to switch between different Python installations as needed.

Text Manipulation: Quickly indent or dedent selected text with dedicated buttons. This feature facilitates code formatting and improves readability, making it simpler to organize your code.

Save As Functionality: Save your current document under a new name or location with the "Save As" button. This feature is essential for managing multiple versions of a document or for initializing new projects based on existing work.

Search Functionality: Search for specific text within your document using the search field and button. Each search highlights matches in orange, allowing for easy navigation through occurrences.

![SimpleCodeEditorPicture](SimpleCodeEditor.png)

## How to Use
Upon launching the Simple Code Editor, you'll find a straightforward interface with a menu bar and a toolbar at the top, alongside a spacious area for code editing.

Opening Files: Click the "Open" button or choose "Open" from the "File" menu to open existing files for editing.

Saving Files: Use the "Save" button for quick saves of the current document. If the file hasn't been saved before, it will prompt you for a location to save the file, similar to "Save As".

Saving Files As: To save the current document under a new name or location, use the "Save As" button. This is useful for creating a copy of the current document or saving it for the first time.

Creating Versioned Copies: To create a timestamped version of the current file, use the "Version" button. This feature is handy for keeping track of different versions of your document without manually renaming them.

Executing Python Scripts: Press the "Run" button to execute the currently open Python script. If it's the first time running a script, or if the Python interpreter path needs to be specified or changed, you'll be prompted to do so.

Changing the Python Interpreter Path: If you need to change the Python interpreter used for executing scripts, click the "Python" button to specify a new path. This feature allows flexibility in using different Python environments or versions.

Searching within the Document: Enter the text you wish to search for in the search field, and press the "Search" button to find the next occurrence of the text. The search starts from the beginning of the document or continues from the current cursor position, highlighting matches in orange for easy visibility.
The editor allows for basic syntax highlighting customization through the highlight_patterns method. Modify patterns here to adjust syntax highlighting to fit your needs.

## Compiling
The Simple Code Editor is not only user-friendly but also developer-friendly. Compiling it into a standalone executable is straightforward with PyInstaller, making distribution and deployment effortless. Simply run pyinstaller --onefile codeeditor.py from your terminal, and PyInstaller will generate a single executable file for your platform. This process encapsulates all the necessary dependencies, allowing the editor to be used on any compatible system without requiring Python to be installed. Additionally, for those who prefer working directly with the script, running the editor is as simple as executing python codeeditor.py in your command line. This flexibility ensures that whether you're looking to share your tool with others or just need a quick and lightweight code editor for personal use, the Simple Code Editor meets your needs with ease.

## License
This project is open-sourced under the MIT License. See the LICENSE file for more details.

## Contributions
Contributions are welcome! If you'd like to improve the Simple Code Editor, feel free to fork the repository and submit a pull request.
