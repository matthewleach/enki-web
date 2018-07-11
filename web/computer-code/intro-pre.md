---
author: stefan.stojanovic

levels:
  - beginner
  - basic

type: normal

category: must-know

standards:
  web.markup-text.2: 10
  web.layout-html.4: 10

aspects:
  - introduction
  - workout
  - deep
---
# pre - Preformatted Text
---
## Content

The HTML `<pre>`, or the **Pre-formatted Text** element, is used to display text exactly as it is within the HTML file. This means that text and all the spaces within the `<pre>` element will all be displayed in the space exactly. This is useful since HTML typically ignores multiple spaces. 

Example:
```
<pre>.enki-highlight {
  color: #F46C43;
 }
</pre>
```

Result:
##### --> pre-element.svg

In the example above, the `<pre>` element is used to display some sample CSS code within the HTML with the appropriate spaces, which otherwise would be taken out by the browser. As you can see, the text within the `<pre>` element is set to display as a monospace font by default.

Using the `<pre>` and `<code>` elements together with a little CSS can really improve the presentation of your code within your web pages.

##### --> pre-element-styled.svg

![View CodePen](https://codepen.io/enkidevs/pen/BVqPgZ)

**Note:** Since all spaces within the `<pre>` element are used, pay attention to adding any unnecessary spaces or hard returns after the opening tag. 

Bad Example as an extra hard return will display at the top of the code sample in the HTML page:
```
<pre>
 .enki-highlight {
  color: #F46C43;
 }
</pre>
```

Good Example as the displayed code is written immediately after the opening tag:
```
<pre>.enki-highlight {
  color: #F46C43;
 }
</pre>
```

---
## Practice

Which is true about the `<pre>` element?

???

* Shows the content exactly as it is formatted, including whitespace and line breaks
* produces an inline element
* represents user input
* represents sample output
* whitespace is removed

---
## Revision

What HTML element is used to display the text exactly as it is laid out within the element?

???

* pre
* samp
* code
* element
* white-space
* standard
* output

---
## Quiz

### How much do you know about text formatting with HTML elements?

Which HTML element is best used for "???" to properly display this code within a webpage:  

`<???>`
.alert {
  color:red;
}
`<???>`

* pre
* code
* perf
* samp
