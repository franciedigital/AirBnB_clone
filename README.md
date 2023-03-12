<p align="center">
  <!-- <img src="https://github.com/franciedigital/AirBnB_clone/blob/master/public/images/hbnb_logo.png" alt="ALX Airbnb logo"> -->
  <img src="./public/images/hbnb_logo.png" alt="ALX Airbnb logo">
</p>

</p>

# AirBnB Clone
--------------
### This project is a clone of the AirBnb web application

## Command interpreter
----------------------

The command interpreter is a command line interpreter use to manage the object of this project.
- Create a new project
- Retrieve an object from a file or database
- Do operation on objects (count, compute states, etc...)
- Update attributes of an object
- Destroy an object

The interpreter works in interactive mode
$ ./console.py
(hbnh) help

Documented commands (type help <topic>):
EOF help quit

(hbnb)
(hbnb)
(hbnb) quit
$

But also in non-interactive mode
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
EOF  help quit
(hbnb)
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
EOF help quit
(hbnb)
$
