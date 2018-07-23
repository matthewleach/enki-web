---
author: mihaiberq

levels:

  - beginner

type: normal

category: must-know

inAlgoPool: false

standards:
  web.syntax-html.0: 10
  web.layout-html.0: 10

aspects:
  - introduction

links:
  - '[MDN divisions](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div){documentation}'
  - '[MDN spans](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/span){documentation}'


---

# Divisions and Spans

---
## Content

`<div>`s (short for divisions) and `<span>`s are important HTML elements used for styling. `<div>`s and `<span>`s alone do absolutely nothing without CSS. They do not have any semantic value as they are simple containers that wrap around content (text, images, etc) to help control the layout and styling.

A `<div>` is often used to group larger chunks of content and is often a block element, meaning it has a distinct break before and after it (like paragraphs, headings, etc). 

A `<span>` is often used to group a small chunk of content inside a line (such as styling a few key words inside a paragraph).

Check out this code:
```html
<div>
  <p>A paragraph inside a div.</p>
  <p>An <span>important</span> paragraph
     inside the div. </p>
  <p>A div <div></div> inside a
     paragraph.</p>
</div>
```

Visually, the code above will be rendered this way:

```html
A paragraph inside a div.

An important paragraph inside the div.

A div

inside a paragraph.
```

One difference between `<div>` and `<span>` elements is that you are able to stack multiple `<span>`s on the same line without breaking the layout of the page, while trying to stack `<div>`s will effectively be adding a new line (in the above case, between **div** and **inside**).

When using CSS to style `<div>` and `<span>` elements, ids and classes are often assigned to them in order to uniquely style them. So, it is common to see them written like this where the `<div>` has certain styles assigned to it and the `<span>` changes the style of the text within that paragraph. 

```html
<div id="callout">
  <p>This is 
   <span class="highlight>
     important
   </span> to see!
  </p>
</div>
```

---
## Revision

Span's are seen as ??? elements.

* stylistic
* structural
* not
