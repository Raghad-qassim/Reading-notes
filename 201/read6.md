# chapter (3)

**Objects**
 group together a set of variables and functions to create a model of a something you would recognize from the real world.

*Variables become known as properties*

*Function become known as method*

**You can access the properties or the methods of an object using the dot notation** 

![image](https://cdn-images-1.medium.com/max/1024/1*GA7toY-Y3a3l0nlewOxIAw.png)
 
 # Chapter(5)

**The Document Object Model (DOM)**

specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

**people call the DOM an Application Programming Interface (API).**

![img](https://www.conceptdraw.com/solution-park/resource/images/solutions/dom-tree/SOFTWARE-DEVELOPMENT-DOM-Tree-DOM-Hierarchy-in-HTML88.png)


 **Accessing and updating the DOM tree involves two steps:**

1: Locate the node that represents the element you want to work with.

2: Use its text content, child elements, and attributes. 

*DOM queries may return one element, or they may return a Nodelist,
which is a collection of nodes.*

**Method that return a single element node :**

1-getElementByld( 'id' )

2-querySel ector( ' css selector')

**Method that return a one or more element :**

1-getEl ementsByClassName( ' class ' )

2-getEl ementsByTagName( ' tagName ' )

3-querySelectorAll ( 'css select or')

**A Nodelist is a collection of element nodes. Each node is given an index number (a number that starts at zero, just like an array).**

1-a live Nodelist, when your script updates the page, the Nodelist is updated at the same time

2-a static Nodelist when your script updates the page, the NodeList is not updated to reflect the changes made by the script.

**traversing the DOM**

When you have an element node, you can select another element in relation to it using these five properties:
1-parentNode

2-previousSibling 

nextSibling

3-firstChild

 lastChild

 *Traversing the DOM can be difficult because some browsers add a text node whenever they come across whitespace between elements.*

**node value property.**

 you can select a text node, you can retrieve or amend the content using it

**The textContent property**

allows you to collect or update just the text that is in the containing element (and its children)

**i nnerHTML property**

you can access and amend the contents of an element, including any child elements using it


**DOM manipulation**

offers another technique to add new content to a page (rather than i nnerHTML). It involves three steps:

1-CREATE THE ELEMENT 

createEl ement ()

2-GIVE IT CONTENT ADD IT TO THE DOM 

createTextNode()

3-ADD IT TO THE DOM 

  appendChild()

**DOM manipulation can be used to remove elements from the DOM tree.**

**Comparing techniques (update HTML content:)**
we have seen three techniques for adding HTML to a web page:

1-document.write()

2-element.innerHTML

3-DOM MANIPULATION

**If you add HTML to a page using i nnerHTML (or several jQuery methods), you need to be aware of Cross-Site Scripting Attacks or XSS**

XSS can give the attacker access to information in: 

• The DOM (including form data) 

• That website's cookies 

• Session tokens: information that identifies you from other users when you log into a site
