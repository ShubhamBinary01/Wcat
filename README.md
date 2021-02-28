# Wcat
Wcat is a partial synchronous clone of cat command available in bash but not in windows cmd.

It has 2 main features:
    1- To display a text file. (single or multiple files)
    2- To combine copies of text file. (extension of 1)

General Syntax:
Wcat [options] [files]



output generated by script is inserted into a file by override by single arrow
output generated by script is inserted into a file by Append by double arrow

the cmd before > and >> is only executed

option to remove big line break (-s)
option to add line number to non empty lines (-b)
option to add line numbers to all lines (-n) 

Commands:

1- wcat filename => displays content of the file in the terminal 
2- wcat filename1 filename2 filename3... => displays content of all files in the terminal(contactinated form) in the given order.
3- wcat -s filename => convert big line breaks into a singular file 
4- wcat -n filename => give numbering to all the lines 
5- wcat -b filename => give numbering to non-empty lines 

We can mix and match the options.

