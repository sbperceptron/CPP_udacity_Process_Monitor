# CPP_udacity_Process_Monitor
## Project Overview: 
---------------
Udacity process monitor project: The main goal of the project is to buils a process monitor like htop in linux operating system. The Process monitor displays information of all the process running, CPU usage, RAM usage statistics. This information is obtained by reading into the process files stored in the linux machine and parsing them.

So used C++ programming language to do the parsing of process files and display the stats about each process. Specifically for displaying the data in terminal we use 'ncurses' library to display the data.

## Programming languages and tools used:
----------------
- C++
- ncurses

## ncurses
ncurses is a dedicated API for writing terminal independent text outputs. It refreshes the terminal data every second and it also creates percentage bars and seperate windows within teminal

## installing ncurses package
-------------
`sudo apt-get install libncurses5-dev libncursesw5-dev`

## running the project
-------------
compiling the project

`$ g++ -std='c++17' main.cpp -lncurses`

running the project

`$ ./a.out`
