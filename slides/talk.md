# TypeScript

---

# 👨👩 + JS = 😠 ? <!-- .element: class="fragment" -->
# 👨👩 + JS = 😐 ? <!-- .element: class="fragment" -->
# 👨👩 + JS = 😍 ? <!-- .element: class="fragment" -->

Note:
- Hands up if...

---

# Overview

- A Brief History of JavaScript <!-- .element: class="fragment" -->
  - Early JS Design Goals <!-- .element: class="fragment" -->
- What is TypeScript? <!-- .element: class="fragment" -->
- Why TypeScript? <!-- .element: class="fragment" -->
- 👍 & 👎 <!-- .element: class="fragment" -->
- Demo <!-- .element: class="fragment" -->

Note:
- First up...

---

# A Brief History of JavaScript <span class="fragment" data-fragment-index="1">*</span>

<small span class="fragment" data-fragment-index="1">* Simplified</small>

---

- Invented - 1995
- Standardized as ECMAScript (ES1) - 1997 <!-- .element: class="fragment" -->
- ES2 - 1998 <!-- .element: class="fragment" -->
- ES3 - 1999 <!-- .element: class="fragment" -->
- ES4 - Abandoned <!-- .element: class="fragment" -->
- ES5 - 2009 <!-- .element: class="fragment" -->
- ES6 - 2015 <!-- .element: class="fragment" -->
- ES7 - 2016 <!-- .element: class="fragment" -->

---

## Early JS Design Goals

<small>The impetus was the belief on the part of at least Marc Andreessen and myself, along with Bill Joy of Sun, that HTML needed a "scripting language", a programming language that was **easy to use** by amateurs and novices, where the code could be **written directly in source form as part of the Web page markup**. We aimed to provide a **"glue language"** for the Web designers and part time programmers who were building Web content from components such as images, plugins, and Java applets. We saw Java as the "component language" used by higher-priced programmers, where the glue programmers -- the Web page designers -- would assemble components and automate their interactions using JS. - Brendan Eich</small>

Note:
- Designed to be forgiving
- Tries to keep running. e.g. 5 + 'George' = '5George'

---

# What is TypeScript?

> "A typed superset of JavaScript that compiles to plain JavaScript" - [TypeScript](https://www.typescriptlang.org)

> "JavaScript that scales" - [TypeScript](https://www.typescriptlang.org)

Note:
- Microsoft describes TypeScript as...
 - Types: Declare a variable
 - superset

---

# Why TypeScript?

- Remember the design goals? <!-- .element: class="fragment" -->
- <span class="fragment">The Web is <del>Major</del>.Minor.Patch</span>

Note:
- TypeScript smoothes over some rough edges
- Why might it need to do that?
  - Additive only
  - Foot guns will always be there
  - Has one huge advantage. See http://www.warnerbros.com/archive/spacejam/movie/jam.htm

---

# 👍 & 👎

<small>(Pros & Cons)</small>

---

## 👍

- Gradual typing <!-- .element: class="fragment" -->
- Works with many popular libraries! <!-- .element: class="fragment" --> [definitelytyped.org](http://definitelytyped.org) <!-- .element: class="fragment" -->
- Developer tooling 😍 <!-- .element: class="fragment" -->

Note:
- Gradual typing
  - Allows you to gradually add types to your code. Don't need to rewrite your projects
  - Add types where they're needed
- If a library has definitions, TypeScript can work with it
- As you'll see in a moment, dev tooling is 👍

---

## 👎

- Gradual typing 🤔 <!-- .element: class="fragment" -->
- Doesn't work with some libraries <!-- .element: class="fragment" -->

Note:
- Gradual typing
  - Not strict, effectiveness is on the developer.
- Not all libraries and frameworks are supported. They need to be kept up to date.

---

# Demo

## 🔥💻🔥

---

# Projects using TypeScript

- [TypeScript](https://github.com/Microsoft/TypeScript)
- [Glimmer 2](https://github.com/tildeio/glimmer)
- [VS Code](https://github.com/Microsoft/vscode)
- [Trending on GitHub](https://github.com/trending/typescript)

---

# Slides

[leighwilliams.github.io/typescript-talk/](http://leighwilliams.github.io/typescript-talk/)

---

# References

https://en.wikipedia.org/wiki/ECMAScript
http://www.computerworld.com.au/article/255293/a-z_programming_languages_javascript/

---

# Resources

- [typescript.org](https://www.typescriptlang.org)
- [Types - Gary Bernhardt](https://gist.github.com/garybernhardt/122909856b570c5c457a6cd674795a9c)
