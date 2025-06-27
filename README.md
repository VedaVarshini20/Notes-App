# Notes Manager

A simple command-line Java application to manage personal notes with timestamps.

## Features

. Write new notes with timestamps  
. View all saved notes  
. Search notes by keywords or timestamp  
. Delete notes by line number  
. Delete notes by timestamp

All notes are saved to a local text file called `notes.txt`.


The program offers a menu with the following options:

### 1. Write a Note

- Prompts you to enter a note.
- Attaches a current timestamp.
- Appends the note to `notes.txt`.

### 2. Read All Notes

- Reads `notes.txt`.
- Displays each note with a line number.

### 3. Search Notes by Keyword or Timestamp

- Prompts you to enter a keyword or part of a timestamp.
- Displays matching notes.

### 4. Delete a Note by Number

- Shows all notes with line numbers.
- Prompts you for the line number to delete.
- Deletes that specific line from the file.

### 5. Delete a Note by Timestamp

- Prompts you for a timestamp or partial timestamp string (e.g. `2025-06-27`).
- Deletes all notes that contain the provided timestamp substring.

### 6. Exit

- Closes the application.
- 
## File Used

- **notes.txt**  
  Stores all your notes. Each note is on a separate line.

## How to Run

1. Save the Java code into a file called `NotesManager.java`.

2. Open a terminal or command prompt.

3. Compile the program:

```bash
javac NotesManager.java

<img width="248" alt="notes app" src="https://github.com/user-attachments/assets/03ff423e-1e7d-434f-8c55-7c449849533a" />


