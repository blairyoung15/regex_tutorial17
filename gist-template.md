# Regex Turotial - Hex Value

In this tutorial, you will gain a better understanding of regex, also known as regular expression, and how a regex can be used to find a hex value. A regex is used in programming to define a specific search pattern, which is displayed as a sequenze of characters. Often, regex is used to find patterns of characters within a string, find or replace a cahracter or sequence of characters within a string or validate input. 

## Summary

For this tutorial, we will be breaking down a regex used to match a hex value. A hex value is a hexadecimal way to represent color using RGB format. The RBG (red, blue green) format is combosed of three values, which represents the amounts of the RBG in the color shade. 


<kbd>/^#?([a-f0-9]{6}|[a-f0-9]{3})$/</kbd>


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### **Anchors**
<kbd>/^</kbd>#?([a-f0-9]{6}|[a-f0-9]{3})<kbd>$/</kbd>

Anchors are the first part of the regular expression that we will be looking at. They are crucial for a regular expression becuase they denote the beginning and end of a regular expression. If these special characters are not used, the user will not be able to find a match or validate and input correctly. There are two types of anchors used: <kbd>^</kbd> a caret and <kbd>$</kbd> a dollar sign. A caret is used at the beginning, a dollar sign at the end of the regex. 

In our code above, we see the beginning anchor and end anchor highlighted.




### **Quantifiers**
/^#<kbd>?</kbd>([a-f0-9]<kbd>{6}</kbd>|[a-f0-9]<kbd>{3}</kbd>)$/

Quantifiers are used to define the number of times a character, pattern or group can appear in a match. The quantifiers in the above code are highlighted. <kbd>?</kbd> The question mark quantifier is used to match zero or one preceding character. <kbd>{}</kbd> The curly braces are used ot create a specific numeric quantifier range. For the hex value, we see the code has two sets of curly braces. The curly braces define that the preceding quantifiers should be 6 (hex triplet format) or 3 (shorthand hex format) characters long. 

### **OR Operator**
/^#?([a-f0-9]{6}<kbd>|</kbd>[a-f0-9]{3})$/

The Or operator is used to tell the code that either code on each side of the vertical bar <kbd>|</kbd> can be used for a match. In the code above we see that a match can be made with <kbd>a-f0-9]{6}</kbd> or <kbd>a-f0-9]{3}</kbd>.

### **Character Classes**

### **Flags**

### **Grouping and Capturing**

### **Bracket Expressions**

### **Greedy and Lazy Match**

### **Boundaries**

### **Back-references**

### **Look-ahead and Look-behind**

## Author

Blair Young

I am a student in the full stack developer course through Washington University - St. Louis. To see more of my projects, visit my [github](https://github.com/blairyoung15).
