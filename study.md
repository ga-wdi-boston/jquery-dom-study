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
1. The HTML you write.
2. The HTML in View Source.
```

Is the information inside your Dev Tools the DOM? Why or why not?

```md
<!-- your answer here --> Yes, it can be. In the most basic of instances, the DOM
will look exactly like your HTML, however Javascript can manipulate the DOM so
if there's JavaScript code further down. The DOM will update the HTML to reflect
that Javascript code and your HTML will no longer look like your original HTML or
the HTML in the View Source. Another instance is that if you've missed a closing
tag somewhere in your HTML, the browser will fix it for you causing the DOM to
be different than your original HTML.
```

In your own words, why do you think the DOM is important?

```md
The DOM is what makes the magic happen. When the browser reads your Javascript,
it's just reading what it should be doing. For instance we may have an event on
an element and we've told the browser to listen for it, but it's the DOM node (element)
that will fire that event when it happens.
```
