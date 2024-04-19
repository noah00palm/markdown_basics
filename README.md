# Markdown Basics

## Headlines, Paragraphs, and Basic Formatting

### Headlines

```
#### Heading Level 4
##### Heading Level 5
###### Heading Level 6
```

### Paragraphs and Line Breaks

We create paragraphs by typing the way we would in any other program.
Just hit return twice to start another paragraph.

Where you see empty space between blocks of text in your Markdown document, you will see empty space separating those blocks of text in your formatted HTML document.

To create a line break, hit the spacebar twice + enter key

### Emphasis and Bolding

#### Italics

```
This *works* and this _works_ too.
```

#### Bolding

```
This **works** and this __works__ too.
```
or  
```
This ***works*** and this ___works___ too.
```

### Blockquotes

>Markdown is intended to be as easy-to-read and easy-to-write as is feasible.
>
>Readability, however, is emphasized above all else. A Markdown-formatted document should be publishable as-is, as plain text, without looking like it's been marked up with tags or formatting instructions - [John Gruber](https://daringfireball.net/projects/markdown/ "Creator of Markdown")

### Horizontal Rule

___

---

***

## List

### Numbered Lists

1. Item 1
2. Item 2  

#### Nested Number List

1. Item 1
    1. Item 1
    2. Item 2

### Bulleted Lists

* Item
* Item


* Item
    * Item
        * Item

* Bulleted Item

* ***Bulleted, bold, italicized item***

1. Item 1
    * Item
    * Item
2. Item 2
    * Bulleted Item
        1. Item 1
        2. Item 2

---

## Code

### Inline Code

To install the latest version of NPM, you can type, `npm install npm@latest -g`

### Block Code

#### Example 1:

```
let exampleFunction = () => {
    let foo = 'foo';
    let bar = 'bar';

    return foo + bar;
}
```

#### Example 2:

```JavaScript
let exampleFunction = () => {
    let foo = 'foo';
    let bar = 'bar';

    return foo + bar;
}
```

---

## Links

#### Link

[Treehouse](https://teamtreehouse.com)

#### Link with ALT Text

[Treehouse](http://teamtrehouse "Link to Treehouse")

#### Reference Link

[Treehouse][1]


[1]: https://treehouse.com "Reference Link to Treehouse"

---

## Images

#### Image

![Kittens](https://placekitten.com/250/400)

#### Image with Link

[![Kittens](https://placekitten.com/300/400)](https://placekitten.com/)

#### Image with ALT Text

![Kittens](https://placekitten.com/350/400 "Curious Kitten")

#### Image with ALT Text and Link

[![Kittens](https://placekitten.com/350/400 "Fluffy Kitten")](https://placekitten.com/)

---
