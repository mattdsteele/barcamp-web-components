class: center, middle

# Web Components Aren't .weird[Weird] Anymore

### Matt Steele

---

# Analogy (electric car maybe?)

---

# Tech is like that too

---
class: center, middle

# Web Components (nee Custom Elements)

--

## They Are Awesome

---

# Demo - Joy-Con component

---

# They Just Work
--

- They Work Easily
???
No compile or Webkit necessary
--

- They Work Fast
--

- `querySelectorAll` vs jQuery
--

- They Work Everywhere

---
class: center, middle

# Except They _Don't_ Just Work

---

# Web Component .weird[Weirdness]
--

## No One Implemented

![polyfills](assets/ce-v0.png)
???
At least 50k
---
# Web Component .weird[Weirdness]

## Take Me Down To The Polyfill City
---
# Web Component .weird[Weirdness]

## Framework Lock-In

.center[![polymer](assets/polymerjs.jpg)]
???
---
# Web Component .weird[Weirdness]

## Bespoke Tooling

* HTML Imports
* Bower
* Custom Build Tools
---

class: center, middle
# No wonder React won

---
class: bratz, center, middle

# Five Years Later

---

# Weird Tools Jettisoned

---

# Weird Tools Jettisoned

* ~~HTML Imports~~ ➡️ ES Modules
--

* ~~Bower~~ ➡️ NPM
--

* TypeScript, Webpack, Rollup, A-OK

---

# Write "Vanilla" Custom Elements

```javascript
class HelloWorld extends HTMLElement {
  connectedCallback() {
    this.render();
  }

  render() {
    this.innerHTML = `<div>Hello World!</div>`;
  }
}
customElements.define('hello-world', HelloWorld);
```
---

# Or add some sugar

### (polymer, stencil, skate, lit-html, nutmeg, etc)

---

# Stencil

* Code with TypeScript
* Use JSX
* Reactive Data Binding
* No Runtime

---

# Code example: joy-con

---

# Your framework exports them

* Angular Elements
* Vue
* Dojo
* React (with a wrapper)

---

# Use them in your apps

* Great as "leaf nodes"

---

# Or write entire apps with them

* Ionic's PWA Starter Kit

---

# Others are using it

![github](assets/github.png)

---

# Others are using it

- 📹 YouTube 
- ✨ Stellar 
- 🚂 UPRR 

---
class: center, middle

# .weird[Weird] can be good

## Just not for your websites.


---
class: center, middle

# Web Components Aren't .weird[Weird] Anymore

## Matt Steele
### @mattdsteele