# Intro and History
I chose C++ as my programming language. 
C++ was created by Bjarne Stroustrup in 1979 as an extension to the C language. It expanded upon the C languages by adding additional features, such as the ability to create classes. 
C++ is a multi-purpose language, and given that it allows programmers to get close to operating systems, it is often used for operating systems and embedded systems, it is also used for GUI and software development.
I plan to continue to learn about C++ by reading the fourth Edition of C++ Programming Language  By Bjarne Stroustrup and viewing the tutorials on Geeksforgeeks.org and w3schools.com

# First Steps

To start writing code in C++, one needs a text editor, this could be any, with or without an IDE. I personally used Vi, as I would like to become more familiar with it as it is available in the terminals of most operating systems. 

In addition to a text editor, one needs a compiler, as C++ is a compiler language, which means that it needs to be translated into code that is executable by the machine. Any compiler that is compatible with C++ will work.

## How to run C++ in the terminal

1. First, create a file in a text editor, title it accordingly, and after the title, add .cpp so that the machine knows it is C++ code.

    _ex. helloworld.cpp_

2. Then you will compile the program by calling the appropriate compiler, with the name of the file you'd like the results to output to and the file that it is taking input from. If there are errors the code will not compile, and the terminal will reflect the location of the error, as well as the type of error. Once the error is corrected in the text editor, one must be sure to re-compile the file with this same command. 

   _ex. gcc -o helloworld helloworld.cpp_

3. Lastly, run code with ./filename, pro tip make sure you are in the same directory location as the file you're running for it to work.

    _ex ./helloworld_
   
_Pro-tip, one can bypass most of these steps by using an IDE that is compatible with C++, which would allow you to write, edit, debug, and run C++ code in one place._

### Adding Comments to C++ Code 

To add comments to this code, use two forward slashes followed by the comment. 

_ex //Commenting something_

Or- in cases of multi-lined comments, you will use forward slash+star followed by the comment, another star, and another forward slash. 

_ex. /*commenting something more extensive.*/_
