# Project
In this project, we designed a language, described its grammar, implemented a translator based on Java, and provided three sample programs. 

How to use: 
>>> javac Translator.java

>>> java Translator.java filename > filename.java

>>> javac filename.java

>>> java filename.java

*The piping output java file name must be the filename

Explicit Parsing result will be output to "Explicit Parsing.txt" file

fib, prime and collatz are our example programs. Note that for fib, if the input number is too large the output might overflow
To use fib in command line: 
>>> javac Translator.java

>>> java Translator.java fib > fib.java

>>> javac fib.java

>>> java fib.java 5
