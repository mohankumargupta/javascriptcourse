---
# You can also start simply with 'default'
theme: academic
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
#background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: HTML and DOM
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
layout: cover
# open graph
# seoMeta:
#  ogImage: https://cover.sli.dev
---

# HTML and DOM



<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Press Space or <carbon:arrow-right /> for next page 
</div>

<div class="abs-br m-6 text-xl">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="slidev-icon-btn">
    <carbon:edit />
  </button>
  <a href="https://mohankumargupta.github.io/javascriptcourse" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
title: HTML and DOM
---

# HTML and DOM

<br><br><br>

<Youtube id="J-02VNxE7lE" />


---
title: What is DOM?
---

# What is DOM?

**Document** **Object** Model.

The two important words: document and object.



But first, what document? Answer, HTML Document on disk eg. index.html

What object? Answer, a Javascript object that we can access so that we can modify what we see on webpage.

```html
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Example</title>
  </head>
  <body>
    <h1>Heading 1</h1>
    <p> Some text </p>
  </body>
</html>
```

Is the index.html the DOM? NO!

If not, how does this document relate to the DOM?


---
title: What problem is the DOM trying to solve?
---

# What problem is the DOM trying to solve?

Have a HTML element on webpage that I want to modify with javascript. 

```html
<p> Some text </p>
```

In order, to change the webpage, need to change the DOM. As soon as you change the DOM, the webpage changes.

Need access to a javascript variable that gives me access to the DOM.

That javascript variable is called **document**.

```js
console.log(document);
```

What type is this variable? 
Is it a number or a string?
Or is it something else?

```js
console.log(typeof(document));
```

Answer: object

That is the object in DOM


---
title: Difference between DOM and HTML
---

HTML(index.html) is dead/set in stone. It can be described as "initial page view".

The DOM is a breathing living entity. It is the live view and it can be different from the "initial page view". It can be described as "current page view".

The HTML and the DOM can be out of sync only because javascript has altered the DOM and hence the webpage.

---
title: Mental model of DOM
---

# Mental model of DOM

The DOM is always described as a tree.

![DOM Tree MDN](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Using_the_Document_Object_Model/using_the_w3c_dom_level_1_core-doctree.jpg)

![DOM Tree w3schools](https://www.w3schools.com/js/pic_htmltree.gif)



