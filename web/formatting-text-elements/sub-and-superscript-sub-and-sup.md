# Sub- & superscript (sub & sup)
author: matthew-leach

levels:
  - beginner
  - basic

type: normal

category: must-know

stub: true

tags:
  - deep


---
## Content

## Content

The HTML `<sub>`, or the ** Subscript** element is used to display some text as subscript (written or printed below the line), whereas the `<sup>`, or the **Superscript** element is used to display some text as superscript (written or printed above the line).

Both elements are only used for typographical reasons and neither should be used for styling and/or appearance only. If you want to style your text sub or superscript, you can use the appropriate CSS properties:
  - `vertical-align: sub`
  - `vertical-align: -25%`
  - `vertical-align: super`
  - `vertical-align: 50%`

For instance, you can use the subscript for properly display the 2 in H20 and you can use the superscript to properly display the 2 in E = mc2.

Example:
```
<p>
  Both 
  H<sub>2</sub>O 
  and 
  E = mc<sup>2</sup>
  are fun to learn about.
</p>
```
![View CodePen](https://codepen.io/enkidevs/pen/xzQvPv)

Furthermore, the most common `<sup>` elements uses are to display exponents (x^2) or ordinal numbers (3rd,4th,5th). On the other hand, the most common use for the `<sub>` element is marking footnotes, variable numbers (X1, X2...Xn) and denoting numbers in chemical formulas.

**Note:** Both `<sup>` and `<sub>` cannot be used at the same time to make a subscript appear directly below a superscript number and vice versa. To do so, you need to use the MathML (Mathematical Markup Language). 

**The MathML elements:** `<msub>`, `<msup>` and `<msubsup>`

---
## Practice

Write the code to properly display the text like this:

<p>Both H<sub>2</sub>O and E = mc<sup>2</sup> are fun to learn about.</p>

`<p>`Both H`<tag1>`2`</tag1>`O and E = mc`<tag2>`2`</tag2>` are fun to learn about.`</p>`

tag1 = ???
tag2 = ???

* sub
* sup
* sum
* sud
* sos

---
## Revision

What element should be used to change the "2" in chemical formulas, like H<sub>2</sub>O)?

???

* sub
* sup
* sum
* sud
* sos

What element should be used to change the "2" in formulas, like E = mc<sup>2</sup>?

???

* sup
* sub
* sum
* sud
* sos

---
## Quiz

How much do you know about text in HTML?

Write the code to properly display the text like this:

<p>I learned about E = mc<sup>2</sup> and H<sub>2</sub>O in school.</p>

`<p>`I learned about E = mc`<tag1>`2`</tag1>` and H`<tag2>`2`</tag2>`O in school.`</p>`

tag1 = ???
tag2 = ???

* sub
* sup
* upper
* lower
* ubase
* lbase
