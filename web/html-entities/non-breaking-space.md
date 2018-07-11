---

author: stefan.stojanovic

levels:
  - beginner
  - basic

type: normal

category: must-know

standards:
  web.markup-text.2: 10

aspects:
  - introduction
  - workout
  - deep
  
---
# Non-breaking Space

---
## Content

In HTML, the non-breaking space is a character entity which can:

* Create white space between words or web page elements
* Stop the browser from breaking a line in the wrong place.

To insert a non-breaking space you would use either the HTML entity *name* or the HTML entity *number* :

HTML Entity Number
```
&#160;
```
HTML Entity Name
```
&nbsp;
```
**Prevent Line Break with Non-Breaking Space**

A common use for the non-breaking space is putting it before any numeric (or alphabetic reference) to prevent awkward breaks.

WRONG: 
```
Under Security Law §
1893 purchases can be made. ¶
23 of the contract provides details.
```

CORRECT: 
```
Under Security Law
§ 1893 purchases can be made.
¶ 23 of the contract provides details.
```

By default, two images placed together in a webpage will visually touch. When a single space should be used to separate them, a non-breaking space can be used like this: 

Without &nbsp:
```
<img src="rhino.png"/>
<img src="elephant.png"/>
```

Result:

##### -> nbsp-without-rhino-elephant.svg

With &nbsp:
```
<img src="rhino.png"/>
  &nbsp;
<img src="elephant.png"/>
```

Result:

##### -> nbsp-with-rhino-elephant.svg

**Prevent Table Cell Collapse with Non-Breaking Space**

If you have a table with an empty cell within your web page, you should insert the non-breaking space HTML coding in the empty cell to prevent the cell from collapsing.

```
<table>
  <tr>
    <td>&nbsp;</td>
    <td>Product A</td>
    <td>Product B</td>
  </tr>
  <tr>
    <td>Option 1:</td>
    <td>&nbsp;</td>
    <td>•</td>
  </tr>
  <tr>
    <td>Option 2:</td>
    <td>•</td>
    <td>&nbsp;</td>
  </tr>
</table>
```

##### --> nbsp-table.svg

**Note:** Do not use multiple non-breaking spaces to create larger spaces. If additional space is necessary, then CSS should be used.  


---
## Practice

Which statement is true regarding a non-breaking space:

???

* Prevents an empty cell in a table from collapsing in some browsers.
* Useful for creating indented paragraphs.
* Long strings of them are good ways of creating gaps of space.
* They are easier to read than a space character.

---
## Revision

What HTML character entity is used to prevent the browser from breaking the line between certain words or web page elements?

`<p>5???km</p>`

* &nbsp;
* &ensp;
* &ltsp;
* empty space: " "
* &space
* &gap

---
## Quiz

### How much do you know about displaying images?

What does the "&nbsp;" within this line of code do?

```<img src="image1.png" alt="">
&nbsp;
<img src="image2.png" alt="">```

* Adds an empty character of space between the images.
* Prevents the images from starting on new line like word wrap.
* Removes any space between the images.
* Useful when pulling image files from a database.
