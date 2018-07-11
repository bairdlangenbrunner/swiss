---
layout: page
title: about
permalink: /about/
---

This theme is adapted from Swiss, which itself was "inspired by Swiss design and the works of Massimo Vignelli."  I (Baird) think it's a beautiful theme to start from, and I wanted to edit it to include things like more advanced syntax highlighting and simpler page responses to media.

The primary reason I designed this theme is to be able to discuss research, coding, and blog all within the same document.  Jekyll and GitHub Pages allows for this very nicely, but it's a bit of a learning curve at first.

Something I've specifically added on top of the Swiss theme is syntax highlighting.  By default, it comes with the Solarized Dark theme.  Some example code looks like this:

```python
# add python code here
a = 6
b = 7
def plus(a,b):
    return(a+b)
```

Notice there's specific syntax highlighting.  To create a block of code like this, you enclose it in three single quotation marks.  To make sure it recognizes Python syntax, you also must add Python to it:

	```python
	# add python code here
	a = 6
	b = 7
	def plus(a,b):
		return(a+b)
	```

If you aren't so into the syntax highlighting but still want to use big blocks of code, you can go without the ```python``` above, which looks like this:

```
# without "python" at top
# add python code here
a = 6
b = 7
def plus(a,b):
    return(a+b)
```

I'll update this with more information as I develop my personal websites.

<!--
### Features:
* Mobile-first design ensures this theme performs fastest on mobile while scaling elegantly to desktop-size screens.
* Designed for blogs and sites heavy on written content, with bold typography styles, homepage summaries, and previous/next snippets.
* Supports a wide range of HTML elements and markdown.
* Flexible styles that can be reused for customization without adding additional CSS.
* Simple styling for code snippets (if you want something with syntax highlighting, checkout ....)
* Dynamically generated navigation links. See docs below for adding pages with specific post category for-loops.

## Themes

## Browser Support

## Installation
-->