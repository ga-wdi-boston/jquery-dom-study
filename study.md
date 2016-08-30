# jQuery Study

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
The DOM is not source code. It's also not the rendered page—it's an API for 
interacting with the tree of nodes inside an HTML (or XML) document.
```

Is the information inside your Dev Tools the DOM? Why or why not?

```md
Yes. Dev Tools shows the full document tree (consisting of nodes/elements within 
the rendered document). When writing complex web apps, you likely aren't working 
with the full page's HTML in a single file. What's more: when browsers render HTML, 
they can sometimes correct small mistakes (which means your HTML may not perfectly 
match up with the DOM). The page's source in the browser also may not be a full 
representation of the DOM, as it doesn't reflect any DOM elements that are being 
generated on the server side or manipulated on the fly (i.e., by JavaScript).
```

In your own words, why do you think the DOM is important?

```md
The DOM is important because it lets us interact with different pieces of an HTML 
(or XML) document. Using the DOM, we can create, read/navigate, edit, and delete 
elements on a page. 

```
