# AirBnB_clone
Project done in teams of 2 people ( Mary Mengistu, Saad Belmajdoub)
 Introduction
Team project to build a clone of AirBnB.

The console is a command interpreter to manage objects abstraction between objects and how they are stored.

The console will perform the following tasks:

create a new object
retrive an object from a file
do operations on objects
destroy an object
Storage
All the classes are handled by the Storage engine in the FileStorage Class
0x02 Environment
Suite CRM python Suite CRM Suite CRM git distributed version control system Github
Style guidelines:
.pycodestyle (version 2.7.*)
All the development and testing was runned over an operating system Ubuntu 20.04 LTS using programming language Python 3.8.3
 Installation
 git clone https://github.com/ma09ry90/AirBnB_clone.git
 change to the AirBnb directory and run the command:
  ./console.py
  Execution
   interactive mode:
   $ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$
non-interactive mode: (like the Shell project in C)
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
Testing
All the test are defined in the tests folder.

Documentation
 Modules:
python3 -c 'print(__import__("my_module").__doc__)'
 classes:
python3 -c 'print(__import__("my_module").MyClass.__doc__)'
 Functions (inside and outside a class):
python3 -c 'print(__import__("my_module").my_function.__doc__)'
 and
python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'
Python Unit Tests
unittest module
File extension .py
Files and folders star with test_
Organization:for models/base.py, unit tests in: tests/test_models/test_base.py
Execution command: python3 -m unittest discover tests
or: python3 -m unittest tests/test_models/test_base.py
run test in non-interactive mode
To run the tests in non-interactive mode, and discover all the test, you can use the command:
 $ echo "python3 -m unittest discover tests" | bash
 ![image](https://github.com/ma09ry90/AirBnB_clone/assets/118520635/33f9e636-300c-42f5-a3d1-c9fc68536f9f)

 Usage
 Start the console in interactive mode:
 $ ./console.py
(hbnb)
Use help to see the available commands:
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  all  count  create  destroy  help  quit  show  update

(hbnb)
Quit the console:
(hbnb) quit
$
Authors
  Mary Mengistu 
  Saad Belmajdoub
