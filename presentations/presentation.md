---
marp: true
---
# Lists

<style>
.container {
   display: grid;
   grid-template-columns: 1fr 1fr;
   grid-gap: 10px;
   text-align: left;}
</style>
<div class="container">
  <div>

- punt a
- punt b
  - punt b2  
  </div>
  <div>

1. punt 1
2. punt 2
   1. punt 2b
  </div>
</div>


  <br>

---
# Headings and Emphasis
## Heading 2
*Normal paragraph! cursive*
### Heading 3
**Normal paragraph! bold**
#### Heading 4
***Normal paragraph! bold + cursive***
~~Strike-through!~~

---
# Code-blocks
Inline code looks like `this`.

And a full code-block looks like this:
```
#!/bin/bash
echo "wabi sabi" > /dev/null
for i in $(cat entries.txt); do ping $i; done
exit
```

---
# Block-quotes

> This is a block-quote!


Here's a sentence with a footnote. [^1]

[^1]: This is the footnote. 

---
# Tables
|Column 1| Column 2|Column 3 |
|-|-|-|
| row 2 | cell 5 | text |
| A cell with a bit more | text to test the scaling| of tables. |

---
# Links & Images
[Links:](https://repping.github.io)
```
[Links:](https://repping.github.io)
```
Images:
```
![Alt-text of image.](http://www.richardeppingbroek.nl/assets/images/88x88.png)
```
![Alt-text of image.](http://www.richardeppingbroek.nl/assets/images/88x88.png)

---
# What more?
