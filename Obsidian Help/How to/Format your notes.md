Obsidian is a Markdown-based note-taking and knowledge base app.

We currently support the formats below:

---

### Headers

# This is a heading 1
## This is a heading 2
### This is a heading 3 
#### This is a heading 4
##### This is a heading 5
###### This is a heading 6

---

### Emphasis

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

---

### Lists

* Item 1
* Item 2
  * Item 2a
  * Item 2b

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

--- 

### Images

![Engelbart](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg)

---

### Links

http://obsidian.md - automatic!
[Obsidian](http://obsidian.md)

---

### Blockquotes

> Human beings face ever more complex and urgent problems, and their effectiveness in dealing with these problems is a matter that is critical to the stability and continued progress of society.

\- Doug Engelbart, 1961

---

### Inline code

I think you should use an `<addr>` element here instead.

---

### Code blocks

Syntax highlight is supported with the language specified after the first backticks.

```js
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

    Text indented with a tab is formatted like this, and will also look like a code block in preview. 
    
---

### Task list

- [x] #tags, [links](), **formatting** supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [x] this is an incomplete item

---

### Tables

You can create tables by assembling a list of words and dividing them with hyphens `-` (for the first row), and then separating each column with a pipe `|`:

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

---

### Strikethrough

Any word wrapped with two tildes (like ~~this~~) will appear crossed out.

---

### Footnotes

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: meaningful!

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.

### Math
$$\begin{vmatrix}a & b\\
c & d
\end{vmatrix}=ad-bc$$


## Obsidian specific

### Highlighting

Use two equal signs to ==higlight text==.

### Internal linking

Link to a page: [[Internal link]].

### Internal embeds

Embed another file (read more about [[embedding]]).

![[Obsidian]]