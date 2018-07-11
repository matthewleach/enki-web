---
author: stefan.stojanovic

levels:
  - beginner
  - basic

type: normal

category: must-know

standards:
  web.markup-text.2: 10

aspects:
  - introduction
  - workout
  - deep

---
# Copyright
---
## Content

Some characters are not easily typed on the keyboard, like the Copyright (©) character.

To display the Copyright symbol, you can use either the HTML entity *number* or the entity *name*.

HTML Entity Number:
```
&#169;
```
Result:
```
©
```

HTML Entity Name:
```
&copy;
```
Result:
```
©
```

Example:
```
<p> Copyright &copy; </p>
```
Result:
```
Copyright ©
```

When using the Copyright symbol in your HTML, it is a best practice to use the corresponding HTML entity vs. cutting and pasting the symbol. Because  even if the symbol renders ok on your browser, it may not render the same on everyone's browser.

---
## Practice

Why can using "&copy;" for a copyright symbol be easier to code?

???

* Because © isn't available on your keyboard.
* Typing © on your keyboard is easier than using "&copy;".
* There is no good way to code the copyright symbol.
* &copy; is smaller in filesize, loading faster.

---
## Revision

What HTML character entity is used to insert a copyright symbol into a document?

???

* &copy;
* @
* ©
* &copyright
* @c

---
## Quiz

### How much do you know about HTML character entities?

What does &copy; display in this line of code?

`<p>The symbol "&copy;" should be pretty easy to recognize.</p>`

* ©
* symbol
* &copy;
* Copyright [current year]
