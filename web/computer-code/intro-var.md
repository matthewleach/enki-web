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

links:
  - '[CodePen: var Element](https://codepen.io/enkidevs/pen/QxZZWR){code}'
  - '[MDN Docs for var](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/var){website}'

---
# Intro var
---
## Content

The HTML `<var>`, or the **Variable** element, is used to represent a name of a variable in either a programming context or a mathematical expression.

Example:
```
<p><var>X</var> = 10<br>
 <var>Y</var> = 2
<p>As you can see:
 <var>X</var> > <var>Y</var>
</p><p>As you can see:
 <var>X</var> >
 <var>Y</var>
</p>
```

Result:

##### --> var-element.svg

The default text style for the `<var>` element for most browsers is monospace and <i>italic</i>.

By adding CSS styles, the `<var>` element can be used to present variables in much better ways. 

##### --> var-element-style.svg

![View CodePen](https://codepen.io/enkidevs/pen/QxZZWR)


---
## Practice

Which statement is not true about using the `<var>` element?

???

 * represents user input
 * represents a variable in a mathematical expression
 * represents a variable in a programming context
 * produces an inline element
 * Default text style is both monospace & italic.


---
## Revision

What HTML element is best to display mathematical expressions or a programming context differently than the surrounding text?

???

* var
* samp
* code
* kbd
* pre
* math
* output

---
## Quiz

### How much do you know about HTML elements?

Which HTML element is best to substitute for "tag" within this code:  

`<p>`A simple equation: `<tag>`x`</tag>` = `<tag>`y`</tag>` + 2`</p>`

tag=???

* var
* samp
* code
* kbd
* pre
* math
* output
