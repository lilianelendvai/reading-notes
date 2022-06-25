# Class 2 Reading Notes

## Text Editors

**A text editor is a piece of software that allows you to write and manage text, especially the text to build a website. This is one of the most important tools used by web developers.**

- When selecting a text editor, important features to consider include code completion, syntax highlighting, a variety of themes, and the ability to choose from a healthy selection of extensions
- Choosing a text editor is a personal choice; the "best" text editor is more of a matter of opinion vs. a widely-held belief
- Most text editors are pretty similar, so you should be able to complete the same basic functions regardless which one you choose
- And although they have most of the same basic functions, there are some variations in the features, which influences the selection of one over another
- Some developers switch between text editors as new updates and features are added - it's a constant cycle of who is pushing new and exciting features

## Linux Basics

### **What is a Command Line?**
- A command line, also known as a terminal, is a text-based interface to the system where you can enter commands
- Command lines typically present you with a prompt, and you enter commands by typing them with the keyboard
- We receive output by running the command, and most command outputs will be listed straight under issuing the command; sometimes they don't display and just perform their task unless there was an error
- The final line will be the prompt again, as after the command runs, the terminal will be ready for another command to be entered

**Shortcuts**
- When entering commands, you can traverse the command history by using the up and down errors and edit the commands by using the left and right arrow keys

### **How to move around the System**
- Many tasks rely on being able to get to (or reference) the correct location on the system; there are some basic commands to retrieve that information 
- An **absolute path** is a file or directory in relation to the root of the file sysyem
- A **relative path** is a file or directory location relative to where we currently are in the file system

**Shortcuts**
- **pwd** means Print Working Directory (where we currently are)
- **ls** lists the contents of a directory
- **cd** means Change Directories (move to another directory)
- **Tap Completion**: using the **Tab key** will invoke an autocomplete action; if nothing happens, then there are several possibilities, and hitting Tab again will show them
- a **tilde** (~) is a shortcut for the home directory
- a **dot** (.) is a reference for your current directory
- a **dotdot** (..) is a reference to the parent directory

### **Info about Files**
- With Linux, everything is actually a file: a text file is a file, a directory is a file, the monitor is a file, and even the keyboard is a file
- Under Linux, the system ignores a file's extension and looks inside the file to determine what type of file it actually is
- Linux is case sensitive, and a space on the command line is how to separate items, so be mindful of spaces in file and directory names

**Shortcuts**
- use **file** to obtain information about what type of a file a file or a directory is
- use **ls -a** to list the contents of a directory, including hidden files
