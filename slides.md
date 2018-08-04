class: center, middle

# Web Components Aren't .weird[Weird] Anymore

### Matt Steele

---
class: bigimg, middle

![img](assets/contact1.jpg)

---
class: bigimg, middle

![img](assets/contact4.jpg)

---
class: bigimg, middle

![img](assets/contact2.jpg)

---
class: bigimg, middle

![img](assets/contact3.jpg)

---

class: center, middle

# .weird[Weird]ness

---
class: center, middle

# Web Components

--

## (Custom HTML Elements)

--

## They Are Awesome

---

# Demo - Joy-Con component

---

# They Just Work
--

- Easy to use
???
No compile or Webkit necessary
--

- Uses the platform
--

- Works everywhere

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

# .weird[Weird] stuff jettisoned

---

# .weird[Weird] stuff jettisoned

* ~~HTML Imports~~ ➡️ ES Modules
--

* ~~Bower~~ ➡️ NPM
--

* Webpack ✅

---
class: image-list, center, middle

# Browser Implemented

![chrome](assets/chrome.png)
![safari](assets/safari.png)
![firefox](assets/firefox.png)

---

# Vanilla Custom Elements

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
class: image-list, center, middle

# Or add some sugar

![polymer](assets/polymer.png)
![skate](assets/skatejs.png)
![nutmeg](assets/nutmeg.png)
![stencil](assets/stencil.png)

---

# Stencil

![stencil](assets/stencil.png)

* Code with TypeScript
* Use JSX
* Reactive Data Binding
* Disappearing Framework

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

# Github-Driven-Development

![github](assets/github.png)

---

# Others are using it

- 📹 YouTube 
- 🚂 UPRR 
- ✨ Stellar 

---
class: center, middle

# Try Web Components Out

## It's better than an eyeball full of glass

---
class: center, middle

# Web Components Aren't .weird[Weird] Anymore

## Matt Steele
### @mattdsteele