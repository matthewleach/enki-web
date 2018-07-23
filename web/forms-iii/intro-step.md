---
author: stefan.stojanovic

levels:
  - beginner
  - basic

type: normal

category: must-know

standards:
  web.html-forms.0: 10
  web.html-forms.7: 10

aspects:
  - introduction
  - workout
  - deep
  
links:
  - '[CodePen: Step Attribute](https://codepen.io/enkidevs/pen/gKZKKK){code}'

---
# Intro step
---
## Content

The HTML input form `step` attribute is used to specify a *legal* number interval for the `<input>` element.

For instance, if you set `step="4"`, the legal numbers could be -4, 0, 4, 8, etc.

Example:
```
<form
  action="/action.php">
  <input
    type="number"
    name="points"
    step="4">
  <input
    type="submit">
</form>
```

##### --> intro-step.svg

![View CodePen](https://codepen.io/enkidevs/pen/gKZKKK)

The `step` attribute is easy to assign with the `number` input adn works with any positive floadint point value (.1, .5, 1.667, etc). The `step` attribute can also work together with `min` and `max` attributes to create a range of legal values. When a value isn't assigned, it will often start at 0 or the min value.

If you want to accept any value regardless of how many decimal places, you can set the `step` value as `any`.

---
## Practice

Which statement is NOT true regarding step attributes within forms?

???

* Can step between both numbers and letters. 
* Works with fractions, like 1/2 written as ".5".
* Specifies the legal number intervals for an `<input>` element.
* Can be used with min & max to create range of legal values.
* Works with these input types: number, date, & time.

---
## Revision

Which form attribute allows a number to be entered in a specified interval, such as (-5, 0, 5, 10, etc)?

```
<form
  action="file.php">
 <input
  type="number"
  name="points"
  ???="5">
  <input
  type="submit">
</form>
```

* `step`
* `range`
* `gap`
* `space`
* `span`

---
## Quiz

### How much do you know about restricted numbers in HTML form fields?

Which values would be accepted by this input field?

```
<form
  action="file.php">
 <input
  type="number"
  name="points"
  step="5">
 <input
  type="submit">
</form>
```

???

* `-5, 0, 5, 10`
* `1, 2, 3, 4, 5`
* `0, 1, 2, 3, 4, 5`
* `5, 6, 7, 8, 9`
