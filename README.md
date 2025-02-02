# TEXT CHECKER

## INTRODUCTION

The text cheker is used to correct a text. Given a dictionary of valid \
words, the program finds words in the text that do not appear in the dictionary \
and, by applying a series of different transformations to each 'wrong' word, provides \
with a few (up to five) altenatives of words that could have been misspelled. \
After the program execution, an output file contains every wrong word found \
and their corresponding alternatives.

## CODE CONVENTIONS

Variable names: exampleExample (camelCase) \
Function names: example_example (snake_case)\
Struct names: Example \
Language: English 

## COMPILE PROGRAM
In order to compile the program, running any of these lines is valid:
```
make
```
  o 
```
gcc -o main main.c glist.c hash_table.c dict.c word_functions.c utils.c io.c
```

## TEXT CHECKING

To check a text, the program must be run with the following format:
```
./main input_file.txt output_file.txt
```
Where 'input_file.txt' is the name of the file that contains the text to check.
This file must exist in the same directory where the program is found. \
'output_file.txt' referes to the name of the file that will contain \
the text's corrections. It will be written in the same directory where \
the program is found.

## REMOVE GENERATED FILES

To remove the files generated by the use of the program, the next line \
must be run.
```
make clean
```

 \
 \
Program made by Juan Bautista Figueredo.
