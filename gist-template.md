:trident::trident::trident:#REGULAR EXPRESSION ( Cool RegeX ) :biohazard: :biohazard:

:om:#DESCRIPTION 

:om:## Summary

This is an example of a RegEx Expression meant to match only the first phone number in a text:

\(?\d{3}[-.)]\d{3}[-.]\d{4}$

Text is : :heartbeat:If you love me call at 801.235.2566 , if you are still confused text me (801)555-6666.:heartbeat:

You will find details about the how this Regular Expression works and each part of it.

:om:## Table of Contents
- [Anchors](#Anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)


## Regex Components

:symbols:### Anchors

From the beginning, the first and last symbols are ^ && $. These specifically are known as Line/String Anchors. They are very special, as they are not meant to match characters, but to match the position of them in a string or \n.

In my example $ means the end of the expression

:symbols:### Quantifiers

Quantifiers are used to match the scope of a term which precedes it. You must place these quantifiers at the end of your desired scope, as they are looking for anything to match before its placement.

Like for my example d{3} means that have to have 3 characteres.
And also ? matches between 0 and 1 characters of the preceeding expression boundaries

:symbols:### OR Operator

:symbols:### Character Classes

In the expression, we find character classes are popular! Character classes zone in on any specific character set, combination, any digit, etc.

in this case [-.] between the square parenthesis has to macth what is in the phone number - or .

:symbols:### Grouping and Capturing

In the expression, Grouping and Capturing are found using () as a means to specify/consolidate which information we want to capture. Any subpattern inside a pair of these parentheses will be captured within a 'group.'

In my example the group is (?\d{3}[-.)


## Author

:nerd_face: Hello!!! :wave::wave: My name is Carolina Reedy and I am full Stack Developer, if you have any question please visit : https://github.com/carinvid
