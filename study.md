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
The DOM is not the HTML that you have written.  It is a compilation of the elements in your HTML (nodes in the DOM tree) that the compiler interprets

The DOM is not a set of data structures.  It only infers and interprets logical relationships (or hierarchies in the code) between items
but it is not describing actual relationship , linkage, or dependencies between their data structures.


https://www.w3.org/TR/REC-DOM-Level-1/introduction.html
```

Is the information inside your Dev Tools the DOM? Why or why not?

```md
Yes and no. It is a representation of the DOM but it may change if for example a JQuery script executes after the page load.
As a result, it seems to me a pretty accurate representation of the DOM at a particular point in time.
```

In your own words, why do you think the DOM is important?

```md
The DOM is important because it allows us to navigate and interact with elements on our page.  Using the DOM, we can likely execute a script
on a particular object or element in the page with prescision since we can navigate to it by traversing the nodes.
```
