# Markdown Notes

## Contents
- [Headers](#headers)
- [Separate Line](#separate-line)
- [Emphasis](#emphasis)
- [Lists](#lists)
- [Links](#links)
- [Images](#images)
- [Code](#code)
- [Tables](#tables)
- [Blockquotes](#blockquotes)

## Headers

# Header 1

## Header 2

### Header 3

#### Header 4

##### Header 5

###### Header 6

---
## Separate Line

Use 3 "-" or "*" or "_" to draw a separate line

---

## Emphasis

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

`One line code`

---

## Lists

1. First ordered list item
2. Another item
    * Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
    1. Ordered sub-list
4. And another item

* Unordered list can use asterisks
- Or minuses
+ Or pluses

---

## Links

[Inline link](https://www.google.com/)

[Inline link with header](https://www.google.com/ "Google's Homepage")

Relative reference to a repository [file](./GitNotes.md)

[(reference link)][arbitrary case-insensitive reference text]
Reference link may be marked with [numbers][1]
Reference link may use [the text itself]

Text becomes the link itself [https://www.google.com]

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

text

text

text

[arbitrary case-insensitive reference text]: https://www.mozilla.org/
[1]: http://slashdot.org/
[the text itself]: http://www.reddit.com/

---

## Images

Hover images to see titles

Inline-style image: ![alt text: GitHub logo](https://civic.io/wp-content/uploads/2013/03/github.png?w=100&h= 'Logo Title-1')

Reference-style: ![alt text: GitHub logo][logo]

[logo]: https://civic.io/wp-content/uploads/2013/03/github.png?w=100&h= 'Logo Title-2'

Alt text is shown during image loading errors

You may use images from your local storage with its paths

- ./ -- current directory
- ../ -- parent directory

![Local image](./Images/GithubLogo.png)

---

## Code

`One-line code blocks`

Multiple-line code:

```
while true {
    printf("Hello, world");
}
```

You may note language to use syntax highlighting

```python
s = "Python syntax highlighting"
print s
```

---

## Tables

|Cloumn 1 Header|Cloumn 2 Header |Cloumn 3 Header|
|--------------:|:---------------|:-------------:|
|This           |is a            |simple table   |
|This           |is table        |second row     |
|This           |is table        |third row      | 

1. There must be at least 3 dashes (-) separating each column header cell
2. Outer pipes (|) are optional
3. Colon is used for text alignment 
    1. use :--- for left-aligned
    2. :---: for centred
    3. and ---: for right-aligned
4. You may use inline Markdown

Markdown | Less | Pretty
---: | :---: | :---
*Still* | `renders` | **nicely**
1 | 2 | 3

---

## Blockquotes

> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris interdum libero id quam iaculis ullamcorper. Aliquam erat volutpat. Proin enim magna, semper ut lacinia in, elementum vel sapien. Quisque augue tellus, aliquet sed magna sed, laoreet condimentum sapien. Nulla odio ipsum, congue non risus a, finibus dignissim tellus.

>> Etiam sit amet lectus orci. Proin luctus lorem ex. Nulla sollicitudin semper lorem, id tristique nulla tempus ut. Vivamus rhoncus augue eget lacinia tempor. Pellentesque dui quam, commodo ut metus congue, semper sollicitudin dui. Aliquam maximus sagittis consequat. Donec id erat eu urna volutpat vulputate.

>>> Fusce lobortis ex enim, at scelerisque erat suscipit eu. Proin eget lacinia metus. Praesent in nisi vitae mauris commodo semper. Aenean sodales lectus sed mauris luctus porttitor. Mauris bibendum mi in bibendum tincidunt. Sed nec dolor eros. Etiam ullamcorper diam vel nunc aliquam tristique.

---

## Inline HTML

---
