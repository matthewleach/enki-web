---
author: stefan.stojanovic

levels:
  - beginner
  - basic

type: normal

category: must-know

standards:
  web.semantic-html.0: 10
  web.semantic-html.1: 10
  web.semantic-html.3: 10
  web.markup-text.2: 10
  web.layout-html.3: 10

aspects:
  - introduction
  - workout
  - deep

link:
  - '[CodePen: samp Element](https://codepen.io/enkidevs/pen/BVqOJr){code}'
  - '[MDN Docs for samp](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/samp){website}'

---
# samp - Sample Output Element
---
## Content

The HTML `<samp>`, or the **Sample Output** element, is used to represent a sample output from a computer program.

Example:
```
<p>This is the crazy error I got:</p>
<p><samp>Keyboard not found<br>
  Press F1 to continue</samp></p>
```

Result:

##### --> samp-element.svg

The default font style for the `<samp>` element for most browsers is the monospace font.

By adding CSS styles, the `<samp>` element can be used to present the sample output from a computer program in much better ways. 

##### --> samp-element-styled.svg

![View CodePen](https://codepen.io/enkidevs/pen/BVqOJr)


---
## Practice

When using the `<samp>` element, which statements are true?

???
???

+ represents sample output from a computer program
+ displayed in the browser's default monospace font
- produces a block element
- represents preformatted text
- represents user input

---
## Revision

What HTML element wraps around sample output text from a computer program to identify it differently?

???

* samp
* code
* kbd
* pre
* var
* out
* output

---
## Quiz

### Do you know which HTML element is best to substitute for "???" within this code:  

`<p>`My first selection within Enki was wrong as it displayed the alert `<???>`Oh no... This is a wrong answer`</???>`.`</p>`

???

* samp
* /samp
* code
* /code
* pre
* /pre
* out
* /out
* output
* /output
