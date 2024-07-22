# JavaTextEditor
Technologies Used

Java Swing:

Purpose: Provides the GUI components for creating the text editor's interface.

Components:
JFrame: The main window of the text editor.
JTextArea: The component for displaying and editing text.
JMenuBar, JMenu, JMenuItem: For creating the menu bar with file operations.
JFileChooser: For file selection dialogs.
Event Handling:

Purpose: Manages user interactions such as menu item selections.
Implementation: Uses ActionListener to handle actions like opening, saving, and closing files.
File I/O:

Purpose: Handles reading from and writing to files.

Implementation: Uses FileReader and FileWriter for text file operations.
Key Features
Text Area:

Allows users to enter and edit text.
Supports basic text editing features like cut, copy, paste, and undo.

File Operations:

Open File: Opens an existing file and displays its content in the text area.
Save File: Saves the content of the text area to a file.
New File: Clears the text area for a new document.

Menu Bar:

File Menu: Includes options to open, save, and create new files.
Edit Menu: Provides options for basic text editing operations.
