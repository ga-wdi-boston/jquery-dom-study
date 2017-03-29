# jQuery Study

Use your favorite search engine and the provided readings to research and
respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your
search. We ask you to write responses in your own words in order to see how you
process what you've read. Please do not respond with direct quotes from source
material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

-   [The DOM | Wikipedia](https://en.wikipedia.org/wiki/Document_Object_Model)

-   [The DOM | CSS-Tricks](https://css-tricks.com/dom/). You may **ignore**
    these sections if you wish: "JavaScript can manipulate the DOM" and "Ajax
    and Templating".

-   [Try jQuery](http://try.jquery.com/). You only need to complete level 1.

-   [Check out this video](https://www.youtube.com/watch?v=n1cKlKM3jYI). The
point is to get to think about the DOM as a tree! The DOM is not source and
it's also not a rendered page.

## jQuery !== ?

Please name two things the DOM is not.

```md
1. It is not another programming lanuage but an API that JS uses.  JavaScript uses the DOM to access the document and its elements. The DOM is not a programming language
2. The DOM is not a web page but it is another way to represent, store and manipulate that same document. The DOM is a fully object-oriented representation of the web page but you do not write specific code to 'create' the DOM but you do write code to access objects in the tree node of the DOM.
3. The DOM is not source code nor is it a rendered page
```

Is the information inside your Dev Tools the DOM? Why or why not?

```md
It is. If, for example, you make a change to a DIV using Java Script, and you then used DevTools, you'd be able to see the new representation of this change to the DOM even though the original HTML did not change.
```

In your own words, why do you think the DOM is important?

```md
When a web page is loaded, the browser creates a tree like structure called the Document Object Model of the page and it builds nodes as the page is loaded. The HTML page (node) is the child of the DOM node. The  DOM model is built as a tree of Objects. To quickly traverse to a precise location in a HTML file you'd use the DOM. Also Javascript can dynamically manipulate the DOM. For example, JS can add new HTML elements and attributes or even change all the CSS styles in the page. An example is a travel website like travelocity that shows the number of users that booked a given hotel in the past 24 hours when you bring up a page of hotels. That number is been dynamically generated via DOM manipulation. I couldn't say this better myself so I'll quote this source:
https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction
"It provides a structured representation of the document and it defines a way that the structure can be accessed from programs so that they can change the document structure, style and content. The DOM provides a representation of the document as a structured group of nodes and objects that have properties and methods"
```
