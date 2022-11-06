# Object-Oriented Programming, HTML Tables

## Domain Modeling

* Explain why we need domain modeling.
  * Domain modeling allows an issue to be resolved by taking the situation and breaking it down into smaller packages, subcategories, and in some cases properties that are to be utilized all in the same encapsulated environment.  This methodology is often represented via object oriented programming.

## HTML Table Basics

* Why should tables not be used for page layouts?
  * Table layouts create issues for visually impaired users as the tags will not match the intent of the page layout or information.
  * Tables can bog things down with far too many tags and there are better methods out there
  * Tables are not automatically responsive and require a bit of work to be useful across multiple platforms
* List and describe 3 different semantic HTML elements used in an HTML `table`
  * table row `tr` - indicates the start or stop of a row in a table
  * table header `th` - indicates header information for that cell (typically row)
  * table data `td` - indicates data information for that cell (typically row)

## Introducing Constructors

* What is a constructor and what are some advantages to using it?
  * A constructor is a specific function which initializes the values (or other methods) within an object which is called upon during object creation (or a new instance).
* How does the term `this` differ when used in an object literal versus when used in a constructor?
  * In a constructor `this` is used to define the properties and methods of an object.  For an object literal, it's used to refer to reference the object itself and is usually a prefix in terms of retrieving a particular property.

## Object Prototypes

* Explain prototypes and inheritance via an analogy from your previous work experience
  * Still a bit fuzzy when it comes to prototypes but inheritance overall and classes allows a particular object to borrow or incorporate properties and methods from existing classes.

## Readings

* [Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)
* [HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)
* [Introducing Constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)
* [Object Prototypes Using A Constructor](https://ui.dev/beginners-guide-to-javascript-prototype)
* [HTML Table Advanced Features and Accessibility](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)
