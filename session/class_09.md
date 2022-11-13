# Forms and JS events

## HTML

* Why are forms so important in web development?
  * Forms are one of the main points of interaction between a user and an app.
* When designing a form, what are some key things to keep in mind when it comes to user experience?
  * Keep it as simple as possible
  * Make buttons easy to find and readable (make deletion buttons more difficult)
  * Not everything needs to be on the screen for longer forms
  * Single-column vs. double (portrait vs. landscape)
  * Will a mask be used for the field?
  * Not every field needs a placeholder
* List 5 form elements and explain their importance.
  * form - mostly a semantic element used to define that the enclosed section is a form
  * fieldset - a semantic element used to group together several input fields in a form
  * legend - the description or title given to a fieldset
  * label - the label attached to an input field that the user can see (typically)
  * input - the element which accepts user input via a field or toggle


## JS

* How would you describe events to a non-technical friend?
  * Anything that happens with a time or user-input component
* When using the `addEventListener()` method, what 2 arguments will you need to provide?
  * What to listen for and a pointer to the code to execute when the event occurs
* Describe the event object. What is the target within the event object useful?
  * The event object is an object created when the event occurs and the target is where the event is coming from.
* What is the difference between event bubbling and event capturing?
  * Bubbling triggers from the innermost element and expands to the outer elements
  * Event capturing triggers from the outer elements and then the domain shrinks to the location of the event.

## Readings

* [HTML Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)
* [1st Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)
* [How to Structure a Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)
* [Java Script](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
* [Introduction to Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)
* [HTML5 Input Types](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)
* [Event Reference and Listenings](https://developer.mozilla.org/en-US/docs/Web/Events)