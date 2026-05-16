# One of the core challenges one faces is the act of omitting the (;).
If you omit the semicolon (;), the JavaScript might not be able to interpret the end and beginning of your code. 
Though JavaScript has an Automatic Semicolon Insertion(ASI), the best practice is to always include it. Semicolon helps your code to be readable. It's like punctuation in English Language that helps it to be readable. 


# Commenting as a best practice in programming.
Commenting are lines of statements that are completely ignored by the Javascript engine when running or executing code. 
In JavaScript and other programming languages comments are either single or multiple.
Single comments - // This is a single comment in syntax in JavaScript
Multiple comments - /* This is a multiple comment syntax in Javascript*/

Comments help other people to read your code and be able to make changes or understand the concept of your code.
Over-commenting on code isn not considered a best practice while programming. 

# Working with Data types in JavaScript
1. What is Dynamic Typing in JavaScript, and How does it differ from statically typed language e.g TypeScript. 

JavaScript is a dynamically typed language and this means that unlike Java and other statically typed languages you don't need to specify the data type of the variable. JavaScript being dynamic in nature makes it easier to work with but introduces a lot of bugs that are not easily identifiable when your program becomes larger. 
* Dynamic typed language don't declare variables. It is the flexibility in data types that gives it the upper hand compared statically typed languages like C# and C++. 

* The typeof operator 
The typeof operator helps you to see the data type of a variable. 

* Bracket Notation 
Bracket Notation is used to access string characters. 
An index is the position of a character within a string, and it is zero-based. This means that the first character of a string has an index of 0, the second character has an index of 1, and so on. 
*hack: You can get the last character of a string using the formula (len of string - 1)
The length property of a string tells you how many characters it contains, so you can access the last character of the string. You have to subtract one (- 1) from the string 

let number = "forty";
console.log(number[number.length - 1]); // this would bring out 'y' as the result

* Newline in Strings and Escape Strings
You can create a newline in a string using a special character called an escape sequence (\n)
The escape sequence is used when applying quotes or quotation marks in your string. The code can be found in escape_seq file in the parent folder.

* String interpolation in JavaScript
The string interpolation in JavaScript ${} is the same as using the fstring in python. They serve the same purpose in both languages. Instead of using the raw concatenation and variable you can use string interpolation. 
-Note: to start and end wit a backtick with a backtick (`)

* indexOf() method
The indexOf() method is used to locate the position of a substring inside a string. A substring are separate or individual group of characters in a string statement. 
Note: indexOf() method is case sensitive.

* prompt() method
The prompt() method is similar to the python method of collecting input from the user but there are quite some differences between them. The prompt() method is used in the web browser while the input() method can be used in the terminal. 

# String Character Methods 
* ASCII charCodeAt() and fromCharCode()
ASCII - American Standard Code for Information Interchange is a character encoding standard that is used in the computer to represent text. This is usually taught in Elementary Computer Science. charCodeat() and fromCharCode() was used to relate to character encoding. ASCII uses he 128 unicode characters. 

charCodeAt() method is used o access the numeric code of a character. 
fromCharCode() method helps to retrieve the character of a numeric code. 

# String Search and Slice Methods 

* Test for substring in strings
include() method is used to check for specific substring in strings. It returns true or false. 
The include() method is case-sensitive just like indexOf. 

* Extracting Substrings from String using slice
To cut out a fragment of word or character you use the slice() method. It extracts the portion and returns a string. 
-Syntax
string.slice(startIndex, endIndex). 
startIndex is the starting point of extraction while the endIndex is the ending point of the extraction. 

# String formatting methods

* toUpperCase() and toLowerCase()
toUpperCase() method converts all characters to uppercase letters.
toLowerCase() method converts all characters to lowercase letters. 

* trim(), trimStart() and trimEnd()
trim() method is used to remove whitespace from both the beginning and end of a string. 
trimStart() method is used to remove whitespace at the beginning 
trimEnd() method is used to remove whitespace at the end. 

# String Modification Methods

* replace() and replaceAll()
replace () method is used to replace a specific with character in a string with another and returning a new string. 
- Syntax
string.replace(searchValue, newValue);
replace() method is case sensitive. 

* repeat()
repeat() method is used to repeat strings. It's like looping at a specific number of time. The count parameter of the repeat() method must not be negative or else it throws a RangeError. 