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
  - '[MDN docs for globat attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes){website}'

---
# Important (b & strong)
---
## Content

The HTML `<b>`, or the ** Bring Attention To** element is used to bring readers attention to some text and `<strong>`, or the **Strong Importance** element, is used to give importance to some content.

The `<b>` element was also formerly known as the **Boldface element**.

Example:
```
<p>
  <strong>Warning</strong>: 
  The latest 
  <b>iPhone</b> is expensive.
</p>
```
Result:

**Warning**: The latest **iPhone** is expensive.

The HTML `<strong>` and `<b>` elements appear similar since they both have the same default styling, **bold**, but they both identify the content differently.   

Example:
```
<strong>
  Attention!
</strong>
The floor is 
<b>slippery</b> 
 and <b>wet</b>!
```
Result:

**Attention!** The floor is **slippery** and **wet**!

In the above example, the `<strong>` element is used to specify that the word `Warning` is very important and the `<b>` element is used to give attention to a text `iPhone` without giving it a higher importance. 

Rather than wrapping `<b>` or `<strong>` elements around text that is only meant to be used for visually styling purposes, it is more appropriate in those cases to use the CSS property `font-weight:bold;`.

---
## Practice

Write the code to properly express extra importance on key words in this sentence: 

`<p>`<???>Warning<???>: The latest <???>iPhone<???> is expensive.`</p>` 

* strong
* /strong
* b
* /b
* em
* /em
* i
* /i


---
## Revision

When text needs to bring users attention, you should use which element?

???

When a text needs to be presented with strong importance, seriousness, or urgency for its contents, you should use which element?

???

* `<b>`
* `<strong>`
* `<em>`
* `<i>`
* `<important>`

---
## QUIZ

### How much do you know about HTML text?

Write the code to properly express extra importance to key words : 

```
<h2>Things To Do</h2>
<ul>
  <li>
    <???>Do Now:<???> Call Mum
  </li>
  `<li>`Buy <???>Lord of the Flies<???>
      book`
   </li>`
  <li>
    Fix screen on
    <???>iPhone<???>
  </li>
</ul>
```

* strong
* /strong
* em
* /em
* b
* /b
* cite
* /cite
* i
* /i

