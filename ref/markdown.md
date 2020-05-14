---
title: Markdown
---

# Markdown format

Look at the file with a markdown editor to see to effect of the formatting.

# Header 1
## Header 2
### Header 3
this is not a very good change

or :

Header 1
========

Header 2
--------

Create an _emphasis_

Create a __strong emphasis__

Strike-through some ~~text~~

## Make lists

1. Item 1
2. Item 2
3. Item 3

Or:

- Item 1
- Item 2
- Item 3

# Links

A link is easy to type [Google](https://www.google.com/), or <http://www.icomos.org>

---

# Table

| Number | Name |
|---|---|
|x00001|DOE John|
|x00002|DOE Jane|

| What | Explanation |
| ---|---:|
|Information|The text alignment can be fixed with a ':', see above line|
|Date|June 3d 2020|
|Appointment|da men kou be on time please as we need to go far away da men kou be on time please as we need to go far away da men kou be on time please as we need to go far away|

# Images

![Saint-Denis, France](../pics/p1.png)

# Citations

As you can see in @manthorpe2008, ...

Manthorpe says blah [-@manthorpe2008].


# Footnotes

To create a footnote reference, add a caret and an identifier inside brackets. Identifiers can be numbers or words, but they can’t contain spaces or tabs. Identifiers only correlate the footnote reference with the footnote itself — in the output, footnotes are numbered sequentially.

You don’t have to put footnotes at the end of the document. You can put them anywhere except inside other elements like lists, block quotes, and tables.

Lorem ipsum[^1] dolor sit amet, consectetur adipiscing elit, 
sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor[^t] in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
Excepteur sint occaecat cupidatat non proident,
sunt in culpa qui officia deserunt mollit anim id est laborum.

[^1]: This is a test of footnote. Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.

[^t]: Another footnote. You can use any kind of symbol after the carret, here 't'

# References
