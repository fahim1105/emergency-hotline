1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

**ans:** 
**getElementById:**
This is used to find one element on a page by its unique ID.

**getElementsByClassName:**
This is used to find all elements that share the same class name. It returns a list of elements, because many items can have the same class.

**querySelector:**
This is used to find the first element that matches a CSS selector.

**querySelectorAll:**
This is used to find all elements that match a CSS selector.

2. How do you create and insert a new element into the DOM?

**ans:**
I may create a new element with **document.createElement**, then place it in the page by attaching it to another element using methods like **appendChild** or **append**.

3. What is Event Bubbling and how does it work?

**ans:**
Event bubbling means when you do something, like click a button, the event first happens on that button, then goes up to its parent boxes one by one until it reaches the whole page.

4. What is Event Delegation in JavaScript? Why is it useful?

**ans:**
Event delegation means putting an event listener on a parent element instead of each child. When a child is clicked, the event bubbles up to the parent, and the parent handles it.

It is useful because I don’t need to add many event listeners to every small element. It saves memory, makes code faster, and also works for new child elements added later.

5. What is the difference between preventDefault() and stopPropagation() methods?

**ans:**
preventDefault():
Stops the browser from doing its normal action, like opening a link or submitting a form.

stopPropagation():
Stops the event from going up to parent elements, so only the clicked element reacts.