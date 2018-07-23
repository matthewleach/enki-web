---
author: stefan.stojanovic

levels:
  - beginner
  - basic

type: normal

category: must-know

stub: true

tags:
  - introduction

links:
  - '[CodePen: button Element](https://codepen.io/enkidevs/pen/dKQxjM){code}'
  - '[CodePen: Button element with Text & Image](https://codepen.io/enkidevs/pen/VdqZdQ){code}'
  - '[MDN docs for button](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/button){website}'
  - '[MDN docs for global attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes){website}'
  
---
# Button 
---
## Content

The HTML `<button>` element may seem similar to a link `<a>` with a little more default style, but there are key differences: 

* Buttons are best used *within Forms*. 
* Buttons not used within Forms require JavaScript to have any functionality. 

The default `<button>` element looks like this: 

```
<form action="/" method="post">
  <button>Submit</button>
</form>
```

##### --> button-simple.svg

![View CodePen](https://codepen.io/enkidevs/pen/dKQxjM)

In this case, both the button and the input look and behave the same. 

This input...
```
<form action="/" method="post">
  <button>Submit</button>
  <input type="submit">
</form>
```

![View CodePen](https://codepen.io/enkidevs/pen/rryRQp)

The `<button>` element has a slight edge over the `<input>` as both images and text can be placed within it like this: 

```
<button>
  <img src="submit-icon.svg" alt="">
  Submit
</button>
```

##### --> button-image-text.svg

![View CodePen](https://codepen.io/enkidevs/pen/VdqZdQ)

**Note:** Buttons have no default action upon click. This is why they are best tied to forms or advanced uses of JavaScript. 


---
## Practice

Buttons are best used in what relationship of an HTML form?

???

Match the following terms with their descriptions: 

??? are best when they change the web pages.
??? are best when submitting signup or purchase actions.

* inside
* links
* buttons
* outside
* in connection with
* with JS scripts
* actions 
* elements
* href's
* src's

---
## Revision

What action will be taken by default when a `<button>` is clicked?

???

If a button is outside of a form, what must be used to assign an action to it?

???

* Nothing.
* `JavaScript`
* JavaScript is called.
* Link to another web page.
* Link to an existing web page.
* `CSS`
* `<formaction>`
* `the button type`


---
## Quiz

### How much do you know about buttons?

`<button>Submit</button>` in a `<form>`, by default, is identically to what code?

```
<form action="/" method="post">
  ???
</form>
```

* `<input type="submit" value="Submit">`
* `<input type="submit" value="Button">`
* `<input type="button" value="Submit">`
* `<input type="button" value="Submit">`


