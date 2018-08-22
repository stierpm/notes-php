# PHP Notes

- PHP stands for "PHP: Hypertext Preprocessor"
- PHP files can contain HTML, CSS, JavaScript and PHP

### Data Types
- **String** *example* "The dog wags his tail"
- **Integer** *example* 43
- **Float** *example* 43.75
- **Boolean** *example* false
- **Array**
- **Object**
- **NULL** *example* NULL
- **Resource**

### Variables
Variables in PHP start with the dollar sign, followed by the name of the variable. Variables in PHP have three different scopes:
- **Local:** Any variable declared inside of a function and can only be used inside of that function
- **Global:** Any variable declared outside of a function and can only be used outside of a function, unless you use the 'global' keyword or $GLOBALS array within a function
- **Static:** Any variable prefixed with the 'static' keyword, so that the function that it is within does not delete the data after the function is run. Static variables are still local to their function

### Functions
A function always starts with it's name, followed by opening and closing parentheses. Most functions are like machines, in that once called, they output data. Sometimes you can control the behavior of a function by passing in arguments in the parentheses. Arguments to functions can be found in documentation. You can use functions inside of functions and work from the inside out.
- [PHP Function Index](http://php.net/manual/fa/indexes.php)

### Arrays
Arrays represent a group of things and are important in PHP and, although automatically assigned a number key or index, can be custom mapped using associative arrays. If you do not customize the keys in your array, it is called an Index array. Arrays can be written within arrays.
- Arrays can either be written with array() or just []

### Loops
Loops are language constructs, which means that they are written like functions with an opening and closing curly brace.
- Loop statements do not end with a semi-colon

### Comments
Comments in PHP work the same as comments in JavaScript, having the ability to comment one line, or multiple lines as necessary.
