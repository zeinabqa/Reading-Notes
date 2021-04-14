## HOW HTML, CSS,& JAVASCRIPT FIT TOGETHER
*Before diving into the JavaScript language, you
need to know how it will fit together with the
HTML and CSS in your web pages.*

1. CONTENT LAYER :
Web developers usually talk about three languages that are used to create web pages
HTML, CSS, and JavaScript.
2. PRESENTATION LAYER :
Where possible,aim to keep the three languages in separate files,with the HTML page linking to
CSS and JavaScript files. 
3. BEHAVIOR LAYER :
Each language forms a separate layer with a different purpose. Each layer, from left to right.
builds on the previous one.
## PROGRESSIVE ENHANCEMENT
*These three layers form the basis of a popular
approach to building web pages called
progressive enhancement.*

1. HTML ONLY :
Starting with the HTML layer
allows you to focus on the most
important thing about your site:
its content.
Being plain HTML, this layer
should work on all kinds of
devices, be accessible to all
users, and load quite quickly on
slow connections.
2. HTML+CSS :
Adding the CSS rules in a
separate file keeps rules
regarding how the page looks
away from the content itself.
You can use the same style sheet
with all of your site, making your
sites faster to load and easier
to maintain. Or you can use
different style sheets with the
same content to create different
views of the same data. 
3. HTML+CSS+JAVASCRIPT :
The JavaScript is added last
and enhances the usability of
the page or the experience of
interacting with the site.
Keeping it separate means
that the page still works if the
user cannot load or run the
JavaScript. You can also reuse
the code on several pages
(making the site faster to load
and easier to maintain). 
## CREATING A BASIC JAVASCRIPT
*JavaScript is written in plain text, just like HTML and CSS, so you do not
need any new tools to write a script. This example adds a greeting into an
HTML page. The greeting changes depending on the time of day.*
## LINKING TO A JAVASCRIPT FILE FROM AN HTML PAGE
*When you want to use JavaScript with a web page, you use the HTML
<script> element to tell the browser it is coming across a script.
Its s re attribute tells people where the JavaScript file is stored.*

## THE SOURCE CODE IS NOT AMENDED
*If you look at the source code for the example
you just created, you will see that the HTML is
still exactly the same.*
 ## PLACING THE SCRIPT IN THE PAGE
 *You may see JavaScript in the HTML between
opening <script> and closing </script> tags
(but it is better to put scripts in their own files).*

## Basic JavaScript Instructions
 *In this chapter, you will start learning to read and write
JavaScript. You wil l also learn how to give a web browser
instructions you want it to follow.*

1. THE LANGUAGE:
SYNTAX AND GRAMMAR
like any new language, there are new
words to learn (the vocabulary) and rules
for how these can be put together (the
grammar and syntax of the language)

2. GIVING INSTRUCTIONS:
Web browsers (and computers in general)
approach tasks in a very different way than
a human might. Your instructions need to
reflect how computers get things done.

## STATEMENTS :
*A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement.
Statements should end with a semicolon.*

## COMMENTS :
*You should write comments to explain what your code does.
They help make your code easier to read and understand.
This can help you and others who read your code.*

### Type :
1. MULTI-LINE COMM ENTS :
To write a comment that stretches over more than
one line, you use a multi-line comment, starting with
the /* characters and ending with the */ characters.
Anything between these characters is not processed·
by the JavaScript interpreter.
M ulti-line comment s are often used for descriptions
of how the script works, or to prevent a section of
the script from running when testing it.

2. SINGLE-LINE COMMENTS :
In a single-line comment, anything that follows the
two forward slash characters I/ on that line will not
be processed by the JavaScript interpreter. Singleline comments are often used for short descriptions
of what the code is doing.
Good use of comments will help you if you come
back to your code after several days or months.
They also help those who are new to your code.
