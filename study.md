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
1. The HTML I write is NOT the DOM. But the HTML I write is parsed by the browser and turned into the DOM.
2. View Source is NOT the DOM. View Source just shows you the HTML that makes up that page. It's probably the exact HTML that you wrote.
```

Is the information inside your Dev Tools the DOM? Why or why not?

```md
Yes! When we are looking at the panel in whatever DevTools you we using that shows us stuff that looks like HTML, that is a visual representation of the DOM!
```

In your own words, why do you think the DOM is important?

```md
When our page is rendered, it goes through a process in which DOM and CSSOM interpret our CSS and HTML files' nodes. They are both combined into a render tree that contains the nodes to be rendered, later into a layout and finally the painting on the page. The DOM communicated the html important nodes to the render tree, which represent html elements. The DOM represents the html document as a group of nodes.  ```
