# fieldz
A bash script.

Usage: fieldz [-d field-delimiter] [-r record-separator] [ -z ] [[-]column-number[+]|-fieldname|text]...[filename]
	
Run 'fieldz -h' for more info.
	
Print given field column(s) from input.  Default is last field.  	
Use a minus number to print counting from the last field.  	
First field is numbered from 1 not from zero.  Zero refers to all fields.	
eg, echo a b c | fieldz 1 2   ==> a b 

