# Intro dfn
author: matthew-leach

levels:
  - beginner
  - basic

type: normal

category: must-know

stub: true

tags:
  - deep

links:
  - '[CodePen: Element dfn](https://codepen.io/enkidevs/pen/LBxpJo){code}'
  - '[CodePen: Element dfn & abbr](https://codepen.io/enkidevs/pen/ejgpQj){code}'
  
---
## Content

The HTML `<dfn>` or the **Definition** element is used to specify a term that's being defined within the `<p>`, `<section>` and/or `<dt>`/`<dd>` pairing elements. Also, the `<dfn>` element is usually used to indicate the first use of a term in a document.

Example:
```
<p>
  <dfn>Enki</dfn> is an app 
  that provides daily workouts
  for your dev skills.
</p>
```
Result:

###### --> element-dfn.svg

![View CodePen](https://codepen.io/enkidevs/pen/LBxpJo)

**Note:** The `<dfn>` elements main purpose is to provide semantic meaning. Other than that, it has no special functionality.

Also, the `<dfn>` element has a `title` attribute. If the `title` attribute is present, the content of the `<dfn>` element, which is the value of the `title` attribute, has to be the term being defined and nothing else. 

Furthermore, the `<dfn>` element can have the `<abbr>` element nested inside it. If the `<dfn>` element has a single `<abbr>` element with a `title` attribute nested inside it, then the value of the `<abbr>` elements `title` attribute is the term being defined.

Example `<abbr>`:
```
<p>
  <dfn>
   <abbr 
    title="Hypertext Markup Language">
   HTML
   </abbr>
  </dfn> 
  is the standard markup language 
  for creating web pages.
</p>
<p>... later in the document...</p>
<p>
  After a few hours, 
  I was finally able to understand 
  <abbr 
   title="Hypertext Markup Language">
   HTML
  </abbr>
  !
</p>
```
Result:

###### --> element-dfn-abbr.svg

![View CodePen](https://codepen.io/enkidevs/pen/ejgpQj)


---
## Practice

Mark the following statements that are true regarding the `<dfn>` element.

```
<p><dfn>Enki</dfn> is an app providing daily workouts for your dev skills.</p>
```

+ `<dft>` defines a term when it is being described.
+ Typically, `<dft>` is applied when term is used for the first time
- Useful to apply element each time term is referred. 
- Common to use `<abbr>` with `<dfn>` for all abbreviation's expansion.

---
## Revision

Which HTML element is used to indicate the first use of a term in a document?

???

* dfn
* dir
* item
* id
* term

---
## Quiz

How much do you know about formatting text elements?

From the follow code, match the proper HTML elements with the tags: 

`<p>``<tag1>``<tag2 title="Hypertext Markup Language">`HTML`</tag2>``</tag1>` is the standard markup language for creating web pages.`</p>`
`<p>`... later in the document...`</p>`
`<p>`After a few hours, I was finally able to understand `<tag2 title="Hypertext Markup Language">`HTML`</tag2>`!`</p>`

tag1: ???
tag2: ???

* dfn
* abbr
* wbr
* desc
* id
* term
