# Implementation of function _printf :sparkles:

## :bulb: Purpose

A simple implementation of the standard C function printf, created by two students from Holberton Tulsa. This function was written to mimick the operations of the standard printing function. The purpose of this function is to be able to print strings, characters, and values to standard output; all *without* the use of the standard library!


## :star: Description
### Declaration
Following is the declaration for the _printf function.
```
int _printf(const char *format, ...)
```
### Format Specifiers
Format specifiers are preceeded by the % character. Below is a table of each data type that is supported through our implementation of _printf.

| Type  | Output |
| ------------- |:-------------:|
| d, i     | signed decimal integer    |
| s     | string of characters    |
| c     | single character    |

### Return value
Upon successful return, the _printf function will return the number of characters printed. 
For example, the following code should print however many bottles of milk are left on the wall, after taking one down and passing it around.
```
_printf("%d bottles of milk on the wall", str);
``` 

In the event of failure or error, a negative value is returned.

## :bulb: Contributors
###### This project was brought to you by the following contributors:

The lovely __*Taylor Woodson*__, from Stigler, Oklahoma. Mom to Charlie. Hairstylist. Enjoys activities outdoors.

![This is a alt text.](https://pbs.twimg.com/media/FghkAgdXkAAxbUL?format=jpg&name=small "@WoodsonTD")

The one and only __*Lindsey Thomas*__, born and raised in downtown Tulsa. Yarn artist, calico owner, part time voodoo chicken slinger.

![This is a alt text.](https://pbs.twimg.com/media/FghkAgdXEAAX0BV?format=jpg&name=medium "@timidgeek")

###### *Thank you for  your time.* :sparkles:
