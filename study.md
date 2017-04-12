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
The DOM is NOT the HTML you write. Nor is the view you see the DOM. The DOM is
a data structure your code will interact with.
```

Is the information inside your Dev Tools the DOM? Why or why not?

```md
Yes. The data you see in your dev tools is representative of the data structure
the page is broken into.
```

In your own words, why do you think the DOM is important?

```md
Previous to the DOM web devs had to implement some whacky code acrobatics to try
and make pages dymanmic. The reason is that before the DOM there wasn't really
an easy way to change a single element on the page. If you wanted to change say,
a single value on a line on a page, you had to re-write the entire page on the
back end and send it to the browser. It was costly in bandwidth at the time since
we were not typically on broadband and it took a lot more work on the servers to
serve up entire pages for a single change. The DOM allows for parsable sections
of HTML to be changed and sent back in sections rather than entire pages.
```
