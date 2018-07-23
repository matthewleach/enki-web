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
  - '[CodePen: Element small](https://codepen.io/enkidevs/pen/NBdxNX){code}'
  - '[CodePen: Element small (headings)](https://codepen.io/enkidevs/pen/OwWMbj){code}'
  - '[MDN docs for globat attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes){website}'
  
---
# Small
---
## Content

The HTML `<small>` element, often referred to as `fine print` is used to change the font size of some text to one size smaler(from large to medium or medium to small, etc.), up to the smallest size the browsers allows.

This element is used for adding short phrases or comments, short blocks of text, a copyright notice or other legal text.

Example:
```
<p>Enki is an educational 
technology company.</p>
<hr>
<p><small>The content is licensed 
under a <a rel="license" href="#">
Creative Commons License</a> and 
by using this site, you agree to 
our <a href="#">Terms of Use</a>
and our <a href="#">Privacy Policy
</a></small>.</p>
```

##### --> element-small.svg

![View CodePen](https://codepen.io/enkidevs/pen/NBdxNX)

By default, the font-size is generally set to .8em smaller than the existing text, which is also often 1 font size smaller. In this example the Test text will display at the same size:

```
<h1><small>Test</small></h1>
<h2>Test</h2>
```
##### --> element-small-headings.svg

![View CodePen](https://codepen.io/enkidevs/pen/OwWMbj)

---
## Practice

Select the false statement about the `<small>` element. 

???

* Typical to mark up full 'Terms of Use' page.
* Changes the text font size one size smaller.
* Often referred to as "fine print".
* Best to add to phrases or short block of text.
* Useful around copyright notice

---
## Revision

What HTML element is used to make the text font size one size smaller?

???

* `<small>`
* `<smaller>`
* `<text-size>`
* `<sp>`
* `<fp>`
* `<sub>`
* `<sup>`

---
## Quiz

### How much do you know about formatting text elements?

What does the `<small>` element set the selected text to?

```
<p>
    Some actors change their names,
    like Tom Cruise 
    <small>Tom Mapother</small>.
</p>
```

* one size smaller. 
* smaller and half a character below line of text.
* smaller and half a character above line of text.
* to the smallest display size.
* to the font-size of 10px.
