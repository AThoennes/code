# code
## Description
This is my first attempt at a shell script. It create a file with the specified 
name (as of right now it only suports java) and allows you to specify if you want
a main method in the class or not. By default, this script will write the file and 
it's contents to the Desktop.

## Installation
To use, put the *code* file into the directory, */usr/local/bin/* and put *. /usr/local/bin/code*
into *~/.bash_profile*

## Usage
This program is very simple to use. You call the command by typing *code*. From there you can specify 
if you want a main method *-m* and what the file name with the extension. You may specify a path but
that is optional. Just be sure that the path exists. Type code -h for the help message.
