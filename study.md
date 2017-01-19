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
1. The HTML code on a webpage is not the DOM.  Rather, the code is analyzed by a web browser, such as Google Chrome, which then creates the DOM

2. The DOM is not permanently altered by jQuery.  Instead, it is a map for jQuery to navigate in order to make temporary modification to the code.
```

Is the information inside your Dev Tools the DOM? Why or why not?

```md
The developer tools found that are part of Google Chrome represent the DOM.  Note that this contrasts with the source code, which cannot be thought of as the DOM.  This is because the code undergoes interpretation by the web browser which make adjustments and alter the code.  This is seen when a developer makes a mistake in the code and Google Chrome "forgives" the mistake and alters the code slightly.  But, the final changes are found in the developer tools and represent an accurate depiction of the DOM.
```

In your own words, why do you think the DOM is important?

```md
The DOM is a very powerful tool and is especially useful in terms of JavaScript/jQuery.  It can be used in order to animate a webpage and make it more interactive.  For instance, if you would like a color to change when a button is pressed, the conditional statement can alter the DOM in real time, without having to reload a page.  Thus, being able to manipulate the DOM is an essential part of web interactivity.
```
