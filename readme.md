# Question 1 : What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

> When we use getElementById in JavaScript, it can only select one element at a time. Even if we accidentally give the same ID to multiple elements in wer HTML, JavaScript will only grab the first one it finds and ignore the rest.

> getElementsByClassName lets us select all the elements in our HTML that share the same class. Instead of just one element, it gives back an HTML collection containing all of them.

> querySelector is a method that help us to  select a single element from our HTML, and it works just like a CSS selector. example, we use a hash (#) to target an ID and a dot (.) to target a class, just like in CSS.

> querySelectorAll selects all elements that match a CSS selector (using . for classes and # for IDs) and returns them as a NodeList.

# Question 2 : How do we create and insert a new element into the DOM?

To create a new DOM element, we use document.createElement("tagName") with the tag name in quotes. Then, to display it on the page, we can attach it to the DOM using something like document.body.appendChild(element) or by appending it inside another existing element.

# Question 3 : What is Event Bubbling and how does it work?

Event bubbling is when we use click event or any event on child element then it is first applied on child element then applied on parent element and then applied on grant element then on document then on window and this the Event bubbling.

# Question 4 : What is Event Delegation in JavaScript? Why is it useful?

Event Delegation is a technique that takes advantage of event bubbling. Normally, when we click an element, the event travels up through its parents all the way to the document. With event delegation, instead of attaching events to many child elements, we attach a single event listener to a parent element and use it to handle events for its children. This way, the event only applies to the element that was actually clicked (the target).

# Question 5 : What is the difference between preventDefault() and stopPropagation() methods?

> When we work with an HTML form and submit the form, it automatically reloads, and to stop it, we use the Prevent default method.
to stop this continues issue we use the preventDefault() to stop this reload issue.

> Event propagation is when an event moves from the element it occurred on up to its parent elements. We can use event.stopPropagation() to stop this, so the event doesn’t affect the parent elements.# B12-A5-Emergency-Hotline
