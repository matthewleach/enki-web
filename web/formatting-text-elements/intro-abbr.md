---
author: stefan.stojanovic

levels:
  - beginner
  - basic

type: normal

category: must-know

stub: true

tags:
  - deep
  
links:
  - '[CodePen: Element abbr](https://codepen.io/enkidevs/pen/rrjOGv){code}'
  - '[CodePen: Element abbr Styled](https://codepen.io/enkidevs/pen/rKQEEK){code}'
  - '[MDN docs for global attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes){website}'
  
---
# Intro abbr
---
## Content

The HTML `<abbr>`, or the **Abbreviation** element is used to represent an abbreviation. The element has a `title` attribute which can provide a full description of the abbreviation and nothing else.

The content of the title is often shown in a tooltip when a user hovers over the element.  Also, some browsers add a dotted underline to the content of the element. 

Example:
```
<p>
  Learn all about 
  <abbr 
    title="HyperText Markup Language">
    HTML
  </abbr> 
  using Enki.
</p>
```
Result:

##### --> element-abbr.svg

![View Codepen](https://codepen.io/enkidevs/pen/rrjOGv)

By default, the `<abbr>` element is displayed as an inline element. 

The `<abbr>` element can also be styled with appropriate CSS properties.

##### --> element-abbr-styled.svg

![View CodePen](https://codepen.io/enkidevs/pen/rKQEEK)

Learn all about `HTML` using Enki

---
## Practice

Write the code that provides a full description of the abbreviation for search engines and visually impaired software.

`<p>`Learn all about <??? ???=???>HTML</???> using Enki.`</p>`

* abbr
* title
* "HyperText Markup Language"
* /abbr
* "HyperText Markup Language"
* desc

---
## Revision

Which HTML element is used with abbreviations to provide a full description for search engines and visually impaired software?

???

* abbr
* acronym
* abbrev
* abbreviate
* acro
* desc

---
## Quiz

### How much do you know about the `<abbr>` element?

Mark the false statement regarding the `<abbr>` element: 

??

* Displayed as a block element by default.
* Represents an abbreviation
* Optionally provides a full description of the content.
* Some browsers present the description as a tooltip.
* Displayed as an inline element by default.
* Some browsers add a dotted underline to the content of the element. 



