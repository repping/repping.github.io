---
marp: true
header: ' '
---
# Lists

<style>
/* @import "./template.css"; */

h1 {
  font-family: 'HelveticaNeue-Light', 'Helvetica Neue Light', 'Helvetica Neue', Helvetica, Arial, 'Lucida Grande', sans-serif;
  font-weight: 400;
  font-size: 60px;
  color: #0f0f0f;
}

header {
  background: url("./bild_black.png") no-repeat right 50px top 10px;
  background-size: 40%;
  /* background-color: #0f0f0f; */
  position: absolute;
  /* box-shadow: 10px 15px 40px; */
  left: 980px;
  right: 0px;
  height: 120px;
  width: 300px;
}

section {
  background: radial-gradient(circle, rgba(255,255,255,1) 0%, rgba(210,210,210,1) 100%);
}

.two-column {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-gap: 10px;
  text-align: left;
}

</style>

<div class="two-column">
  <div>

- punt aaaaaaaaaaaaaaaaaaaaaaaaaaaaa
- punt b
  - punt b2  
  </div>
  <div>

1. punt 1111111111111111111111111111111
2. punt 2
   1. punt 2b
   
  </div>
</div>


  <br>

---
# Emoji's!
Many more shortcodes @ [source](https://gist.github.com/rxaviers/7360908)
||||
|---|---|---|
| :bowtie: `:bowtie:` | :smile: `:smile:` | :laughing: `:laughing:` |
| :blush: `:blush:` | :smiley: `:smiley:` | :relaxed: `:relaxed:` |
| :smirk: `:smirk:` | :heart_eyes: `:heart_eyes:` | :kissing_heart: `:kissing_heart:` |
| :kissing_closed_eyes: `:kissing_closed_eyes:` | :flushed: `:flushed:` | :relieved: `:relieved:` |
| :satisfied: `:satisfied:` | :grin: `:grin:` | :wink: `:wink:` |
| :stuck_out_tongue_winking_eye: `:stuck_out_tongue_winking_eye:` | :stuck_out_tongue_closed_eyes: `:stuck_out_tongue_closed_eyes:` | :grinning: `:grinning:` |
| :kissing: `:kissing:` | :kissing_smiling_eyes: `:kissing_smiling_eyes:` | :stuck_out_tongue: `:stuck_out_tongue:` |
| :sleeping: `:sleeping:` | :worried: `:worried:` | :frowning: `:frowning:` |
| :anguished: `:anguished:` | :open_mouth: `:open_mouth:` | :grimacing: `:grimacing:` |
| :confused: `:confused:` | :hushed: `:hushed:` | :expressionless: `:expressionless:` |
| :unamused: `:unamused:` | :sweat_smile: `:sweat_smile:` | :sweat: `:sweat:` |
| :disappointed_relieved: `:disappointed_relieved:` | :weary: `:weary:` | :pensive: `:pensive:` |
| :disappointed: `:disappointed:` | :confounded: `:confounded:` | :fearful: `:fearful:` |
| :cold_sweat: `:cold_sweat:` | :persevere: `:persevere:` | :cry: `:cry:` |
| :sob: `:sob:` | :joy: `:joy:` | :astonished: `:astonished:` |
| :scream: `:scream:` | :neckbeard: `:neckbeard:` | :tired_face: `:tired_face:` |
| :angry: `:angry:` | :rage: `:rage:` | :triumph: `:triumph:` |
| :sleepy: `:sleepy:` | :yum: `:yum:` | :mask: `:mask:` |
| :sunglasses: `:sunglasses:` | :dizzy_face: `:dizzy_face:` | :imp: `:imp:` |
| :smiling_imp: `:smiling_imp:` | :neutral_face: `:neutral_face:` | :no_mouth: `:no_mouth:` |

---
# Headings and Emphasis
## Heading 2
*Normal paragraph! cursive with a*
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

# Block-quotes

> This is a block-quote!


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
