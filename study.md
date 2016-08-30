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
The DOM is not the HTML code that I, the developer, write.

The DOM is not the code I see when I select "View Source" in the browser.
```

Is the information inside your Dev Tools the DOM? Why or why not?

```md
Kind of. It is the brower's visual representation of the DOM. It will reflect
any changes made to the original HTML by JavaScript, or by the browser's own
auto-correction, or by other mechanisms that we have yet to learn about.
```

In your own words, why do you think the DOM is important?

```md
The DOM is important because it shows the HTML as it really lives in the context
of the web browser where a page is rendered and viewed. The branching layout of
HTML elements as nodes in a tree is useful and sensible from a variety of
perspectives, including:
  -JavaScript commands that might need to find and alter an element
  -the browser's construction of a rendering tree from which to
   lay out, paint, and display the HTML elements
```
