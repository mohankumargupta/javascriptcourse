---
# You can also start simply with 'default'
theme: academic
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
#background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Important HTML Refresher
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

# HTML Refresher



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
title: HTML Elements
---

# HTML Elements

<br><br><br>

<img class="w-full" src="https://wikimedia.org/api/rest_v1/media/math/render/svg/37506127f0730d9b6035530f46c706af4e2319d4"/>


<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/features/slide-scope-style
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
title: HTML Elements can be nested
---

# Nested HTML Elements

HTML elements can contain text content

```html
<p>Some text</p>
```

But it can contain other HTML elements.

```html
<p> <a href="https://www.iana.org/domains/example">More information</a> </p>
```

This is also valid HTML

```html
<p> Click the following link <a href="https://www.iana.org/domains/example">Some link</a></p>
```

So HTML elements can contain either:
* text content
* one or more HTML elements
* a mixture of both

---
title: Attributes
---

# Attributes

Some attributes are global(apply to all HTML elements)

```html
<p id="thisone">Some text</p>

<ul>
  <li class="menuitem firstmenu">Menu One</li>
  <li class="menuitem">Menu Two</li>
  <li class="menuitem">Menu Three</li>
</ul>
```

Some attributes only apply to certain elements

```html
<img src="cookie.png"/>

<a href="https://google.com">Google Search</a>
```