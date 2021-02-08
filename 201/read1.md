# chapter(2): Text
Markup can be :

1-Structural markup

   elements that you can use to describe both headings and paragraphs

2-Semantic markup

provides extra information

Tags(Structural markup)

1-Headings:
From <h 1> to <h 6>  

2- Paragraph
<p>

3-Bold & Italic


<b> bold


<i<> italic


4- Superscript & Subscript


 <sub> used to contain characters that should be superscript such as the suffixes of dates ormathematical concepts like 


 raising a number to a power


    <sup>used to contain characters that should be subscript.

5- White Space

In order to make code easier to read.


*white space collapsing: When the browser comes across two or more spaces next to each other, it only displays one space.*

6-Line Breaks & Horizontal Rules

<br/> the browser will automatically show each new paragraph or heading on a new line

<hr/>To create a break between themes

**Visual Editors & Their Code views**

Content management systems and HTML editors such as Dreamweaver usually have two views of the page you are creating:

1-visual editor

often resemble word processors

2- code view

show you the code created by the visual editor so you can manually edit it, or so you can just enter new code yourself

**Tags(Semantic markup)**

1-Strong & Emphasis

<strong> use it to indicates that  content has strong importance

<em> indicates emphasis that subtly changes the meaning of a sentence.
       
2-Quotations

There are two elements commonly used for marking up quotations:

<blockquote>

<q>

3-Abbreviations & Acronyms


<abbr> use when you need to use abbreviation or an acronym


4- Citations & Definitions

<cite > When you are referencing a piece of work such as a book


<dfn> The first time you explain some new terminology


5-Author Details

<address>

It can contain a physical address, but it does not have to. For example, it may also contain a phone number or email address.


7-Changes to content

<ins> element can be used to show content that has been inserted into a document

<del> element can show text that has been deleted from it.

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

<link>
can be used in an HTML document to tell the browser where to find the CSS file used to style the page and it lives inside the element

It should use three attributes:

1-href

This specifies the path to the CSS file

2-type

This attribute specifies the type of document being linked to

3-rel

This specifies the relationship between the HTML page and the file it is linked to


**Using Internal css**

 <style>

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








