# chapter(2): Text
Markup can be :

1-Structural markup

   elements that you can use to describe both headings and paragraphs

2-Semantic markup

provides extra information

Tags(Structural markup)

1-Headings:

2- Paragraph


3-Bold & Italic

4- Superscript & Subscript


 sub: used to contain characters that should be superscript such as the suffixes of dates ormathematical concepts like 
 raising a number to a power

 sup:used to contain characters that should be subscript.

5- White Space

In order to make code easier to read.


*white space collapsing: When the browser comes across two or more spaces next to each other, it only displays one space.*

6-Line Breaks & Horizontal Rules

br: the browser will automatically show each new paragraph or heading on a new line

hr :To create a break between themes

**Visual Editors & Their Code views**

Content management systems and HTML editors such as Dreamweaver usually have two views of the page you are creating:

1-visual editor

often resemble word processors

2- code view

show you the code created by the visual editor so you can manually edit it, or so you can just enter new code yourself

**Tags(Semantic markup)**

1-Strong & Emphasis

strong: use it to indicates that  content has strong importance

em: indicates emphasis that subtly changes the meaning of a sentence.
       
2-Quotations

There are two elements commonly used for marking up quotations:

blockquote

q

3-Abbreviations & Acronyms


abbr: use when you need to use abbreviation or an acronym


4- Citations & Definitions

cite : When you are referencing a piece of work such as a book


dfn: The first time you explain some new terminology


5-Author Details

address

It can contain a physical address, but it does not have to. For example, it may also contain a phone number or email address.


7-Changes to content

ins: element can be used to show content that has been inserted into a document

del: element can show text that has been deleted from it.

# Chapter (10) Introducing CSS

BLOCK & INLINE ELEMENTS

1-Block element

 look like they start on a new line.

2-Inline element

flow within the text and do not start on a new line

**CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed.** 

A CSS rule contains two parts:
 
1-selector 

2-declaration.

CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value.

*Using External CSS*

link
can be used in an HTML document to tell the browser where to find the CSS file used to style the page and it lives inside the element

It should use three attributes:

1-href

This specifies the path to the CSS file

2-type

This attribute specifies the type of document being linked to

3-rel

This specifies the relationship between the HTML page and the file it is linked to


**Using Internal css**

using style tag

**CSS Selectors*

There are many different types of CSS selector that allow you to target rules to specific elements in an HTML document.

1-Universal Selector

2-Type Selector

3-Class Selector

4-ID Selector

5-Child Selector

6-Descendant Selector

7-Adjacent Sibling Selector

8-General Sibling Selector

**Why we use external css ?**

1-All of your web pages can share the same style sheet

2-once the user has downloaded the CSS stylesheet, the rest of the site will load faster. If you want to make a change

3-the one CSS style sheet, rather than changing the CSS rules on every page.

# Chapter(2) “Basic JavaScript Instructions”

**A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement**

comments use to explain what your code does
comments can be :

1-multi-line

2-single-line

**Variables : store the bits of information  in it**

Data type:

1-Numeric

2-String

3-Boolean


Rule for variable naming:

1-The name must begin with a letter, dollar sign ($),or an underscore (_). It must not start with a number.

2-The name can contain letters, numbers, dollar sign ($), or an underscore (_)

3-You cannot use keywords or reserved words.

4-All variables are case sensitive

5-Use a name that describes the kind of information that the variable stores.

6-If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word.

**Arrays An array is a special type of variable. It doesn't just store one value; it stores a list of values.**

**Expression: evaluates into (results in) a single value. Broadly speaking there are two types of expressions.**

**Operator: Expressions rely on things, they allow programmers to create a single value from one or more values.**

 Operator type:

1-Assignment Operator

2-Comparison Operator


3-Arithmetic Operator

4-Logical Operator

5-String Operator

# Chapter (10) “Decisions and Loops”

Comparison operator evaluating conditions:

==(is equal to)

!= (is  not equal to)

===(strict equal to)

!== (strict not equal to)

< (greater than)

> (less than)

<= (greater than or equal)

>= (less than or equal)

Logical operator:

&& (logical and)

|| (logical or)


! (logical not)














