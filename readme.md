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

### Comments
Comments in PHP work the same as comments in JavaScript, having the ability to comment one line, or multiple lines as necessary.
