# mksh
Generates a bash script from a standard template with some basic functions.

Just copy `mksh` and `templ.txt` to a folder in your `$PATH`. 

Features:

* a "main" function at the top of your script where you can define functions below.
* 8 bit color support
* built-in functions for printing informational, warning, and error messages. As well as a standard for user input prompts.
* sample option parsing
* standardized documentation comment at the top of the script

Example:

    pmood@server:~/test$ mksh
    [?] What's the name of the script? TestScript
    [?] Who made it? pmood
    [?] What does it do? Test
    [-] Created /home/pmood/test/TestScript.
    [-] There. It's done.
    pmood@server:~/test$ ./TestScript
    [~] Function not yet implemented.
