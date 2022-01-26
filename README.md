## AirBnB_clone

![This is an image](https://camo.githubusercontent.com/a8cd2eef2325c425519095dc2501111e630a77eddb454938c527cb82ea9c3aeb/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f696e7472616e65742d70726f6a656374732d66696c65732f686f6c626572746f6e7363686f6f6c2d6869676865722d6c6576656c5f70726f6772616d6d696e672b2f3236332f4842544e2d68626e622d46696e616c2e706e67)

## Description :desktop_computer:
HolbertonBnB is a complete web application, integrating database storage, a back-end API, and front-end 
interfacing in a clone of AirBnB. The project currently only implements the back-end console. 
Each tasks are linked and will help you to: 
- put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances 
- create a simple flow of serialization/deserialization: ```Instance <-> Dictionary <-> JSON string <-> file ``` 
- create all classes used for AirBnB (User, State, City, Place...) that inherit from BaseModel 
- create the first abstracted storage engine of the project: File storage. 
- create all unittests to validate all our classes and storage engine
#### Environment
Ubuntu 14.04 LTS
#### Python version
Python 3.4.3
#### Style
PEP 8 (v.1.7)
### Project Requirements
#### Requirements for Python scripts
- Allowed editors: `vi`, `vim`, `emacs` 
- All your files will be interpreted/compiled on Ubuntu 14.04 LTS using `python3` (version 3.4.3) 
- All your files should end with a new line 
- The first line of all your files should be exactly `#!/usr/bin/python3` 
- A `README.md` file, at the root of the folder of the project, is mandatory 
- Your code should use the `PEP 8` style 
- All your files must be executable 
- The length of your files will be tested using `wc` 
- All your modules should have a documentation (`python3 -c 'print(__import__("my_module").__doc__)'`) 
- All your classes should have a documentation (`python3 -c'print(__import__("my_module").MyClass.__doc__)'`) 
- All your functions (inside and outside a class) should have a documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'` and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`)
#### Requirements for Python unit tests
For this project, you will create unit tests, not doctest: 
- Allowed editors: `vi`, `vim`, `emacs` 
- All your files should end with a new line 
- All your test files should be inside a folder `tests` 
- You have to use the [unittest module](https://docs.python.org/3.4/library/unittest.html#module-unittest) 
- All your test files should be python files (extension: `.py`) 
- All your test files and folders should start by `test_` 
- Your file organization in the tests folder should be the same as your project: ex: for `models/base_model.py`, unit tests must be in: `tests/test_models/test_base_model.py` - All your tests should be executed by using this command: 
`python3 -m unittest discover tests` 
- You can also test file by file by using this command: `python3 -m unittest tests/test_models/test_base_model.py` 
- All your modules should have a documentation (`python3 -c 'print(__import__("my_module").__doc__)'`) 
- All your classes should have a documentation (`python3 -c 'print(__import__("my_module").MyClass.__doc__)'`) 
- All your functions (inside and outside a class) should have a documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'` and `python3 -c 
'print(__import__("my_module").MyClass.my_function.__doc__)'`) 
- We strongly encourage you to work together on test cases, so that you don't miss any edge case
### What students should learn from this project
- At the end of this project students are expected to be able to explain to anyone, without the help of Google: 
- How to create a Python package 
- How to create a command interpreter in Python using the cmd module 
- What is Unit testing and how to implement it in a large project 
- How to serialize and deserialize a Class 
- How to write and read a JSON file 
- How to manage datetime 
- What is an UUID 
- What is *args and how to use it 
- What is **kwargs and how to use it 
- How to handle named arguments in a function
## Project Breakdown

## Getting Started

### Installation
To use this project:
1. Clone

```
https://github.com/sentayehut/AirBnB_clone

``` 
2. On your machine, navigate (`cd`) to the newly created directory 

``` 
cd AirBnb_clone

```
### Console
The console is a command line interpreter that permits management of the backend of HolbertonBnB. 
It can be used to handle and manipulate all classes utilized by the application (achieved by calls on the `storage` object defined above).
This console works in interactive mode: 
```shell $ ./console.py 
         (hbnb) help 

         Documented commands (type help <topic>): 
   
         ======================================== 

         EOF help quit 

         (hbnb) 
         (hbnb) 
         (hbnb) quit 
         $ 
``` 
This console also works in non-interactive mode: 
```shell $ ./console.py 
         (hbnb) help 
        
         Documented commands (type help <topic>): 

         ======================================== 
      
         EOF help quit 
         (hbnb) 
         (hbnb) 
         (hbnb) quit $
```
## Authors :memo:
- **Mentesinot Tegegn Taye**  <[Mentesinot](https://github.com/Mentesinot)>
- **Sentayehu Tilahun Adamu** <[Sentayehut](https://github.com/sentayehut)>     
