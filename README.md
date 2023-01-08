# aside

Simple python script to output files side by side in terminal

## Usage

`aside <file> <file> ...`

## Example

For example, if you have two files:

file1.txt:
```
Hello everybody
in the world today
how are you doing
And what do you all need?
```

and file2.txt:
```
@@@@ WOW @@@@
@@         @@
@@  ...X.  @@
@@  X....  @@
@@  ..X..  @@
@@         @@
@@@@@@@@@@@@@
```

Then if you run `aside file1.txt file2.txt`, you will get:

```
Hello everybody            @@@@ WOW @@@@  
in the world today         @@         @@  
how are you doing          @@  ...X.  @@  
And what do you all need?  @@  X....  @@  
                           @@  ..X..  @@  
                           @@         @@  
                           @@@@@@@@@@@@@  
```
