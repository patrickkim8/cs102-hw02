# cs102-hw02

**Due November 13**

For this assignment, you will need to fork this respotiory (see the upper-right corner of this page).
Once you have your own fork, clone it like you would with any other repository. Edit 
`hw03.c` to print the correct output, and then commit and push your changes to your fork.

The goal of this assignment is to create a `struct` that stores student data (it's already half way done for you!) and prints it differently according to the specified `Mode`. The 4 fields your student struct should store are `first_name`, `last_name`, `major`, and `year`. These will be populated from `argv`. The program will be compiled and invoked as follows:

```
clang hw03.c -o hw03
./hw03 0 first_name1 last_name1 major1 year1 first_name2 last_name2 major2 year2 ...
```
Note that there could be an arbitrarily large number of students' data in argv. 

Details about the implementations of the functions in `hw03.c` are in the comments.

Example input commands and their corresponding expected outputs are show in `example_input.sh` and `example_output.txt` respectively.
