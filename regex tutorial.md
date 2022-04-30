Title (replace with your title)
In this, I am going to explain Regex

Summary
The RegExp object is used for matching text with a pattern.

(MDN RegEx)[https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp]

let str = 'JavaScript';
console.log(/^J/.test(str));
## Table of Contents
Anchors
Quantifiers
OR Operator
Character Classes
Flags
Grouping and Capturing
Bracket Expressions
Greedy and Lazy Match
Boundaries
Back-references
Look-ahead and Look-behind
Regex Components
(Other Developer's Idea)[https://blog.bitsrc.io/a-beginners-guide-to-regular-expressions-regex-in-javascript-9c58feb27eb4_)

Anchors
Anchors represent a position at the beginning and end of the text not a character.

The ^ represents the position at the beginning of the text.
let str = 'JavaScript';
console.log(/^J/.test(str));
Any text that starts with the anchor J will return true. If not, it will return false.

The & represents the position at the end

And text that ends with the anchor & will return false. If
Quantifiers
Look at MDN first. That is the gold standard.
Look at WC3 schools or Medium for more 'human' language.
Put it in your own words.
For the code, create or use an example. Explain it in a single line.

OR Operator
Character Classes
Flags
Grouping and Capturing
Bracket Expressions
Greedy and Lazy Match
Boundaries
Back-references
Look-ahead and Look-behind
Author
A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)

This is how you link: (the text that will highlight)[www.google.com]

regex_ex.md
Regex tutorial for Module 17 - Matching a URL
A regular expression is a sequence of characters that define a search pattern. These expressions can be used for string-searching algorithms, find and find and replace operations on strings. They are also often used for data validation.

Summary
The regex I will be attempting to explain is the matching a URL regex. I will explain the different componets that make up a regex and how each is used in this particular expression.
/^(https?://)?([\da-z.-]+).([a-z.]{2,6})([/\w .-])/?$/
Table of Contents DON'T TOUCH THIS SECTION! IT IS DONE FOR YOU!
Anchors
Quantifiers
OR Operator
Character Classes
Flags
Grouping and Capturing
Bracket Expressions
Greedy and Lazy Match
Boundaries
Back-references
Look-ahead and Look-behind
Regex Components
Anchors
The anchor/position meta characters ^ and $ asserts position at the start and end of the string.
^ - marks the beginning of the string
$ - marks the end of the string
Quantifiers
OR Operator
Character Classes
Flags
Grouping and Capturing
Bracket Expressions
Greedy and Lazy Match
Boundaries
Back-references
Look-ahead and Look-behind
Author
A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)