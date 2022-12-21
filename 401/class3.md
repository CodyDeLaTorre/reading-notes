# Class 3 Reading Notes

## FileIO & Exceptions

### Reading and Writing Files in Python

One of the most common tasks that you can do with Python is reading and writing files.
When you want to work with a file, the first thing to do is to open it. This is done by invoking the open() built-in function. open() has a single required argument that is the path to the file.

- 'r' Open for reading (default)
- 'w' Open for writing, truncating (overwriting) the file first
- 'rb' or 'wb' Open in binary mode (read/write using byte data)

Read Methods

- .read(size=-1) This reads from the file based on the number of size bytes. If no argument is passed or None or -1 is passed, then the entire file is read.
- .readline(size=-1) This reads at most size number of characters from the line. This continues to the end of the line and then wraps back around. If no argument is passed or None or -1 is passed, then the entire line (or rest of the line) is read.
- .readlines() This reads the remaining lines from the file object and returns them as a list.

Write Methods

- .write(string) This writes the string to the file.
- .writelines(seq) This writes the sequence to the file. No line endings are appended to each sequence item. It’s up to you to add the appropriate line ending(s).

### Python Exceptions

Exception error - This type of error occurs whenever syntactically correct Python code results in an error. The last line of the message indicated what type of exception error you ran into.Instead of showing the message exception error, Python details what type of exception error was encountered.

- raise allows you to throw an exception at any time.
- assert enables you to verify if a certain condition is met and throw an exception if it isn’t.
- In the try clause, all statements are executed until an exception is encountered.
- except is used to catch and handle the exception(s) that are encountered in the try clause.
- else lets you code sections that should run only when no exceptions are encountered in the try clause.
- finally enables you to execute sections of code that should always run, with or without any previously encountered exceptions.

---

### Resources

[Read/Write Files in Python](https://realpython.com/read-write-files-python/)

[Python Exceptions](https://realpython.com/python-exceptions/)

---

[Back to Home](../README.md)
