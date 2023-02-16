# HTML Forms

1. Why are forms so important in web development?
**Web forms are one of the main points of interaction between a user and a website or application. Forms allow users to enter data, which is generally sent to a web server for processing and storage. or used on the client-side to immediately update the interface in some way**

2. When designing a form, what are some key things to keep in mind when it comes to user experience?
**Designing a quick mockup will help you to define the right set of data you want to ask your user to enter. From a user experience (UX) point of view, it's important to remember that the bigger your form, the more you risk frustrating people and losing users.**


3. List 5 form elements and explain their importance.

**The *form* element represents a document section containing interactive controls for submitting information.**

**The *label* element represents a caption for an item in a user interface.**

**The *input* element is used to create interactive controls for web-based forms in order to accept data from the user; a wide variety of types of input data and control widgets are available, depending on the device and user agent.**

**The *textarea* element represents a multi-line plain-text editing control, useful when you want to allow users to enter a sizeable amount of free-form text**

**The *button* element is an interactive element activated by a user with a mouse, keyboard, finger, voice command, or other assistive technology. Once activated, it then performs an action, such as submitting a form or opening a dialog**

## Intro to Events

***
1. How would you describe events to a non-technical friend?

**fired to notify code of "interesting changes" that may affect code execution. These can arise from user interactions such as using a mouse or resizing a window, changes in the state of the underlying environment**

2. When using the addEventListener() method, what 2 arguments will you need to provide?

**the name of the event we want to register this handler for, and the code that comprises the handler function we want to run in response to it.**

3. Describe the event object. Why is the target within the event object useful?

 **it is automatically passed to event handlers to provide extra features and information.property of the event object is always a reference to the element the event occurred upon. So, in this example, we are setting a random background color on the button, not the page.**

4. What is the difference between event bubbling and event capturing?

**Event bubbling describes how the browser handles events targeted at nested elements. Event caputuring is like event bubbling but the order is reversed: so instead of the event firing first on the innermost element targeted, and then on successively less nested elements, the event fires first on the least nested element, and then on successively more nested elements, until the target is reached.**

[HTML5 Input Types](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)

[Event Reference and listings](https://developer.mozilla.org/en-US/docs/Web/Events)