# Topic Notes


## What is a Text Editor?

The formal definition is: “A text editor is a type of program used for editing plain text files.A text editor is a piece of software that you download and install on
your computer, or you access online through your web browser, that
allows you to write and manage text, especially the text that you write
to build a web site. 

## What features should you look for in a text editor?
* **syntax highlighting**
  * determines the color and style of source code displayed in the Visual Studio Code editor.
  * allows code in posts to be highlighted based on the language it's written in, to make it easier to read
* **code completion**
  * A great feature of any text editing software is code completion. 
  * feature in some programming environments that speeds up the process of coding applications by reducing typos and other common mistakes.
* **a nice variety of themes**
  *  themes will allow you to change the color of the background of your text editor, the series of colors in your text, and sometimes themes will affect other   aspects of your text editing
software as well
  * reduce eye strain and fatigue
* **Extentsion**
  * provide some plugin mechanism, or is scriptable, so a programmer can customize the editor with additional features – this is more advanced
  
  
  ### Comparison of “Basic text editor" vs coding-specific text editor vs IDE.
  
  - A **Basic Text Editor** kind of gives away what it does in the title— *it edits text*. It also manages text, and manages files.
  - A **code specific Text Editor** is specifically meant to edit code.A text editor is a piece of software that you download and install on
your computer, or you access online through your web browser, that
allows you to write and manage text, especially the text that you write
to build a web site. 
  - An **IDE (Integrated Development Environment)** is really a suite ofdifferent software all coming together. An IDE is a text editor, a filemanager, a compiler, and a debugger all in one software package.
 
 
 # Introduction to using a terminal
 
 ### What is a terminal?
 A Terminal is your interface to the underlying operating system via a shell, usually **bash**. It is a command line. Back in the day, a Terminal was a screen+keyboard that was connected to a server. Today, it is usally just a progam.
 A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.The command line typically presents you with a prompt. As you type, it will be displayed after the prompt. Most of the time you will be issuing commands.
 
 Within a terminal you have what is known as a **shell**.This is a part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you. There are various shells available but the most common one is called bash which stands for Bourne again shell. 
 
 If you would like to know which shell you are using you may use a command called echo to display a system variable stating your current shell. echo is a command which is used to display messages.

## how to navigate in terminal
Directory basically means a folder.
here are some basic commands prompts and how to use them.
 * _**cd**_ stands **(Change Directory)**. this command enables you to change directory.
 * _**pwd**_ stands for **(Print Working Directory)**. It will print the full path to the current working directory.
 * The _**mkdir**_ command stands for **(Make Directory)**.
 * Using the **touch** command, we can create a file.
 * The _**ls**_ command stands for **(List)**. We can use it to list all the contents of the specified directory, if no path is specified it will list everything in the current directory.
 * _**clear**_ is used to clear the entire code. 
 * The _**mv**_ command stands for **(Move)**. We can use this command to move files and directories from one place to another.
 * The _**cp**_ command stands for **(Copy)**. its used to copy files from one place to another.

## More about Files

On Linux, the file system is case sensitive. This means that you could have files named file, File, and FILE in the same folder. Each file would have different contents – Linux treats capitalized letters and lower-case letters as different characters.
the file command determines the file type of a file. It reports the file type in human readable format.

### Example of file extentsions

 * file.exe - an executable file, or program.
 * file.txt - a plain text file.
 * file.png, file.gif, file.jpg - an image

Everything is a file under Linux even directories.
Linux is an extension-less system. Files can have any extension they like or none at all. Linux is case sensitive

* **file**
   * obtain information about what type of file a file or directory is.
  
* **ls -a**
   * List the contents of a directory, including hidden files.


#### Spaces in names

Spaces in file and directory names are perfectly valid but we need to be a little careful with them. As you would remember, a space on the command line is how we seperate items.

#### Escape Characters

Another method is to use what is called an **escape character**, which is a backslash ( \ ). What the backslash does is escape (or nullify) the special meaning of the next character.


