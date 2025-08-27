# Government Emergency Services Directory

A modern, fully responsive flower shop website built with HTML, CSS and JS. This project demonstrates best practices in responsive design, clean UI, and accessibility for both desktop and mobile users.

---

## 🚀 Live Demo
[View on GitHub Pages](https://shariar-ahamed.github.io/Government-Emergency-Services-Directory/)

---

### 6. Answer the following questions clearly:

1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?
- `getElementById` → Returns **one element** by its unique id.
- `getElementsByClassName` → Returns **all elements** with a specific class (HTMLCollection).
- `querySelector` → Returns **the first element** matching a CSS selector.
- `querySelectorAll` → Returns **all elements** matching a CSS selector (NodeList).

2. How do you **create and insert a new element into the DOM**?  
```
let newEl = document.createElement('div');  
newEl.textContent = "Hello World";  
document.body.appendChild(newEl);  
```
3. What is **Event Bubbling** and how does it work?
- Event starts at the **target element** and then **bubbles up** to its parent elements.
- Example: Click on a button → first button, then div, then body.

4. What is **Event Delegation** in JavaScript? Why is it useful?
- Instead of adding event on each child, we **add event to parent** and catch events from children.
- Useful for **dynamic elements** and improves performance.

5. What is the difference between **preventDefault() and stopPropagation()** methods?  
`preventDefault()` → Stops default **browser action** (like form submit or link click).  
`stopPropagation()` → Stops the event from **bubbling or capturing** further.  
---

