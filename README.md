# AirBnB_clone
Project done in teams of 2 people ( Mary Mengistu, Saad Belmajdoub)

## Introduction:

* Team project to build a clone of AirBnB.

* The console is a command interpreter to manage objects abstraction between objects and how they are stored.

### The console will perform the following tasks:

* create a new object.
* retrive an object from a file.
* do operations on objects.
* destroy an object.

## Storage:

All the classes are handled by the `Storage` engine in the `FileStorage` Class.

## Environment:

https://camo.githubusercontent.com/a4f0621f517fa66e8974e2f30834df4f35f8a5a2a8e6332c9e710e5fccb19186/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d266d6573736167653d47697426636f6c6f723d463035303332266c6f676f3d476974266c6f676f436f6c6f723d463035303332266c6162656c436f6c6f723d324633333341 https://camo.githubusercontent.com/36cfab6b091d0d3436f28ed011f2adedb6e64cde49a1d585f4cb6830a7ace02e/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d266d6573736167653d56696d26636f6c6f723d303139373333266c6f676f3d56696d266c6f676f436f6c6f723d303139373333266c6162656c436f6c6f723d324633333341 https://camo.githubusercontent.com/81bd4f4b4344056caf1786c0089fd0618bac0bb77ad5e373bdd257d011ea3fa5/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d266d6573736167653d5562756e747526636f6c6f723d453935343230266c6f676f3d5562756e7475266c6f676f436f6c6f723d453935343230266c6162656c436f6c6f723d324633333341 https://camo.githubusercontent.com/499b3175256e1af61c73b1d5cd2399b33f7c26d15e85cf36980772b4ab1b2929/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d266d6573736167653d507974686f6e26636f6c6f723d464644343342266c6f676f3d707974686f6e266c6f676f436f6c6f723d333737364142266c6162656c436f6c6f723d324633333341

* Style guidelines:
     
     https://pypi.org/project/pycodestyle/

All the development and testing was runned over an operating system Ubuntu 20.04 LTS using programming language Python 3.8.3

## Installation

``` 
 git clone https://github.com/ma09ry90/AirBnB_clone.git

```

### change to the AirBnb directory and run the command: 

```
./console.py
```
## Execution:

  interactive mode:

```
  $ ./console.py
(hbnb) help

Documented commands (type help <topic>):

EOF  help  quit

(hbnb)
(hbnb)
(hbnb) quit
$
```

non-interactive mode: (like the Shell project in C):

```
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):

EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):

EOF  help  quit
(hbnb) 
$
```

## Testing

All the test are defined in the `tests` folder.

## Documentation:

 * Modules:

```
$ python3 -c 'print(__import__("my_module").__doc__)'
```

 * classes:
```
python3 -c 'print(__import__("my_module").MyClass.__doc__)'
```
 * Functions (inside and outside a class):
```
$ python3 -c 'print(__import__("my_module").my_function.__doc__)'
```
 and
```
$ python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'
```
### Python Unit Tests

* unittest module
* File extension `.py`
* Files and folders star with `test_`
* Organization:for `models/base.py`, unit tests in: `tests/test_models/test_base.py`
* Execution command: `python3 -m unittest discover tests`
* or:` python3 -m unittest tests/test_models/test_base.py`

### run test in non-interactive mode

To run the tests in non-interactive mode, and discover all the test, you can use the command:
```
 $ echo "python3 -m unittest discover tests" | bash
```
 ![image](https://github.com/ma09ry90/AirBnB_clone/assets/118520635/dc753dde-074d-4d0e-8fb9-59661ef8a53f)

## Usage:

 * Start the console in interactive mode:
 ```
$ ./console.py
(hbnb)
```
* Use help to see the available commands:
``` 
(hbnb) help

Documented commands (type help <topic>):

EOF  all  count  create  destroy  help  quit  show  update

(hbnb)
```
* Quit the console:
```
(hbnb) quit
$
```
## Authors

  1. Mary Mengistu 
  2. Saad Belmajdoub
