# PHP Notes
- PHP stands for "PHP: Hypertext Preprocessor"
- PHP files can contain HTML, CSS, JavaScript and PHP

### Data Types
- **String** *example* "The dog wags his tail"
- **Integer** *example* 43
- **Float** *example* 43.75
- **Boolean** *example* false
- **Array** *example* ['data','data','data']
- **Object**
- **NULL** *example* NULL
- **Resource**

### Variables
Variables in PHP start with the dollar sign, followed by the name of the variable. Variables in PHP have three different scopes:
- **Local:** Any variable declared inside of a function and can only be used inside of that function
- **Global:** Any variable declared outside of a function and can only be used outside of a function, unless you use the 'global' keyword or $GLOBALS array within a function
- **Static:** Any variable prefixed with the 'static' keyword, so that the function that it is within does not delete the data after the function is run. Static variables are still local to their function
- **Constants:** Constants are created using the define(name,value,case-insensitive[default:false]) function and once defined, cannot be changed. Constants are automatically global.

### Strings
A string is a sequence of characters. String concatenation can be performed with a "." between variables, unlike JavaScript, which uses a "+". Any number of PHP string functions can be called on a string to output information about that string.
- **strlen()** returns the length of a string
- **str_word_count()** returns the number of words in a string
- **strrev()** reverses a string
- **strpos()** searches for specific text within a string
- **str_replace()** replaces a text with specified text in a string
- [PHP String Reference](http://php.net/manual/en/ref.strings.php)

### Arithmetic Operators
- **+** addition *$x + $y*
- **-** subtraction *$x - $y*
- **\*** multiplication *$x * $y*
- **/** division *$x / $y*
- **%** modulus *$x % $y*
- **\*\*** exponentiation *$x &ast; $y*

### Assignment Operators
- **=** value set *x = y*
- **+=** addition *x += y or x = x + y*
- **-=** subtraction *x -= y or x = x - y*
- **\*=** multiplication *x &ast;= y or x = x &ast; y*

### Comparison Operators
- **==** equal *$x == $y*
- **===** identical *$x === $y*
- **!=** not equal *$x != $y*
- **<>** not equal *$x <> $y*
- **!==** not identical *$x !== $y*
- **>** greater than *$x > $y*
- **<** less than *$x < $y*
- **>=** greater than or equal to *$x >= $y*
- **<=** less than or equal to *$x <= $y*

### Increment/Decrement Operators
- **++$x** pre-increment, will increment by one then return value
- **$x++** post-increment, returns value then increments by one
- **--$x** pre-decrement, will decrement by one then return value
- **$x--** post-decrement, returns value then decrements by one

### Logical Operators
- **and** true if both are true *$x and $y*
- **or** true if either is true *$x or $y*
- **xor** true if either is true, but not both *$x xor $y*
- **&&** true if both are true *$x && $y*
- **||** true if either is true *$x || $y*
- **!** not true *!$x*

### Conditional Statements
Conditional statements are used to perform different actions based on different conditions.
- **if** executes if one condition is true
- **if...else** executes some code if condition is true and another if condition is false
- **if...elseif...else** executes different code blocks for more than two conditions
- **switch** selects one of many block of code to be executed

### Functions
A function always starts with it's name, followed by opening and closing parentheses. Most functions are like machines, in that once called, they output data. Sometimes you can control the behavior of a function by passing in arguments in the parentheses. Arguments to functions can be found in documentation. You can use functions inside of functions and work from the inside out.
- [PHP Function Index](http://php.net/manual/fa/indexes.php)

### Arrays
Arrays represent a group of things and are important in PHP and, although automatically assigned a number key or index, can be custom mapped using associative arrays. If you do not customize the keys in your array, it is called an Index array.
- Arrays can be written within arrays, also called multi-dimensional array
- Arrays can either be written with array() or just []

### Loops
Loops are language constructs, which means that they are written like functions with an opening and closing curly brace.
- Loop statements do not end with a semi-colon

### Comments
Comments in PHP work the same as comments in JavaScript, having the ability to comment one line, or multiple lines as necessary.
